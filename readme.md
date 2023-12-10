# Docker skeleton for PHP applications

## Installs
Containers: `nginx` `php-fpm 8.2 alpine` `mariadb` `redis`
Network: `phpapp`

## Installation

### Create /src folder

This docker compose file mounts the /src folder to /usr/share/nginx/html within nginx. 

```
mkdir /src
```

### Run docker

```
docker-compose up
```
