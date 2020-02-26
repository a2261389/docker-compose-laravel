# docker compose laravel

```
git clone https://github.com/a2261389/docker-compose-laravel
cd docker-compose-laravel
docker compose up -d
docker exec app composer install
cp .env.example .env
docker exec app php artisan key:generate
```

If you need NPM, run:
```
docker exec npm npm your_command
```

You can modify NGINX config in ``docker/nginx/laravel.conf``
