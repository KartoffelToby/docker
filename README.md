# Docker images form KartoffelToby

## Networking

### kartoffeltoby/caddy_proxy(https://hub.docker.com/r/kartoffeltoby/caddy_proxy/)
This is a Alpine Based Image with CaddyServer and Docker-Gen
It's like the nginx-Proxy Image

Connects Automatic with Containers with a special Env

So you can use

- HTTPS_DOMAIN=test.de (https with a letsencryped Cert)
- HTTP_DOMAIN=test.de (Only http)

if your target Container hasn't exosed ports 80 or 443
you can set the port via HOST_PORT=300

## Apps/Services


## Server
