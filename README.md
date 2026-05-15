# Laravel Service Scheduler

Laravel Service Scheduler is a web application built with Laravel for managing service scheduling records through CRUD operations.

The project follows Laravel’s conventional MVC structure and includes the standard application layers for routing, controllers, views, database configuration, public assets, application storage, and testing structure.

> The latest version of this project is maintained in the `v6` branch.

---

## Overview

This project was developed as a Laravel web application focused on service scheduling management.

The application demonstrates a CRUD-based workflow using Laravel’s standard project organization, including routing, database interaction, Blade views, and MVC-oriented structure.

The main goal of this project is to practice and demonstrate the fundamentals of building a structured Laravel application with database-backed operations.

---

## Features

- Create service scheduling records
- List registered scheduling records
- View stored scheduling data
- Update existing records
- Delete records
- Laravel-based routing structure
- MVC-oriented application organization
- Database-ready Laravel structure
- Blade-based view layer
- Standard Laravel project configuration

---

## Tech Stack

- **PHP**
- **Laravel**
- **Blade**
- **HTML**
- **CSS**
- **JavaScript**
- **Composer**
- **Laravel Artisan**
- **Laravel MVC Structure**

---

## Architecture

The project follows Laravel’s standard MVC architecture:

- **Models** represent application data and database entities.
- **Controllers** handle request flow and application logic.
- **Routes** define how HTTP requests are mapped inside the application.
- **Views** render the user interface using Blade templates.
- **Database files** support migrations and persistence configuration.
- **Public assets** are served through Laravel’s `public/` directory.

This structure keeps application responsibilities separated and follows Laravel’s conventional organization for web applications.

---

## Project Structure

```text
laravel-service-scheduler/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
└── .editorconfig
```

### Main Directories

- `app/`  
  Contains the core Laravel application logic, including controllers, models, and application classes.

- `bootstrap/`  
  Contains framework bootstrap files responsible for initializing the Laravel application.

- `config/`  
  Stores Laravel configuration files.

- `database/`  
  Contains database-related resources such as migrations, factories, and seeders when available.

- `public/`  
  Public entry point of the application and location for publicly accessible assets.

- `resources/`  
  Contains Blade views and frontend-related resources.

- `routes/`  
  Defines the application routes.

- `storage/`  
  Stores framework-generated files such as logs, cache, and compiled files.

- `tests/`  
  Contains Laravel’s default testing structure.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/lucaspc6/laravel-service-scheduler.git
```

Access the project directory:

```bash
cd laravel-service-scheduler
```

Switch to the latest project branch:

```bash
git checkout v6
```

Install PHP dependencies:

```bash
composer install
```

Create the environment file:

```bash
cp .env.example .env
```

Generate the application key:

```bash
php artisan key:generate
```

Configure your database connection in the `.env` file.

Run database migrations:

```bash
php artisan migrate
```

---

## Running the Project

Start the Laravel development server:

```bash
php artisan serve
```

Open the application in your browser:

```text
http://127.0.0.1:8000
```

---

## Environment Variables

This project uses Laravel’s standard `.env` configuration file.

Common environment variables include:

```env
APP_NAME=
APP_ENV=
APP_KEY=
APP_DEBUG=
APP_URL=

DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

Update the database values according to your local development environment.

---

## Testing

The repository includes Laravel’s standard `tests/` directory.

If tests are configured in the project, they can be executed with:

```bash
php artisan test
```

---

## Screenshots

Screenshots are recommended to improve the visual presentation of this repository.

Suggested screenshots:

- Scheduling records listing page
- Create scheduling record form
- Edit scheduling record form
- Record details page, if available
- Delete confirmation flow, if available

---

## Future Improvements

Potential improvements for this project include:

- Add screenshots to the README
- Document the available routes
- Add sample data for easier local testing
- Improve form validation feedback
- Add automated tests for CRUD operations
- Improve the visual documentation of the application flow
- Add a brief explanation of the database tables used by the scheduling workflow

---

## Author

**Lucas Carvalho**

GitHub: [@lucaspc6](https://github.com/lucaspc6/)
