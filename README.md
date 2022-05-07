# Ansible Playbook - Wordpress Setup using LAMP on Ubuntu:

## Tools Used:
Ansible, Ubuntu, Apache, MySQL, PHP

## Scenario:
Run the Ansible playbook to setup Wordpress website on localhost on an Ubuntu machine.

## How to run:
### 1. Configure the variables:
- Edit the default.yml under vars folder and set values to the variables to make changes to your setup configuration.

### 2. Run the playbook:
- Run the playbook file with the name playbook.yml

```console
ansible-playbook -i [target_inventory_file] -u [remote_user] playbook.yml
```
