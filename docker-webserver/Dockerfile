## Download base image php:7.0-apache
FROM php:7.0-apache

# Set the timezone.
RUN sudo timedatectl set-timezone Europe/Stockholm

COPY src/ /var/www/html

EXPOSE 80
