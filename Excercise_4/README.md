## Notes
- An Ansible configuration file to edit behaviour of Ansible, always in same folder as playbook
  - Disables SSH host key verification, sets the path of the inventory file to current directory
  - Allows Ansible to manage 5 nodes in parallel, saves logs to /var/log/ansible.log
  - Escalates privilege and disables prompt for sudo password
- The db.yaml playbook now uses variable values
