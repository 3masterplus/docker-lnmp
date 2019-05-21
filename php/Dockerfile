FROM php:7.2-fpm

RUN apt-get update && pecl install redis && docker-php-ext-enable redis \
&& pecl install swoole  && docker-php-ext-enable swoole
