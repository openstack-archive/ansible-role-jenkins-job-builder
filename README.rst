================================
ansible-role-jenkins-job-builder
================================

Ansible role to manage Jenkins Job Builder

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-jenkins-job-builder.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-jenkins-job-builder
* Bugs: https://bugs.launchpad.net/ansible-role-jenkins-job-builder

Description
-----------

Jenkins Job Builder takes simple descriptions of Jenkins jobs in YAML or JSON
format and uses them to configure Jenkins. You can keep your job descriptions
in human readable text format in a version control system to make changes and
auditing easier.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install jenkins job builder
      hosts: jenkins
      roles:
        - ansible-role-jenkins-job-builder
