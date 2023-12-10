# Docker skeleton for PHP applications

## Installs
Containers: `nginx` `php-fpm 8.2 alpine` `mariadb` `redis`\
Network: `phpapp`

## Installation

### Create /src folder

This docker compose file mounts the hosts /src folder to nginx /usr/share/nginx/html folder. The /src folder should be used as root folder for your PHP application. 

```
mkdir /src
```

### Run docker

```
docker-compose up
```
