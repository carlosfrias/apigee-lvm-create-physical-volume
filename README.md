Apigee LVM Create Physical Volume
=========

This role will create a physical volume and added to the specified volume group.

Requirements
------------

To be completed

Role Variables
--------------

    partnum: 3
    typecode: 8E00
    device_name: xvda
    device_path: "/dev/{{ device_name }}"
    volume_name: vgroot


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
<!-- BEGIN Google Required Disclaimer -->

# Required Disclaimer

This is not an officially supported Google product.
<!-- END Google Required Disclaimer -->
