# Luminary

[Luminary](https://github.com/arewtech/luminary.git) is a library website designed specifically for school libraries. This website is well-suited for the needs of libraries within schools only.

## Features ( Coming Soon )

-   Notification ( Actual Return Book )
-   Report ( Rent Logs )

## Preview Website

Preview Dashboard

![Luminary](/public/assets/preview/dashboard.png)

Preview Book List

![Luminary](/public/assets/preview/list-book-users.png)

Preview Books

![Luminary](/public/assets/preview/books.png)

Preview Rent Logs | Admin & Operator

![Luminary](/public/assets/preview/rentlogs-admin.png)

Preview Show User Rent Logs | Admin & Operator

![Luminary](/public/assets/preview/show-users.png)

Preview Profile

![Luminary](/public/assets/preview/profile.png)

Preview Settings

![Luminary](/public/assets/preview/settings.png)

Preview Rent Logs | Users

![Luminary](/public/assets/preview/rentlogs-users.png)

### satset

```bash
git clone https://github.com/arewtech/luminary.git 'project'
cd project
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh --seed
php artisan storage:link
php artisan serve
```

## Authors

Luminary is created by [Maman](https://github.com/arewtech).
