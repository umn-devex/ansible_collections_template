# Ansible_collections_Template

Use this repo to create an ansible collection and add it to ansible galaxy to be shared.  See additional information on collections [HERE.](https://docs.oit.umn.edu/tower/Collections/)

Prerequisites:
- You have a [Galaxy account](https://galaxy.ansible.com/).  They are free and leverage your Github.com account.
  - If you don't already have one, go to the [Galaxy](https://galaxy.ansible.com/) site, click on the "Login" icon, this should take you to a page with the github logo, click on it and you will be directed to the github.com login page
  - The default [namespace](https://galaxy.ansible.com/docs/contributing/namespaces.html) will be your github Id, but you can request an additional namespace [here](https://github.com/ansible/galaxy/issues/new?template=New_namespace.md)
- Github Actions enabled or available.

## How to use this template

1. Click on the Green button above, "Use this template", and select "Create a new repository"
   1. This should go in your own organization
2. **Update** the galaxy.yml file
   1. set `namespace:` to the namespace of your galaxy account
   2. set `name:` to the name of this collection
3. If you are not creating plug-ins you can delete that folder
4. Add your roles to the 'roles' folder
5. (Optional) Adjust the meta/runtime.yml file to reflect which versions of ansible this collection is appropriate for
