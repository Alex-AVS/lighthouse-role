lighthouse-role
=========

This role installs lighthouse web UI for ClickHouse databases.

Requirements
------------

- git installed
- some web server to run the app (server configuration is out of scope of this role).

Role Variables
--------------

Defaults:
 - lighthouse_dst_dir:  default is "/opt/lighthouse" - path to install te app to.
Variables:
 - lighthouse_url - repository URL

Dependencies
------------

None.

Example Playbook
----------------


    - hosts: servers
      roles:
         - nginx
         - ligthouse-role
      tasks:
         - Configure nginx
            ...
License
-------

BSD

Author Information
------------------


