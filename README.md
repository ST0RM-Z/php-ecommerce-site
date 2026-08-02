# PHP E-Commerce Site

A full e-commerce site built in PHP, with a customer-facing storefront and an admin panel for managing products and orders.

## Features

- Product catalog, cart, and checkout flow (`addToCart.php`, `cart.php`)
- Admin panel for managing products (`admin.php`, `adminedit.php`, `admininsert.php`, `admindelete.php`, `adminupdate.php`)
- Session-based user authentication (credentials stored in session)
- Transactional email via PHPMailer

## Tech Stack

- PHP
- HTML5 / CSS3
- Bootstrap 5

## Setup

1. Import the database using `dbinit.php` to create and hash the initial user table:
   ```
   https://localhost/php-ecommerce-site/dbinit.php
   ```
2. Log in as admin with `user1@mail.com` / `root`.

## Live Demo

[shoperhub.vercel.app](https://shoperhub.vercel.app)

## Author

Dhairya Arya
