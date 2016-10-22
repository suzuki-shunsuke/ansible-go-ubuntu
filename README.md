go-ubuntu
===========

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-go-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-go-ubuntu)

Install Go on Ubuntu.

https://galaxy.ansible.com/suzuki-shunsuke/go-ubuntu/


Requirements
------------

Nothing.

Role Variables
--------------

* go_use_ppa: Whether use ppa to install go or not. The default value is "no".
* go_upgrade: Whether upgrade go if go has already installed. The default value is "no".

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.go-ubuntu
    go_use_ppa: yes
    go_upgrade: yes
```

License
-------

MIT
