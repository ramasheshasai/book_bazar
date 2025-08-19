# BOOKBAZAR - Online Book Store

A simple online bookstore built with PHP and MySQL where users can browse, purchase books, and admins can manage inventory.

## Features

- **User Features:**
  - Browse and search books
  - Add books to shopping cart
  - Secure checkout process
  - View order history

- **Admin Features:**
  - Add, edit, and delete books
  - Manage user orders
  - View customer messages
  - Dashboard with sales analytics

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Responsive Design:** Mobile and desktop compatible

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/BOOKBAZAR.git
   cd BOOKBAZAR
   ```

2. **Set up the database:**
   - Import `shop_db.sql` into your MySQL database
   - Update database credentials in `config.php`

3. **Configure web server:**
   - Place files in your web server directory (htdocs for XAMPP)
   - Start Apache and MySQL services

4. **Access the application:**
   - Open `http://localhost/BOOKBAZAR` in your browser
   - Register as a new user or admin

## Default Login

- **Admin:** Create admin account during registration
- **User:** Register as regular user

## Project Structure

- `home.php` - Main homepage
- `shop.php` - Product catalog
- `cart.php` - Shopping cart
- `admin_page.php` - Admin dashboard
- `config.php` - Database configuration
- `css/` - Stylesheets
- `js/` - JavaScript files
- `images/` - Static images

## Contributing

Feel free to fork this project and submit pull requests for improvements.
