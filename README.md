WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role - Base
====================

A base role for elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Handlers
-------------

    sudo restart  # Restart sudo service


Role Variables
--------------

    elao_env: prod  # Environment used in relative roles (dev|prod)


Example Playbook
----------------

    - hosts: servers
      vars:
        elao_env: dev
      roles:
         - { role: elao.base }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
