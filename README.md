# Udemy-docker-and-kubernetes-laravel
Dockerize a laravel project with services including composer, php, server nginx, mysql, artisan and npm

Step 1: Use composer to create laravel project source code
docker-compose run --rm composer create-project --prefer-dist laravel/laravel:^8.0 .

Step 2: Synchronize information at env/mysql.env to src/.env

Step 3: Use docker-compose up for list of service you want to run
docker-compose up -d server php mysql

Step 4: Enjoy http://localhost:8000/