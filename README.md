[![Build Status](https://travis-ci.org/dsegurag/ansible-role-pihole.svg?branch=master)](https://travis-ci.org/dsegurag/ansible-role-pihole)

Ansible Role: Pi-hole
==========================

An Ansible Role that runs [Pi-hole](https://pi-hole.net/) using Docker on Linux.

Requirements
------------

This role uses Docker, so you can install it using the `geerlingguy.docker` role.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role is always nice for users too:

    - hosts: servers
      roles:
         - { role: dsegurag.pihole }

License
-------

MIT

Author Information
------------------

This role was created by [Dani Segura](https://www.dsegurag.com/).
