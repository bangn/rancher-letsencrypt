A rancher server with [nginx-proxy](https://github.com/jwilder/nginx-proxy) and [letsencrypt-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion).

# Environment variables

You need to set below environment variables. See [docker-run](./docker-run).
- VIRTUAL_HOST*
- LETSENCRYPT_EMAIL*

(*) mandatory environment variables.

# Prerequisite
`docker` and `docker-compose`

# DNS
You need to point you VIRTUAL_HOST address to the IP of the host runs these
containers.

# Run all containers
```bash
docker-compose up -d
```

# Credit
This is individual project and is inspired by [this example](https://github.com/fatk/docker-letsencrypt-nginx-proxy-companion-examples)
