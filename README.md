Role Name
=========

This will set up btrfs handling on a rhel8 based host.

Since rhel8 does not support btrfs by default, we have to 
install new kernel that support btrfs, this is the reason for this role.

Requirements
------------

A rhel8 host

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

Sample run:

    $ ansible-playbook -e host=avcs8-ks01 -e role=btrfs_rhel8 add_role.yml

License
-------

BSD

Author Information
------------------

This role was created in 2021 by Richard Chen.
