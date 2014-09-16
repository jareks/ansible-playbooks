jareks.swapfile
=========

Creates a /swapfile and mounts it.

Requirements
------------

-

Role Variables
--------------

swapfile_path: path to swap file, default: /swap_file
swapfile_size: size of swap file to allocate, default: 1G

Dependencies
------------

-

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jareks.swapfile, swapfile_size: 2G }

License
-------

BSD

Author Information
------------------

Jarek Skrzypek
