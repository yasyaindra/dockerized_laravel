# STEP MAKE A FOLDER

# HOW TO RUN

```zsh
docker-compose up -d --build
```

# EXECUTE CONTAINER

```zsh
docker exec -it php bash
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
DB_HOST=dockerized_laravel_mysql_1
DB_PORT=3306
DB_DATABASE=laradock
DB_USERNAME=laradock
DB_PASSWORD=secret
```

dont forget to make database 'laradock'

# GENERATE KEY

```php
php artisan key:generate
```

Happy hacking
