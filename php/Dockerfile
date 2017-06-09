FROM php:fpm-alpine

MAINTAINER Felix Favre <gnomus@gnomus.de>

RUN apk add gettext \
    && docker-php-ext-install gettext


EXPOSE 9000
CMD ["php-fpm"]
