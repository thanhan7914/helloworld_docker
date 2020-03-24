FROM composer

WORKDIR /app

RUN composer install

RUN cp .env.example .env

RUN php artisan key:generate

RUN php artisan cache:clear

