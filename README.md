# sshd

[![Build Status](https://travis-ci.org/m31271n/ansible-role-sshd.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-sshd)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.sshd-blue.svg)](https://galaxy.ansible.com/m31271n/sshd

Ansible role that setup a secure sshd.

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
    - role: m31271n.sshd
      x: 42
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
