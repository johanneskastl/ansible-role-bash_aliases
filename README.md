![Ansible Lint](https://github.com/johanneskastl/ansible-role-bash_aliases/workflows/Ansible%20Lint/badge.svg)

bash_aliases
=========

Create a `~/.alias` file containing some sensible aliases for bash:

- git aliases
- kubectl aliases
- kubie aliases
- ...

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.bash_aliases'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
