satellite-clients
=========

A simple module used to enable software on satellite hosts.

Requirements
------------

Satellite is required, and system must already be registerd to satellite.  This role should be placed in /etc/ansible/roles on all capsules (including integrated).  After the module is here, navigate to Configure -> Ansible Roles, click the import button and select the capsule.  After the role has been imported, it may be applied to hosts or host groups as desired.

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: satellite-clients }

License
-------

BSD

Author Information
------------------

Roy Williams <roywilliams@redhat.com> - Initial commit.
