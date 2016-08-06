# Docker images from KartoffelToby

## Networking

#### [kartoffeltoby/caddy_proxy] (https://hub.docker.com/r/kartoffeltoby/caddy_proxy/)
This is a Alpine based Image with CaddyServer and Docker-Gen
It's like the nginx-Proxy Image

Connects Automatic with Containers with a special Env

Usage:

- HTTPS_DOMAIN=test.de (https with a letsencryped Cert)
- HTTP_DOMAIN=test.de (Only http)

if your target Container hasn't exosed ports 80 or 443
you can set the port via HOST_PORT=300

---
#### [kartoffeltoby/docker-nas-samba] (https://hub.docker.com/r/kartoffeltoby/docker-nas-samba/)
This is a Debian based Image wth Samba 4

Usage:
- hostname=Servername 
- PASSWORD=test
- USER=test

Access via : smb://ip/test

## Apps/Services


## Server
