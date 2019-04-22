# Ansible
Ansible tutorials

- hosts: all
  sudo: yes
  gather_facts: False
  pre_tasks:
   - setup:
       filter: ansible_*
  roles:
   - your_role_here
