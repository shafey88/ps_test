# Configuring the environment for ansible

## Requirements
Ubuntu 18.04
- python-pip
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- docker
- docker-py

## Build & Run

Clone geerlingguy.nginx role to folder with project
```bash
git clone https://github.com/geerlingguy/ansible-role-nginx.git
```
Build and run:
```bash
ansible-playbook -i inventory.yml playbook.yml
```




