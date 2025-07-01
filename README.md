# 🚀 Laravel Sanctum Boilerplate

A clean and simple **Laravel 12** boilerplate that provides basic **API authentication using Laravel Sanctum**. This project is ideal for quickly getting started with token-based auth systems in Laravel.

![Laravel](https://img.shields.io/badge/Laravel-12.x-red)
![License](https://img.shields.io/badge/license-MIT-blue)
![Sanctum](https://img.shields.io/badge/Sanctum-Installed-green)

---

## 📋 Features

- ✅ User Registration API (`/api/register`)
- ✅ User Login API (`/api/login`)
- ✅ Token-based Authentication with Sanctum
- ✅ Hashed Passwords
- ✅ Structured, Clean Controller & Service Code
- ✅ Laravel Request Validation
- ✅ Ready for Postman/Thunder Client Testing

---

## 🧰 Tech Stack

- PHP 8.2.x
- Laravel 12.x
- Laravel Sanctum
- MySQL
- Composer
- Postman (for API testing)

---

## 🚀 Installation & Setup

```bash
# 1. Clone the repo
git clone https://github.com/Amirmurshad/laravel-sanctum-boilerplate.git

cd laravel-sanctum-boilerplate

# 2. Install dependencies
composer install

# 3. Setup .env
cp .env.example .env

# 4. Generate app key
php artisan key:generate

# 5. Run migrations
php artisan migrate

# 6. Install Sanctum (already added, but just in case)
composer require laravel/sanctum
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
php artisan migrate
```
