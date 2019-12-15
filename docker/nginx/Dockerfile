FROM nginx:1.17.6-alpine

RUN mkdir /var/www
RUN mkdir /var/www/public
RUN mkdir /var/www/private

COPY conf.d/default.conf /etc/nginx/conf.d/default.conf