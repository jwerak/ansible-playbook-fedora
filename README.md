Ansible playbook: Post Fedora workstation installation 
=========
Post Fedora installation Ansible script for provisioning dev machine.

## Installation
1. Install Ansible:
`sudo dnf install ansible`
2. To execute the playbook:
```
ansible-playbook -i inventory.ini local.yml --ask-become-pass
```
