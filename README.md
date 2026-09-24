# 🐘 PostgreCon — Laravel PostgreSQL Integration

A clean and simple **Laravel** application configured with a **PostgreSQL** database connection and student data schema.

---

## 🛠️ Tech Stack
- **Framework**: Laravel 13 (PHP 8.3+)
- **Database**: PostgreSQL
- **Frontend**: Blade / Vite

---

## 🚀 Setup & Installation

### 1. Clone & Install Dependencies
`ash
git clone https://github.com/Ambartiwari2001/postgrecon.git
cd postgrecon
composer install
npm install
`

### 2. Environment Configuration
Copy .env.example to .env and set your PostgreSQL database credentials:
`env
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=your_db_name
DB_USERNAME=your_postgres_username
DB_PASSWORD=your_postgres_password
`

Generate application key:
`ash
php artisan key:generate
`

### 3. Run Migrations
`ash
php artisan migrate
`

### 4. Run Development Server
`ash
php artisan serve
`

---

## 📄 License
This project is open-source software licensed under the [MIT License](LICENSE).
