FROM php:7.4-fpm-alpine

RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/phph.ini

COPY ./conf.d /usr/local/etc/php/conf.d

WORKDIR /app

