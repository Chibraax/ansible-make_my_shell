Role Name
=========

Automatic shell configuration + customisation. (<https://github.com/Chibraax/ansible-make_my_shell/blob/main/tasks/main.yml>)

Requirements
------------

access to remote machine

Role Variables
--------------

This variable define the user's shell to configured

                make_my_shell_user: myuser

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        - make_my_shell_user: myuser
      roles:
         - ansible-make_my_shell

License
-------

BSD

Author Information
------------------

Chibraax, check <https://github.com/Chibraax>
