base
========

This role is responsible for setting up a base line for all supported systems.

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/base/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/base)

Requirements
------------

Ansible version 1.6.3 or greater.

Role Variables
--------------

* `base_admin_packages`: This variable contains a list of packages to be installed on all systems.
* `base_custom_packages`: This variable can contain a custom list of packages that would vary from the default set.
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
        - { role: Rackspace_Automation.base, x: 42 }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
