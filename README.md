# caddy wordpress docker
Configure Caddy + WordPress through docker-compose

## Setting up & configuring
```bash
# Clone repository
git clone https://github.com/starunity/caddy-wordpress-docker.git
cd caddy-wordpress-docker

# Edit config/Caddyfile and replace'<YOUR_SITE_NAME>' and '<YOUR_EMAIL>'
# Note <YOUR_SITE_NAME> must be the DNS site name you configured
vim config/Caddyfile

# Build via docker-compose
docker-compose up
```

## Reference project
https://github.com/ned-kelly/docker-caddy-wordpress

