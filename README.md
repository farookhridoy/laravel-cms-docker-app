<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel-CMS-Docker-App

Practice docker environment with laravel & sail

## Docker Container Based Laravel
Sample Project: Realtime chat application built with Laravel WebSockets.

This docker build can be used to run all your Laravel Projects. Our implementation will include containers:

- sail
- mysql
- redis
- meilisearch
- mailpit
- selenium
- mysqladmin

## Docker Important Command
- Setup docker on your machine according to your environment.
- git clone https://github.com/gmfaruk/laravel-cms-docker-app.git
- cd laravel-cms-docker-app

- docker ps :: to check globally container status
- docker-compose ps :: to check dir based container status
- docker-compose up :: deploy the server
- docker-compose down :: down the server after each changes
- docker-compose up --build :: deploy and build the server
- docker-compose up -d :: hide the terminal command
- docker exec <container name> <command> :: Example: docker exec docker-app-laravel.test-1 php artisan migrate

## Run host and service
- http://localhost:8001/ :: for run phpmyadmin
- http://localhost:80 :: for run the localhost application

## check container logs
- docker logs -f <container name>
- docker logs -f mysql
