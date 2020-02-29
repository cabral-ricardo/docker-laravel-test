# docker-laravel-test
This repository contains an image to up container laravel

## dockerhub image
https://hub.docker.com/repository/docker/cabralricardo/laravel

## install composer
composer install

## config .env
- rename .env.example to .env
- changes:
  - DB_HOST=127.0.0.1 to DB_HOST=db
  - DB_PASSWORD= to DB_PASSWORD=root
  - REDIS_HOST=127.0.0.1 to REDIS_HOST=redis

## run docker compose
docker-compose up -d --build

## stop docker compose
docker-compose down
