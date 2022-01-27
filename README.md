cvmfs_client
============
Ansible role for the cvmfs_client installation and data.galaxyproject.org, data.elixir-italy-cvmfs repositories mounting 

Requirements
------------
Ansible = 2.9 

Role Variables
--------------

**la_cvmfs_repository:** data.elixir-italy-cvmfs #set elixir-it repository

**elixir_it_repo:** true #bool to configure elixir-it repo

Dependencies
------------
 
- galaxyproject.cvmfs
- geerlingguy.repo-epel

Example Playbook
----------------
```
- hosts: galaxy
  become: true
  roles:
    - cvmfs-client
``` 

License
-------
GPL-3.0-only

Author Information
------------------

**name:** Pietro Mandreoli 
**email:** pietro.mandreoli@unimi.it
