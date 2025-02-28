EWC Ansible Role Update System
==============================

Make sure your system is up-to-date. Supports both Rocky and Ubuntu.

Requirements
------------
None

Role Variables
--------------
 - `reboot_if_required`: Boolean to reboot the instance if required after an update. Default: true

Example Playbook
----------------

    - hosts: all
      roles:
         -  ewc-ansible-role-update-system

License
-------

Apache 2.0.

Author Information
------------------

ECMWF for the European Weather Cloud