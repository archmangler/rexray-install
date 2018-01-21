Role Name
=========

- SUPER simple playbook to install rexray on an existing ceph cluster.
- Uses the latest stable version of EMC's rexray binary agent

Requirements
============

- pre-existing ceph cluster

Role Variables
==============

None at present. Although we might want to consider the default volume size (but then again, it is a "default" ;-) ).

Dependencies
============

No role dependencies at present.

Example Playbook
================

---
- hosts: ceph-clients
  become: True
  roles:
   - rexray-install

License
=======

None

Author Information
==================

traiano.welcome@teralytics.ch, Teralytics Pte.
