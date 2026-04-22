# Laravel Student API
Simple REST API untuk mengelola data student menggunakan Laravel

## Features
* Create Student
* Get All Students
* Get Student by ID
* Update Student
* Delete Student

## Enpoint
Dokumentasi APi: https://documenter.getpostman.com/view/53993646/2sBXqDsiQg

## Tech Stack
* Laravel
* MySQL
* Postman (testing)

## Installation

1. Clone repository

```
git clone https://github.com/itsrezuu/laravel-student-api.git
```

2. Masuk ke folder project

```
cd laravel-student-api
```

3. Install dependency

```
composer install
```

4. Copy file environment

```
cp .env.example .env
```

5. Generate key

```
php artisan key:generate
```

6. Setup database di file `.env`

7. Jalankan migration

```
php artisan migrate
```

8. Jalankan server

```
php artisan serve
```

---
