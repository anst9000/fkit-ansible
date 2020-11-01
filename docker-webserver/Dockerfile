## Download base image php:7.0-apache
FROM php:7.0-apache

COPY src/ /var/www/html

EXPOSE 80

##--------------------------------------------------------------------------##
## Dockerfile ska instruera containern att utföra nedanstående:         
##	a. Sätta svensk tidzon         
##	b. Installera valfri webbserver där webbservern vid start av containern
##	   visar texten “FKIT” när man surfar till den
## Set this environment variable to true to set timezone on container start.
## ENV TZ=Europe/Stockholm
## RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
##--------------------------------------------------------------------------##
