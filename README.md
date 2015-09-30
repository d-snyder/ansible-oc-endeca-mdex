Role Name
=========

This role installs and configures oracle endeca mdex 6.5.1 on linux platforms

Requirements
------------

You must accept the license agreement, download V46002-01.zip (for the linux x64 platform), and copy it to the playbook directory or to the files directory within this role from: https://edelivery.oracle.com


Role Variables
--------------

install_root: the root directory where the application will be installed. Actual installation may occur within a path under this directory depending on the installer.
install_url: If defined, the role will attempt to download the install archive before attempting installation.


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: oc-endeca-mdex, install_root: /opt/oracle, sudo_user: oracle }
         

License
-------

GPL V3

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
