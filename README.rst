===================
ansible-role-consul
===================

Ansible role to manage Consul

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-consul.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-consul
* Bugs: https://bugs.launchpad.net/ansible-role-consul

Description
-----------

Requirements
------------

Packages
~~~~~~~~

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install consul
      hosts: consul
      roles:
        - ansible-role-consul
