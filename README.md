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

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
