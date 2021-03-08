FROM php:7.4-fpm

MAINTAINER Juan Antonio Reifs Ramirez "initiategnat9@gmail.com"

RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

ENV DATABASE_SERVER=book_sql MYSQL_ROOT_PASSWORD=root MYSQL_USER=book_user MYSQL_PASSWORD=book_passwd MYSQL_DATABASE=bookmedik
