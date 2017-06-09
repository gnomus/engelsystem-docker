FROM php:fpm-alpine

MAINTAINER Felix Favre <gnomus@gnomus.de>

RUN apk add php-gettext \
    && docker-php-ext-install gettext


EXPOSE 9000
CMD ["php-fpm"]
