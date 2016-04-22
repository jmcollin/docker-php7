FROM	php:7.0.5-fpm

MAINTAINER Jean-Marie Collin <jmcollinfr@gmail.com>

RUN rm /usr/local/etc/php-fpm.d/www.conf
ADD ./www.conf /usr/local/etc/php-fpm.d/

RUN rm /usr/local/etc/php-fpm.conf
ADD ./php-fpm.conf /usr/local/etc/

RUN rm /etc/sysctl.conf
ADD ./sysctl.conf /etc/

EXPOSE 9000