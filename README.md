# Sistem Informasi Akademik

## Run Locally

Clone the project

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Login

-   email = admin@admin.com
-   password = 123
