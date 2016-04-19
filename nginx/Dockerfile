FROM nginx:1.9.14-alpine

RUN rm /etc/nginx/nginx.conf
ADD ./nginx.conf /etc/nginx/

RUN rm /etc/nginx/conf.d/default.conf
ADD ./default.conf /etc/nginx/conf.d/

EXPOSE 3000