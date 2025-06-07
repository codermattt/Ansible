# Ansible
- I used Ansible to execute scripts from an Ubuntu control machine to 3 CentOs remote machines
- each excercise has a different goal and practice concept
- I practiced ad hoc commands and playbooks 

# Prerequisites
- Ansible is a python library, we need to install a python interpreter on our ubuntu control machine
- make sure inventory file has all the remote target machine login details (usernames, private keys, private ip's, etc...)
- generate and edit the ansible.cfg file to stop host key checking, so that it doesn't show the fingerprint prompt when trying to execute the python scripts on the targets
