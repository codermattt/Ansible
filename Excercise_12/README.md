## Notes
- adds a new 'geerlingguy.java' role in the provisioning playbook, which was downloaded off galaxy.ansible.com. It has ready-made roles with different use cases
- This new role has tasks which downloads java packages based off the Operating System, it has tasks based off the Operating System
- Downloading roles are good for some tasks, but when we need to configure settings of our system it will be a lot of code to look through and edit
- That is why it is mostly better to write own code
- different values of the ntp variables were defined in the playbook itself and in the
  roles/post-install/defaults/main.yml file to excercise variable precedence
