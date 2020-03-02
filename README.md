# Symfony 5 docker containers

A Proof-of-concept of a running Symfony 5 application inside containers

```
git clone https://github.com/medmejri1990/sf5-docker.git

cd symfony-5-docker
download symfony 5
- > run  symfony new --full src
https://symfony.com/download

cd docker

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