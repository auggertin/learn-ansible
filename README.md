Role Name
=========

Learning ansible roles - Day 3.

Requirements
------------

service
debug
template
yum

Role Variables
--------------

vars/main.yml
 - svc_name
 - content_main_loc
 - testurl

Dependencies
------------

No Dependencies

Example Playbook
----------------

    - name: Testing a role
      hosts: webservers
      roles:
      - test_apache

License
-------

BSD

Author Information
------------------

auggertin@proton.me
