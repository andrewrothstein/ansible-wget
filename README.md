andrewrothstein.wget
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-wget.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-wget)

Installs wget via the OS package manager.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.wget
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
