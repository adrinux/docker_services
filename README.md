docker_services
=========

My personal ansible role for deploying selfhosted services via docker. It may be of use to you too.

Requirements
------------

I use this role to install docker:
geerlingguy.docker https://github.com/geerlingguy/ansible-role-docker



Role Variables
--------------

[A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.]


Example Playbook
----------------

[Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
]

License
-------

GPLv3

Author Information
------------------

Adrian Simmons (adrinux)

This role takes heavy 'inspiration' from [ansible-role-docker-services](https://github.com/Thulium-Drake/ansible-role-docker_services) - whilst not being a direct fork some code was used as a base.