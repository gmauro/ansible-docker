# Ansible Docker [![Build Status](https://travis-ci.org/gmauro/ansible-docker.svg?branch=master)](https://travis-ci.org/gmauro/ansible-docker)
[Ansible](https://wwww.ansible.com) role to install [Docker-CE](http://www.docker.com) and extensions on Ubuntu or Debian systems .  


## Usage

Clone this repo into your roles directory:

```bash
$ git clone https://github.com/gmauro/ansible-docker.git roles/docker
```

And add it to your play's roles:

```yaml
- hosts: ...
  roles:
    - docker
    - ...
```

This role comes preloaded with multiple available defaults. You can override each one in your hosts/group vars, in your inventory, or in your play. See the annotated defaults in ``defaults/main.yml`` for help in configuration.