icmp-ping
=========

Simple icmp ping to particular host

Requirements
------------

Installed ping tool

Role Variables
--------------

hosts - list hosts for ping

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: icmp-ping, hosts: ['8.8.8.8'] }

License
-------

MIT

Author Information
------------------

Dmitriy Kotov tutunak.com
