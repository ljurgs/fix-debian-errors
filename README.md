Role Name
=========

A role that provides workarounds for some annoying but non-serious bugs that result in error messages appearing in the system log in debian family distributions.

Requirements
------------

None.

Role Variables
--------------

None

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ljurgs.fix-debian-errors

License
-------

BSD-3-Clause
