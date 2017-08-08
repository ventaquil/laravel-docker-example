FROM php:7.1-apache

RUN apt-get update -y && apt-get install -y libxml2-dev node npm

RUN docker-php-ext-install mysqli pdo pdo_mysql mbstring dom

RUN a2enmod rewrite

