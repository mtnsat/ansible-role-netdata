ymajik.netdata
=========

[![Build Status](https://travis-ci.org/ymajik/ansible-role-netdata.svg?branch=master)](https://travis-ci.org/ymajik/ansible-role-netdata)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-netdata-blue.svg?style=flat)](https://galaxy.ansible.com/ymajik/netdata)

Install and update netdata.

Requirements
------------

Ansible 2.2 or higher. Operating systems that use systemd as init system need the ansible systemd module.

Role Variables
--------------

```yaml
    netdata_install_dir: /opt/netdata
```
Netdata dependencies are loaded from within the vars file per operating system family (Debian or RedHat).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: all
      roles:
         - ymajik.netdata
```

License
-------

MIT

Author Information
------------------

ymajik
