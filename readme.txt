install extension gd 
docker exec -it nginx-server_php-fpm_1 sh
apk update
apk add libpng-dev
docker-php-ext-install gd
