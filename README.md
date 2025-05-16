# Ansible_collections_Template

Use this repo to create an ansible collection and add it to U of MN AAP Automaiton Hub

Prerequisites:
- Your CESI Unit has been on-boarded to AAP and you have been added to your team's Org
  - If your team has not been on-boarded you may do so [here](https://tdx.umn.edu/TDClient/31/Portal/Requests/ServiceDet?ID=636)

## How to use this template

1. Click on the Green button above, "Use this template", and select "Create a new repository"
   1. This should go in your own organization
2. **Update** the galaxy.yml file
   1. feel free to use the `namespace: umn_community` to the namespace or create a new one
   2. set `name:` to the name of this collection
3. If you are not creating plug-ins yo u can delete that folder
4. Add your roles to the 'roles' folder
5. (Optional) Adjust the meta/runtime.yml file to reflect which versions of ansible this collection is appropriate for
6. In Either the Github Org or repo, create a Actions Secrete named `AAP_HUB_TOKEN` and the value will come from generating a token [here](https://platform.aapjecq2y5bgr4mu.ansiblecloud.redhat.com/content/api-token)
