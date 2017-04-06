Role Name
=========

Use ansible to ease this installation of Docker Toolbox. 
Docker-machine-nfs increase the read/write access to your filesystem between OSX and your VM.

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: anthonykgross.docker-osx-install, default_virtual_memory: 2048 }

## Creator
**Anthony K GROSS**
- <http://anthonykgross.fr>
- <https://twitter.com/anthonykgross>
- <https://github.com/anthonykgross>

## Copyright and license
Code and documentation copyright 2017. Code released under [the MIT license](https://github.com/anthonykgross/ansible-docker-osx-install/blob/master/LICENSE).
