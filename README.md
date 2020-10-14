Fire Fox
=========

The goal of this project is to automatically install and configure android-sdk according to a users preferences.

Requirements
------------

An inventory file with an entry for desktop should exist.  I use this project to spin up an Ubuntu
desktop in EC2 using terraform: https://github.com/bbux-aws/aws-packer-terraform-ansible.  This also
generates and inventory file that will work with this project.

Role Variables
--------------


Dependencies
------------

No Dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: desktop
      roles:
        - role: android-sdk

License
-------

Apache2
