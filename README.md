# osx-dev-provision

## Ansible provision

### [How I Fully Automated OS X Provisioning With Ansible](http://il.luminat.us/blog/2014/04/19/how-i-fully-automated-os-x-with-ansible/)

### geerlingguy.homebrew
```
- hosts: localhost
  vars:
    homebrew_installed_packages:
      - mysql
  roles:
    - { role: geerlingguy.homebrew }
```
### [Mac OS X VirtualBox VM Instructions @geerlingguy](https://github.com/geerlingguy/mac-osx-virtualbox-vm)
### [@geerlingguy / mac-dev-playbook](http://sweet.io/p/geerlingguy/mac-dev-playbook)
### [ansible-playbooks](https://github.com/MWGriffin/ansible-playbooks)

