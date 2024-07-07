NGINX Reverse Proxy
===================

`NGINX`_ is a web server, load balancer and reverse proxy with a strong
focus on performance, high concurency (over 10,000 simultaneous
connections), and low memory usage.

This appliance includes NGINX preconfigured as a light weight HTTP/HTTPS
reverse proxy, including SSL/TLS termination. It is intended as a public
internet facing gateway. It can be used as a base for installing
local web applications not intended for direct public access or running on
non-standard ports. It can also reverse proxy other webservers and/or be
used to access different apps/services via domain name.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- NGINX pre-configured as a reverse proxy to a simple example local
  page (TurnKey Web Control panel) running on port 3000. 
- Includes TurnKey Web Control panel with links to useful
  references and resources (convenience).
- SSL support out of the box.
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**


.. _NGINX: http://nginx.org
.. _TurnKey Core: https://www.turnkeylinux.org/core
