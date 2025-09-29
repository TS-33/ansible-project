Role Name
=========
A common role to init a linux node
This role will:
 add a user named guest
 set sudo permission
 add ssh_pub_key
 set timezone=Asia/Shanghai
 enable or disable firewall and set vaild port
 disable selinux
 makesure yum repository is available


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
- name: common
  hosts: all
  vars:
	allow_port: '8080/tcp'   #more vars please see defaults/main.yml
  roles:
	- common

License
-------

BSD

Author Information
------------------
created by thcsip

