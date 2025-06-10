## Notes
- The problem is that everytime the playbook runs, services are restarted, which disrupts the system
- I used handlers to only restart the service after the template module detects a templating change to the conf files
- If no templating change, the services won't get restarted while playbook runs, which is better for the system
