Role Name
=========

Ansible Galaxy role for installing MySQL following mysql_secure_installation.

Role Variables
--------------

    - mysql_root_password
    Specify root user password 

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: sparkfabrik.mysql, mysql_root_password: 'root' }

License
-------

BSD
