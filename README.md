# lamp_playbook-jenkins

## Playbook
Ansible playbook with roles for instaling and setup LAMP stack. Usage:
```bash
$ ansible-playbook -i inventory.ini playbook.yml
```
## Jenkinsfile
Launching a playbook and checking the existence of a database (postgres). If the database does not exist - loads the dump.

## Jenkinsfile67
Saving a database dump as a Jenkins artifact. And getting random information from the database. The table name is set as a parameter

