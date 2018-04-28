FROM php:5.6-apache
ADD webvulscan-0.12.tar.gz /var/www/html/
RUN mkdir /var/www/html/webvulscan-0.12/scanner/logs
RUN chmod -R 777 /var/www/html/

RUN docker-php-ext-install pdo_mysql mysqli
