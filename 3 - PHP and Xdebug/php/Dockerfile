#FROM php:fpm
#RUN pecl install xdebug
#RUN docker-php-ext-enable xdebug
FROM wodby/php:8.2
COPY php/php.ini /usr/local/etc/php/
RUN addgroup --gid 1024 mygroup
RUN adduser --disabled-password --gecos "" --force-badname --ingroup 1024 myuser 
USER myuser
