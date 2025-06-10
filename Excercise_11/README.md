## Notes
- Introducing roles: If your playbook has more tasks and functionality. Roles are a cleaner and more structured way of organising your playbook. It makes it
                     easier to read and understand your playbook by simplifying and segregating the content.
- inside the playbook we specify which role to look through for everything the playbook needs
- when the playbook runs, it will know where to look for everything it needs inside the roles/post-install folder like variables, templates, tasks, handlers, etc    


## Pre-requisites
- need to install 'tree' package to organise and visualize content in a tree structure
- create roles folder, then run 'ansible-galaxy init role_name' inside the 'roles' folder, which auto creates the tree structure for the 'role_name'
- copy files, variables, tasks, templates, etc into the specified folders inside the 'role_name' folder
