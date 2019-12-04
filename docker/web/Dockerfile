FROM php:7.2-apache
RUN a2enmod rewrite
RUN apt update
RUN apt install libpq-dev -y
RUN docker-php-ext-install pcntl pdo pdo_pgsql
RUN apt install git -y