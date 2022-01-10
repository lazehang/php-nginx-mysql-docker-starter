# php-nginx-mysql-docker-starter
Starter template for running PHP, NGINX and MYSQL using docker-compose.

## Setup
* Clone this repository
* `docker-compose up -d --build`
* Go to `localhost:8200`
* Run command inside container with 
`docker-compose exec -T app <command>`
for eg. `docker-compose exec -T app php -v`
clone this repository

`docker-compose up -d --build`

