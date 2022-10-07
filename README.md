Docker Server Ansible Role
==========================

An ansible role to install standalone docker server on CentOS / RHEL, and expose it over TCP/SSH.


Role Variables
--------------

The default varibales are defined in `defaults/main.yml`, (e.g. versions) and should be overriden as convenient.


Dependencies
------------

N/A.

Example Playbook
----------------

Install the role:

    ansible-galaxy install abarrak.rhel_docker_server

Include the role to run the setup tasks:

    - hosts: docker-server
      ansible.builtin.import_role
        name: abarrak.rhel_docker_server

License
-------

MIT.

Author
------

Abdullah Barrak (@abarrak).
