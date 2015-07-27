# osx-dev-provision

## Ansible provision
### geerlingguy.homebrew
```
- hosts: localhost
  vars:
    homebrew_installed_packages:
      - mysql
  roles:
    - { role: geerlingguy.homebrew }
'''
### [geerlingguy / mac-dev-playbook](http://sweet.io/p/geerlingguy/mac-dev-playbook)
### [ansible-playbooks](https://github.com/MWGriffin/ansible-playbooks)

