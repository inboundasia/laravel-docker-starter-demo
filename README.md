# Demo Project for laravel-docker-starter

1. git clone this project
2. `docker-compose up -d`
3. `docker-compose exec php php artisan migrate`

now you can access http://localhost

to destroy container, volumes, network
`docker-compose down -v`