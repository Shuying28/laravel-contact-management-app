# Laravel InertiaJS Vuetify

A laravel inertiajs vuetify contact management system

## Demo

You can access demo app in : <https://laravel-inertia-vuetify.fly.dev>

## Features

- Laravel 10
- Inertia.js
- Vue 3
- Vite
- Vuetify + Material Design Icons
- ESLint + Prettier
- Authentication (Login, Register, Forgot Password)
- CRUD with serverside pagination, searching, and sorting
- SPA (Single Page Application)

## Installation

Clone repo locally

```bash
git clone https://github.com/Shuying28/laravel-contact-management-app
```

Install PHP dependencies

```bash
composer install
```

Install NPM dependencies

```bash
npm install
```

Build assets

```bash
npm run dev
```

Setup configuration

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Run database migrations

```bash
php artisan migrate
```

Run application
```bash
php artisan serve
```
