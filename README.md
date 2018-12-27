Role: Automated Tasks
===============

This role is used by the environment setup for my Starfly infrastructure.

It is used to setup the rc.local file to automate docker-compose relaunch (That tasks will change in favor of the "restart: always" parameter in docker). It will be replaced by the cron role.

Requirements
------------

Que alfred et docker soit sur la machine.

Role Variables
--------------

None.

Platform
--------

Debian

Dependencies
------------

Ce role se télécharge automatiquement à partir du requirements.yml


Author Information
------------------

Starfly Env Team
