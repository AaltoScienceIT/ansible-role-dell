ansible-role-dell
=========

Installs Dell DSU yum repo and related softwares for managing a Dell server 

http://linux.dell.com/repo/hardware/dsu/

Requirements
------------

 - ansible -m setup and system_vendor should say "Dell Inc."

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-dell }

License
-------

MIT

Author Information
------------------

Johan Guldmyr
