FROM phpdockerio/php:8.3-fpm
WORKDIR "/app"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.3-decimal \
        php8.3-gd \
        php8.3-http \
        php8.3-imagick \
        php8.3-intl \
        php8.3-maxminddb \
        php8.3-mcrypt \
        php8.3-mysql \
        php8.3-redis \
        php8.3-uuid \
        nodejs \
        npm \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
