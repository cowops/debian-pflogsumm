Debian-Pflogsumm
=================

pflogsumm.pl is designed to provide an over-view of postfix activity, with just enough detail to give the administrator a "heads up" for potential trouble spots.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

None
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-pflogsumm }

Tasks
-----

  - Install [pflogsumm](http://jimsun.linxnet.com/postfix_contrib.html) tool

License
-------

BSD