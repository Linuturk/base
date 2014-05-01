base
========

This role is responsible for setting up a base line for all supported systems.

[![Build Status](http://drone.onitato.com/github.com/rack-roles/base/status.svg?branch=master)](http://drone.onitato.com/github.com/rack-roles/base)

Requirements
------------

No requirements.

Role Variables
--------------

There is currently one variable set.

* `admin_packages`: This variable contains a list of packages to be installed on all systems.

Dependencies
------------

There are no external dependencies.

Example Playbook
-------------------------

Here is a simple example playbook:

    ---
    - hosts: all
      roles:
        - Rackspace_Automation.base

License
-------

BSD

Author Information
------------------

Justin Phelps
