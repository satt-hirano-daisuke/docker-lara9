FROM php:8.0-fpm-alpine

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

RUN apk update && apk add git vim


