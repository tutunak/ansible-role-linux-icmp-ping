[![Build Status](https://travis-ci.org/tutunak/ansible-role-linux-icmp-ping.svg?branch=master)](https://travis-ci.org/tutunak/ansible-role-linux-icmp-ping)

icmp-ping
=========

Simple icmp ping to particular host

Requirements
------------

Installed ping

Role Variables
--------------

hosts - list hosts for ping

Dependencies
------------

ping

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: icmp-ping, hosts: ['8.8.8.8'] }

License
-------

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Author Information
------------------

Dmitriy Kotov tutunak.com
