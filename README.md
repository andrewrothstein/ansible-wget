andrewrothstein.wget
=========
![Build Status](https://github.com/andrewrothstein/ansible-wget/actions/workflows/build.yml/badge.svg)


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
