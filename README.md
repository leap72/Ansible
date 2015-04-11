## WHAT IS ANSIBLE?

Ansible is a radically simple IT automation engine that automates cloud
provisioning, configuration management, application deployment,
intra-service orchestration, and many other IT needs.

It uses for IT automation, deployment and server provisioning so on. It
is a agenless tool that not require to install any additional package on
the target nodes. It communicates via SSH port 22.

Base on my own expereince it is very easy to learn and write the first
ansible playbook or role.

## Ansible Key Components
1. Inventory
2. Playbook
3. Role
4. Ad-Hocs
5. Modules

## INVENTORY
Here's what a plain text inventory file like:
[webservers]
www1.example.com
www2.example.com

[dbservers]
db0.example.com
db1.example.com

## PLAYBOOK
Sample Playbooks
---
- hosts: examplehost
  gather_facts: true
  roles:
    - role: apache
    - role: mysql
    - role: sudo

##  Ad-Hocs
Sample Ad-Hocs
ansible hostname -a "free -m"

