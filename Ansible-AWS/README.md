## Notes
- creating an ec2 instance through AWS with an IAM user.
- I didnt want to print the private key each time it was generated, so I commented it out
- The code tell Ansible to wait until insance is in a running state before moving onto next task
- The exact_count being 1 ensures there is only one instance with the specified tags running, if I run the playbook again, it wont launch any instance

## Pre-requisites
- The IAM user needs to have AdminstratorAccess, then generate access and secret key to be exported inside the .bashrc file on the control machine
  - This authenticates and gives access to AWS services
- The playbook needs modules/libraries to access AWS resources. I made a python3.12 virtual environment to install boto3. Which is used to
  interact and access AWS resources.
- In the playbook I generated a public and secret key, with the secret key stored on the local system to access the ec2 instance.
  
