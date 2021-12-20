andrewrothstein.pivnet
=========
![Build Status](https://github.com/andrewrothstein/ansible-pivnet/actions/workflows/build.yml/badge.svg)

Installs Pivotal's [pivnet-cli](https://github.com/pivotal-cf/pivnet-cli).

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
    - andrewrothstein.pivnet
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
