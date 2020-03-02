hyperized.docker-compose
=========

_Installs docker-compose._

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

    docker_compose_state: present
    docker_compose_path: /usr/local/bin/docker-compose
    docker_compose_version: 1.25.4
    docker_compose_url: "https://github.com/docker/compose/releases/download/{{ docker_compose_version }}/docker-compose"

Dependencies
------------

    n/a

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - role: hyperized.docker-compose

License
-------

MIT

Author Information
------------------

Gerben Geijteman <gerben@hyperized.net>
