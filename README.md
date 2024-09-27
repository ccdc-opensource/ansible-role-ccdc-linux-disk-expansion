ansible-role-ccdc-linux-disk-expansion
=========

Ansible role to increase disk size using LVM

Requirements
------------

community.general.lvol

Role Variables
--------------

disk_name
lv_name
vg_name
disk_size_use
resize2fs

Dependencies
------------

none

Example Playbook
----------------

- role: ansible-role-ccdc-linux-disk-expansion

License
-------

MIT

Author Information
------------------

Sam Jackson
