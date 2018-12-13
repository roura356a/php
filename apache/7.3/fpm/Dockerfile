FROM php:7.3-apache

ENV FPM_HOST fpm
ENV FPM_PORT 9000
ENV VHOST_FOLDER /var/www/html/

RUN a2enmod rewrite proxy proxy_fcgi

COPY ./000-default.conf /etc/apache2/sites-available/
