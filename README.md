# Laravel Note App

This project is a simple Note-taking application built with Laravel. Its main purpose is to help me practice and apply the basics of building CRUD (Create, Read, Update, Delete) applications, as well as to serve as my introduction to PHP and the Laravel framework. This is my first time working with Laravel and PHP.

I followed a tutorial on YouTube to help guide me through the process of setting up and building this application.

## Features

- User authentication (login/register)
- Create, view, edit, and delete notes
- Notes are private to each user

## How to Run

1. **Clone the repository:**
   ```sh
   git clone https://github.com/xianonnnnn/laravel11-crash-course.git
   cd laravel11-crash-course
   ```

2. **Install PHP dependencies:**
   ```sh
   composer install
   ```

3. **Install Node dependencies:**
   ```sh
   npm install
   ```

4. **Copy the example environment file and set your environment variables:**
   ```sh
   cp .env.example .env
   ```

5. **Generate the application key:**
   ```sh
   php artisan key:generate
   ```

6. **Set up your database:**
   - Create a database and update your `.env` file with the correct database credentials.

7. **Run migrations:**
   ```sh
   php artisan migrate
   ```

8. **Build frontend assets:**
   ```sh
   npm run build
   ```

9. **Start the development server:**
   ```sh
   php artisan serve
   ```

10. Visit [http://localhost:8000](http://localhost:8000) in your browser.

---

This project is for learning purposes and is not intended for production use.

