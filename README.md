Role Name
=========

`jekyll` is a role that installs the requirements for setting up a local development environment for Jekyll. It is
an alternative to using a container. It is used in conjunction with Vagrant, which is why a task is used to open a port.

Requirements
------------

None

Role Variables
--------------
`defaults/main.yml`

jekyll_development_port: port to use when port forwarding

Dependencies
------------

None

Example Playbook
----------------
    - hosts: servers
      roles:
        - influentialcodellc.jekyll

License
-------

GPLv3

Author Information
------------------

This role was created by Influential Code LLC (https://www.influentialcode.com).
