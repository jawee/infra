Nginx config external
=========

Creates a config for reverse proxy, for the external server. 

Requirements
------------
* Nginx 
* Ubuntu
* Config files placed in /etc/nginx/sites-available and /etc/nginx/sites-enabled

Role Variables
--------------

* external_domain: "something.test.something.se"
* internal_ip: "127.0.0.1"
* internal_port: 80
* service_name: "test1"
* user: "username"
