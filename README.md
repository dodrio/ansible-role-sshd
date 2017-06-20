# sshd

[![Build Status](https://travis-ci.org/m31271n/ansible-role-sshd.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-sshd)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.sshd-blue.svg)](https://galaxy.ansible.com/m31271n/sshd)

Ansible role that setup a secure sshd.

## Requirements

None.

## Role Variables

+ `sshd_port`: `22`
+ `sshd_protocol`: `2`
+ `sshd_permitrootlogin`: `no`
+ `sshd_permitemptypasswords`: `no`
+ `sshd_passwordauthentication`: `no`
+ `sshd_gssapiauthentication`: `no`
+ `sshd_pubkeyauthentication`: `yes`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.sshd
      sshd_port: 8022
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
