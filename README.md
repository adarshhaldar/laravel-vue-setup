# Guide Link
https://medium.com/@hadarsh04/laravel-vue-basic-integration-and-setup-vite-9497b63d2bdf

# Laravel + Vue.js Basic Integration

This repository demonstrates the basic integration of Laravel (backend) and Vue.js (frontend) to create a scalable.

---

## **Prerequisites**

Ensure you have the following installed:

- Composer
- PHP >= 8.0
- Laravel 11
- Node

---

## **Setup Instructions**

### 1. Clone the Repository

### 2. Install Laravel Dependencies
```bash
composer update
```

### 3. Install Frontend Dependencies
```bash
npm install
```

### 4. Configure Environment Variables
- Copy the `.env.example` file to `.env`:
  ```bash
  cp .env.example .env
  ```
- Set up your database credentials in the `.env` file.

### 5. Run Database Migrations
```bash
php artisan migrate
```

### 6. Build Frontend Assets
```bash
npm run dev
```

### 7. Start the Development Server
- Start the Laravel server:
  ```bash
  php artisan serve
  ```

---

## **Project Structure**

### Key Files and Directories

- **`resources/js/app.js`**: Entry point for Vue.js.
- **`resources/js/components/App.vue`**: App Vue component.
- **`vite.config.js`**: Laravel Vite configuration.
- **`routes/web.php`**: Web routes.
- **`resources/views/index.blade.php`**: Blade template where Vue component is mounted.

---

Happy coding!
