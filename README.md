# Food Ordering Website - PHP

A full-stack food ordering web application built with PHP, MySQL, HTML, CSS, and JavaScript. It includes a customer-facing storefront and an admin dashboard for managing products, orders, users, and messages.

## Features

### User
- Register, login, and manage profile/address
- Browse menu by category and search products
- Quick view product details
- Add items to cart and update quantities
- Checkout and place orders
- View order history
- Contact form

### Admin
- Secure admin login and registration
- Dashboard with overview stats
- Manage products (add, update, delete)
- Manage placed orders and update status
- Manage user and admin accounts
- View customer messages

## Tech Stack
- **Backend:** PHP (PDO for MySQL)
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, JavaScript
- **Libraries:** Swiper.js, Font Awesome

## Project Structure
```
├── admin/              # Admin panel pages
├── components/         # Shared PHP components (header, footer, db connection)
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── images/             # UI images
├── project images/     # Product images
├── food_db.sql         # Database schema
└── *.php               # User-facing pages
```

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/food-ordering-website.git
   ```

2. **Set up a local server**
   - Install [XAMPP](https://www.apachefriends.org/) or any PHP/MySQL stack
   - Move the project folder into `htdocs/`

3. **Import the database**
   - Open phpMyAdmin
   - Create a database named `food_db`
   - Import `food_db.sql`

4. **Configure database connection**
   - Edit `components/connect.php` if your MySQL credentials differ:
     ```php
     $db_name = 'mysql:host=localhost;dbname=food_db';
     $user_name = 'root';
     $user_password = '';
     ```

5. **Run the project**
   - Start Apache and MySQL in XAMPP
   - Visit `http://localhost/food-ordering-website/home.php`
   - Admin panel: `http://localhost/food-ordering-website/admin/admin_login.php`

## Author
**Arsany Naim**