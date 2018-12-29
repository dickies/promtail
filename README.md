Promtail 
=========

Install binary promtail.

Requirements
------------

None

Role Variables
--------------

#Defaults file for promtail

http_listen_port: 0
grpc_listen_port: 0

positions_path: /tmp/positions.yml

loki_server_ip: localhost


Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: promtail

License
-------



Author Information
------------------

This role was created in 2018 by [Dickies](https://github.com/dickies/promtail)
