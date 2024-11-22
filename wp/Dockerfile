FROM wordpress:6.7.1-fpm-alpine

WORKDIR /var/www/html

COPY upload/plugin/ /var/www/html/wp-content/plugins/

ENTRYPOINT ["docker-entrypoint.sh"]

CMD ["php-fpm"]