FROM php:7.1-apache

RUN /usr/local/bin/docker-php-ext-install mysqli pdo pdo_mysql

RUN apt-get update && apt-get install -y vim
RUN apt-get update && apt-get install -y wget

RUN usermod -u 1000 www-data

EXPOSE 80