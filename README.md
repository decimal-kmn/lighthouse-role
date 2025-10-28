Role name
=========

This role deploys LightHouse (is a lightweight GUI interface for ClickHouse)

Requirements
------------

Nginx
wget
tar


Dependencies
------------

nginx (for proxy to clickhouse)
wget (get lighthouse disrib)
tar (for extracting lighthouse distrib)
clickhouse node


Example Playbook
----------------

- name: Deploy lighthouse
  hosts: lighthouse
  become: true
  roles:
    - lighthouse-role

License
-------

MIT

Author Information
------------------

Mike Kolmykov
# lighthouse-role
