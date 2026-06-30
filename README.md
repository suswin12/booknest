# booknest
BookNest is a simple Laravel Book Store web application developed using Laravel, Blade Templates, MySQL, Bootstrap, and Google Books API.

This project includes:

- User Home Page
- Book Details Page
- Add To Cart
- Login System
- Admin Dashboard
- CRUD Operations
- Google Books API Integration
- MVC Architecture

 Features

 User Features

- View all books
- View book details
- Add books to cart
- Login required for cart access
- Responsive UI

---
 Admin Features

- Admin Login
- Admin Dashboard
- Add Book
- Edit Book
- Delete Book
- Manage Price & Availability

---

 Technologies Used

| Technology | Purpose |
|------------|---------|
| Laravel | Backend Framework |
| PHP | Server-side Language |
| Blade | Frontend Templating |
| MySQL | Database |
| Google Books API | External API Integration |



 Installation Steps

1 Clone Repository

git clone https://github.com/suswin12/booknest.git

2 Open Project Folder

cd booknest

3 Install Dependencies

composer install

---

4️ Create Environment File

copy .env.example .env

---

5 Generate Application Key

php artisan key:generate

---

6 Configure Database

Open `.env` file and update:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bookstore
DB_USERNAME=root
DB_PASSWORD=
```

7 Create Database

Open phpMyAdmin and create database:

bookstore


---

8 Run Migrations

```bash
php artisan migrate
```

---

9 Start Laravel Server

```bash
php artisan serve
```

Open in browser:

http://127.0.0.1:8000


Admin Login Credentials

Email: admin@gmail.com
Password: admin123


 Google Books API

This project uses Google Books API to fetch programming books dynamically.

API Used:

```bash
https://www.googleapis.com/books/v1/volumes?q=programming
```

---

#  MVC Architecture Used

## Model
Handles database operations.

```bash
Book.php
```

---

## View
Handles frontend UI using Blade Templates.

```bash
home.blade.php
cart.blade.php
dashboard.blade.php
```

---

## Controller
Handles business logic.

```bash
BookController.php
AdminController.php
```

---

# 📸 Project Pages

- Home Page
- Login Page
- Admin Dashboard
- Book Details Page
- Cart Page



# 👨‍💻 Author

Developed by **Suswin Prasath**

GitHub :
https://github.com/suswin12
