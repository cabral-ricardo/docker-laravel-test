# docker-laravel-test
This repository contains an image to up container laravel

## dockerhub image
https://hub.docker.com/repository/docker/cabralricardo/laravel

## install composer
- composer install 
or 
- composer install --ignore-platform-reqs 
-> in error case

### other operating system
https://getcomposer.org/doc/00-intro.md#installation-linux-unix-macos

## config .env
- create a new file .env and copy content .env.example
- changes:
  - DB_HOST=127.0.0.1 to DB_HOST=db
  - DB_PASSWORD= to DB_PASSWORD=root
  - REDIS_HOST=127.0.0.1 to REDIS_HOST=redis

## run docker compose
docker-compose up -d --build

## stop docker compose
docker-compose down

## add cloud build
https://cloud.google.com/cloud-build/docs/build-config