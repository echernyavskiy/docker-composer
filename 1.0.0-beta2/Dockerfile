# Composer Docker Container
FROM composer/composer:base
MAINTAINER Rob Loach <robloach@gmail.com>

ENV COMPOSER_VERSION 1.0.0-beta2

# Install Composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer --version=${COMPOSER_VERSION}

# Display version information
RUN composer --version
