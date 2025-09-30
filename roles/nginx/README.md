Role Name
=========
This module can intelligently install nginx, set configure file, create systemd service file, start and enable a nginx server.

Requirements
------------
none

Role Variables
--------------
please see defaults/main.yml

Dependencies
------------
none

Example Playbook
----------------
- name: Deploying nginx
  hosts: test
  roles:
    - nginx

License
-------

BSD

Author Information
------------------
thcsip
