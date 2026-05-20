FROM php:8.2-apache

# Instalamos los editores de texto actualizando los repositorios modernos
RUN apt-get update && apt-get install -y \
    vim \
    nano \
    && rm -rf /var/lib/apt/lists/*

EXPOSE 80