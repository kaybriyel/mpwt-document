# Installation

## Requirements

- PHP 8.2.0
- Composer 2.5.1

## Create Project

```bash
composer create-project laravel/laravel laravel-api
```

### creating project

<img src="/img/new-laravel-api/creating-laravel.png" />

### created project

<img src="/img/new-laravel-api/created-laravel.png" />

## Running API server

Go into project root directory

```bash
cd laravel-api
```

**Serve with default host and port**

```bash
php artisan serve
```

Accessible within your machine only<br/>
[http://localhost:8000](http://localhost:8000)<br />
http://127.0.0.1:8000

**Serve with custom host and port**

```bash
php artisan serve --host 0.0.0.0 --port 8001
```

Accessible from any machine in your network
[http://localhost:8001](http://localhost:8001)<br />
http://127.0.0.1:8001<br/>
[http://your-ip:8001](http://your-ip:8001)
