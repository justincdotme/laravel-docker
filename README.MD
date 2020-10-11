#laravel-docker


Basic scaffolding for running a new Laravel app in a Docker container. Leverages php-fpm7.3, Xdebug, MySQL and Nginx

This is a modified version of a solution that was proposed on the [Digital Ocean Community website](https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose).

This repository is intended to be used as a submodule. This repository is intended for use during development and is not intended for and has never been tested for use in a production environment. 

## Docker Images
 - php-fpm 7.3 (Digitalocean)
 - Nginx 1.19.3 (Alpine)
 - Xdebug (PECL)
 - MySQL 5.7.22


## Requirements
The containers run on Ubuntu. As such, the Docker host system needs to run on the Linux kernel. 

