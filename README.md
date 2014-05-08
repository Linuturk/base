base
========

This role is responsible for setting up a base line for all supported systems.

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/base/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/base)

Requirements
------------

No requirements.

Role Variables
--------------

* `admin_packages`: This variable contains a list of packages to be installed on all systems.
* `rax_pub_keys` is a list of public SSH keys to be set.

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
