## Notes
- Update group_vars/all file with values declared for ntp server variables
- The values are used in the Debian and Redhat configuration files
  - ntp (network time protocol) adjusts your system clock to match real-world time, which is important for security, logs and distributed systems
  - having multiple servers is useful in case one is down, then there are still other servers that can be used. It also increases fault tolerance and precision by
    confirming time from mutiple servers
- adds a banner file which displays when logging into one of the target machines
- deploys the ntp conf file for Debian and Red Hat respectively, then restarts the ntp service on each to confirm the changes on the service
- also creates a devdata directory, then defines permissions for it in octal format
