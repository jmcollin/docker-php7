FROM	nginx

MAINTAINER Jean-Marie Collin <jmcollinfr@gmail.com>

RUN rm /etc/nginx/conf.d/default.conf

RUN mkdir /etc/nginx/sites-available/
ADD ./sites-available/default.conf /etc/nginx/sites-available/

RUN rm /etc/nginx/nginx.conf
ADD ./nginx.conf /etc/nginx/

RUN rm /etc/sysctl.conf
ADD ./sysctl.conf /etc/

EXPOSE 3000