# ./docker/php/Dockerfile
FROM php:7.4.1-fpm

#COPY apps/backend /var/www

#WORKDIR /usr/src/app
#RUN ls -l

#RUN docker-php-ext-install pdo_mysql
#
#RUN pecl install apcu
#
#RUN apt-get update && \
#apt-get install -y \
#zlib1g-dev \
#libzip-dev
#
#RUN docker-php-ext-install zip
#RUN docker-php-ext-enable apcu
#
#RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" \
#    && php -r "if (hash_file('SHA384', 'composer-setup.php') === 'baf1608c33254d00611ac1705c1d9958c817a1a33bce370c0595974b342601bd80b92a3f46067da89e3b06bff421f182') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;" \
#    && php composer-setup.php --filename=composer \
#    && php -r "unlink('composer-setup.php');" \
#    && mv composer /usr/local/bin/composer
#
#WORKDIR /usr/src/app
#
#COPY apps/backend /usr/src/app
#
#RUN PATH=$PATH:/usr/src/apps/vendor/bin:bin
#
#RUN composer install