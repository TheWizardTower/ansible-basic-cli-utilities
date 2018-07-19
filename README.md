basic-cli-utilities
=========

This playbook installs a set of command line utilities that I find useful. Note that care is taken to avoid installing graphical programs, this is meant to be suitable for contexst where you're ssh'ing to a dev machine, or running a container.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: thewizardtower.ansible_basic_cli_utilities }

License
-------

BSD
