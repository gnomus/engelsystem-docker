FROM php:fpm-alpine

MAINTAINER Felix Favre <gnomus@gnomus.de>

RUN apk add --no-cache gettext-dev \
    && docker-php-ext-install gettext


EXPOSE 9000

ENTRYPOINT ["docker-php-entrypoint"]

CMD ["php-fpm"]
