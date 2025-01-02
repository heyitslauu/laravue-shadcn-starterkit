<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## About the Project

This repository is a starter kit for [Laravel 11](https://laravel.com/), [Inertia](https://inertiajs.com/), [Vue 3](https://vuejs.org/), and [shadcn-vue](https://www.shadcn-vue.com/).

## Getting Started

Follow the steps below to set up and run the project on your local environment:

### 1. Clone the repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install PHP dependencies

```bash
composer install
```

### 3. Install Node.js dependencies

```bash
npm install
```

### 4. Create the .env file

Copy the example environment file and customize it for your setup:

```bash
cp .env.example .env
```

### 5. Generate the application key

```bash
php artisan key:generate
```

### 6. Configure the database

Update the .env file with your database credentials:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

### 7. Run database migrations

```bash
php artisan migrate
```

### 8. Build frontend assets

##### For development:

```bash
npm run dev
```

##### For development:

```bash
npm run build
```

### 9. Start the development server

```bash
php artisan serve
```

Access the application via returned url. Commonly [localhost](http://localhost:8000).

### 10. (Optional) Seed the database

If seeders are configured, run:

```bash
php artisan db:seed
```
