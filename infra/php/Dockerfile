ARG PHP

FROM php:$PHP-apache

COPY --from=composer /usr/bin/composer /usr/bin/composer
RUN apt update && apt install bash-completion