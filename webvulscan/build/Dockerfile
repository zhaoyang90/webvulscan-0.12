FROM php:5.6-apache
ADD webvulscan-0.12.tar.gz /var/www/html/
RUN chmod -R 777 html
RUN docker-php-ext-install pdo_mysql mysqli

