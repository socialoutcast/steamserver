# steamserver
Ansible management for steam servers
This tool is designed for CentOS 7 currently.
Several assumptions are made if you are using this tool
   1. You have ssh access to the system you plan to deploy the server on
   2. You have sudo access without requiring a password
   3. You know how to use ansible and deploy it
   4. You know how to setup a server.inv file for the servers you want to deploy to.
Simply clone and either run the playbook on a specific host or create an server.inv file for the inventory.