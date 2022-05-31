FROM webdevops/php-apache-dev:7.4

#Install GD
#RUN apt-get update && apt-get install -y \
#        libfreetype6-dev \
#        libjpeg62-turbo-dev \
#        libpng-dev \
#    && docker-php-ext-configure gd --with-freetype --with-jpeg \
#    && docker-php-ext-install -j$(nproc) gd

#Install Redis & Xdebug
#RUN pecl install redis-5.1.1 \
#    && pecl install xdebug-2.8.1 \
#    && docker-php-ext-enable redis xdebug

#Install Memcache
#RUN apt-get update && apt-get install -y libmemcached-dev zlib1g-dev \
#    && pecl install memcached-2.2.0 \
#    && docker-php-ext-enable memcached