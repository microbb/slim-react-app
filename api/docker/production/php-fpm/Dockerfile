FROM php:8.2-fpm-alpine

RUN mv $PHP_INI_DIR/php.ini-production $PHP_INI_DIR/php.ini

COPY ./docker/production/php-fpm/conf.d /usr/local/etc/php/conf.d

WORKDIR /app

COPY ./ ./
