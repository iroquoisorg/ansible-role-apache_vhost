# apache_vhost

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-apache_vhost.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for apache_vhost

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.apache_vhost`

# Default settings

```

apache_vhost_host: ""
apache_vhost_web_root: ""
apache_vhost_web_port: 80
apache_vhost_ssl_crt_path: ""
apache_vhost_ssl_key_path: ""
apache_vhost_ssl_crt_chain_path: ""
apache_vhost_env_vars: []
apache_vhost_basic_auth_location: "/"
apache_vhost_basic_auth_users: []
apache_vhost_force_ssl: false
apache_vhost_force_ssl_location: "/"
apache_vhost_apache_user: "{{ apache_user | default(\"www-data\") }}"
apache_vhost_apache_group: "{{ apache_group | default(\"www-data\") }}"
apache_vhost_server_aliases: []

```
