# Proxy for Testing http1 Core+ Workers

This project uses docker compose + nginx to configure an http1 proxy on localhost targetting multiple ports.

## Config

- Server can be set in a `.env` file via the `NGINX_DH_SERVER` variable
- Ports are set in `docker-compose.yml` and `templates/nginx.conf.template`

## Running

`docker compose up`
