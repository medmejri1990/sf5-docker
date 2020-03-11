# Symfony 5 docker containers

A Proof-of-concept of a running Symfony 5 application inside containers

```
git clone https://github.com/medmejri1990/sf5-docker.git

cd sf5-docker
download symfony 5
- > run  symfony new --full api
https://symfony.com/download

create new app  angular 
https://angular.io/start
cd docker
docker-compose vuild
docker-compose up
```

## Compose

### Database (MariaDB)

...

### PHP (PHP-FPM)

Composer is included

```
docker-compose run php-fpm composer 
```
```

### Webserver (Nginx)

...
