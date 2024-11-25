FROM wordpress:latest

WORKDIR /var/www/html

COPY upload/plugin/ /var/www/html/wp-content/plugins/

COPY upload/wpconf/wp-config-docker.php /usr/src/wordpress/

#ENTRYPOINT ["docker-entrypoint.sh"]
ENTRYPOINT ["docker-entrypoint.sh"]

#CMD ["php-fpm"]
CMD ["apache2-foreground"]