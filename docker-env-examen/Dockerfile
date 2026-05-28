# 1. Traemos la imagen oficial de PHP con el servidor Apache
FROM php:8.2-apache

# 2. Instalamos las extensiones necesarias para que PHP pueda hablar con MariaDB
RUN docker-php-ext-install pdo pdo_mysql mysqli

# 3. (Opcional pero recomendado) Damos permisos a la carpeta de la web
RUN chown -R www-data:www-data /var/www/html


