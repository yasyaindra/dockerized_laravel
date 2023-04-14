# STEP MAKE A FOLDER

# HOW TO RUN

```zsh
docker-compose up -d --build
```

# EXECUTE CONTAINER

```zsh
docker exec -it php_laravel bash
```

# HOW TO MAKE A PROJECT IN SRC

```php
composer create-project laravel/laravel .
```

# SETTING UP .ENV

```zsh
cp .env.example .env
```

```txt
DB_CONNECTION=mysql
DB_HOST=nama container di docker
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

# GENERATE KEY

```php
php artisan key:generate
```

Happy hacking
