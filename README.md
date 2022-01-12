# php-nginx-mysql-docker-starter
Docker running PHP, NGINX and MYSQL.

## Setup
* Clone this repository
* Copy `.env.example` file and rename to `.env`.
* `docker-compose up -d`
* Go to `localhost:8200`
* Run command inside container with 
`docker-compose exec app <command>`
for eg. `docker-compose exec app php -v`
