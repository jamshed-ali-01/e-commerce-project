# E-Commerce Project

A Laravel-based e-commerce web application built as a learning project.

This project includes a customer-facing shopping website and an admin dashboard for managing products, categories, brands, orders, coupons, shipping, pages, and users.

## About This Project

This is a learning project created to practice Laravel web development, e-commerce flow, database handling, authentication, admin management, cart functionality, checkout process, Stripe payment integration, and order management.

The main purpose of this project is to improve practical backend development skills using Laravel and understand how real-world e-commerce applications are structured.

## Tech Stack

- PHP 8.1+
- Laravel 10
- MySQL
- Blade Templates
- Laravel Vite
- JavaScript
- Axios
- Stripe Payment Gateway
- Laravel Sanctum
- Intervention Image
- Hardevine Shopping Cart Package

## Main Features

### Customer Side

- Home page
- Shop page
- Product detail page
- Category and sub-category based product browsing
- Add to cart
- Update cart
- Delete cart item
- Checkout
- Stripe payment integration
- Apply discount coupon
- Product rating and reviews
- Wishlist
- Contact form
- Static pages
- User registration
- User login
- Forgot password
- Reset password
- User profile
- Change password
- My orders
- Order detail page

### Admin Side

- Admin login
- Admin dashboard
- Category management
- Sub-category management
- Brand management
- Product management
- Product image upload
- Static page management
- Shipping management
- Discount coupon management
- Order management
- Change order status
- Send invoice email
- Admin password change

## Project Structure

```bash
e-commerce-project/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Middleware/
│   ├── Models/
│   └── helpers/
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   └── seeders/
├── public/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
├── routes/
│   └── web.php
├── storage/
├── composer.json
├── package.json
└── README.md
```

## Installation Guide

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/jamshed-ali-01/e-commerce-project.git
cd e-commerce-project
```

### 2. Install PHP Dependencies

```bash
composer install
```

### 3. Install Node Dependencies

```bash
npm install
```

### 4. Create Environment File

```bash
cp .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Configure Database

Open the `.env` file and update your database details:

```env
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

### 7. Run Migrations

```bash
php artisan migrate
```

### 8. Run Seeders

```bash
php artisan db:seed
```

### 9. Create Storage Link

```bash
php artisan storage:link
```

### 10. Run Vite Development Server

```bash
npm run dev
```

### 11. Run Laravel Development Server

Open another terminal and run:

```bash
php artisan serve
```

Now open the project in your browser:

```bash
http://127.0.0.1:8000
```

## Stripe Setup

This project includes Stripe payment integration.

Add your Stripe keys in the `.env` file:

```env
STRIPE_KEY=your_stripe_publishable_key
STRIPE_SECRET=your_stripe_secret_key
```

## Common Commands

```bash
php artisan serve
```

```bash
npm run dev
```

```bash
npm run build
```

```bash
php artisan migrate
```

```bash
php artisan db:seed
```

```bash
php artisan optimize:clear
```

## Admin Panel

Admin panel routes are available under:

```bash
/admin/login
```

From the admin dashboard, the admin can manage products, categories, brands, orders, coupons, shipping charges, and static pages.

## Learning Goals

Through this project, I practiced:

- Laravel MVC structure
- Routing and controllers
- Blade templating
- Authentication
- Admin dashboard development
- CRUD operations
- Product and category management
- Cart and checkout flow
- Stripe payment integration
- Order management
- Image upload handling
- Database migrations and seeders
- Frontend asset handling using Vite

## Future Improvements

- Improve UI and responsiveness
- Add product search suggestions
- Add advanced filters
- Add email verification
- Improve admin dashboard statistics
- Add product stock alerts
- Add order tracking page
- Add REST APIs for mobile app support
- Improve security and validation
- Add automated tests

## Repository

GitHub Repository:  
https://github.com/jamshed-ali-01/e-commerce-project

## Author

**Jamshed Ali**

GitHub: [jamshed-ali-01](https://github.com/jamshed-ali-01)

## Note

This project is created for learning and practice purposes.

It may not be fully production-ready, but it demonstrates the core workflow of a Laravel-based e-commerce application.
