Install Docker
=========

Add docker-ce repository, install and run docker, add user to docker group

Role Variables
--------------

| Variables:      |                                 |
| --------------- | ------------------------------- |
| docker_packages | defined in role defaults
| ansible_user    | for adding user to docker group


Example Playbook
----------------

    - hosts: servers
      roles:
         - d1t5u.docker_install

License
-------

MIT

Author Information
------------------

Tsurganov Dmitry
