FROM php:7.4-apache
RUN apt-get update && \
    apt-get install -y vim && \
    docker-php-ext-install mysqli
RUN a2enmod rewrite
RUN a2enmod ssl
