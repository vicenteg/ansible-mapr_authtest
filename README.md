mapr_authtest
=========

A role to confirm that a MapR ticket has been obtained.

Requirements
------------

You need to have a secure MapR cluster for this to be useful.

Role Variables
--------------

None

Dependencies
------------


Example Playbook
----------------

    - hosts: cluster
      roles:
         - { role: mapr_authtest }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
