FROM	php:7.0.5-fpm

MAINTAINER Jean-Marie Collin <jmcollinfr@gmail.com>

RUN rm /usr/local/etc/php-fpm.d/www.conf
ADD ./www.conf /usr/local/etc/php-fpm.d/

EXPOSE 9000