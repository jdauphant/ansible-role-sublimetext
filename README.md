ansible-role-sublimetext
========================

Ansible role to install Sublime Text on Debian, Ubuntu, and Mac OS X.

https://galaxy.ansible.com/list#/roles/3070

# Notes
- Only support sublimetext 3

# Examples

## Install Sublime Text

```yaml
- hosts: all
  roles:
    - role: jdauphant.sublimetext
```

## Install Sublime Text different build version

```yaml
- hosts: all
  roles:
    - role: jdauphant.sublimetext
      sublimetext_build:  3083
```  
