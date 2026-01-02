#### testing php74

    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && exec bash"

    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && composer update"
    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && composer install"
    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && sh phpunit"
    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && git status"
    docker exec -it dev-php74 sh -c "cd /var/www/php74/yusam-hub/json-ext && git pull"

å