gitlab
=========

Role for installing gitlab docker container

Requirements
------------

- Only tested with CentOS7 and RHEL7
- The following packages should be installed beforehand
  - docker-compose
  - docker

Role Variables
--------------

t.b.d

Dependencies
------------

- The following packages should be installed beforehand
  - docker-compose
  - docker
  
Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gitlab, tags: install }

License
-------

BSD

Author Information
------------------

nm7-jp
