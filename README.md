Docker Server Ansible Role
==========================
[![CI](https://github.com/abarrak/docker-server-role/actions/workflows/ci.yml/badge.svg)](https://github.com/abarrak/docker-server-role/actions/workflows/ci.yml)
[![Release](https://github.com/abarrak/docker-server-role/actions/workflows/release.yml/badge.svg)](https://github.com/abarrak/docker-server-role/actions/workflows/release.yml)

An ansible role to install standalone docker server on CentOS / RHEL, and expose it over TCP/SSH.

Role Variables
--------------

The default varibales are defined in `defaults/main.yml`, and should be overriden as convenient.


Dependencies
------------

N/A.

Example Playbook
----------------

Install the role:

    ansible-galaxy install abarrak.docker_server_role

Include it to run the setup tasks:

    - hosts: docker-server
      import_role:
        name: abarrak.docker_server_role

License
-------

MIT.

Author
------

Abdullah Barrak (@abarrak).
