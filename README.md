# docker-laravel5-nginx-node-mysql
Docker example with Nginx, MySql,Php 7.1,Node

## Prerequisites

* Docker

## How to run app

#### Clone and run

```
$ git clone https://github.com/AbhinavDobhal/docker-laravel5-nginx-node-mysql.git
$ cd docker-laravel5-nginx-node-mysql
$ docker-compose up -d
```

#### laravel .env 

```
DB_CONNECTION=mysql
DB_HOST=db(mysql - use db)
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=root
```