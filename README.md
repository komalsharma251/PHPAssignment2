
# PHP Tech Support Project

**Author:** Komal Sharma  
**Date:** February 2, 2026  
**Project Type:** Web Application (PHP, MySQL)

## Overview

This is a **Tech Support Management System** built with PHP and MySQL.  
The project allows administrators to manage products, technicians, and client requests efficiently. It is structured with clean MVC principles and uses a MySQL database for data storage.

## Features

 **Admin Panel**
  - Add, delete, and manage products
  - Manage technicians
  - View and handle errors
 **User Management**
  - Contact form for customer inquiries
  - Track orders and appointments (can be expanded)
 **Database**
  - MySQL database (`db/tech_support.sql`)
  - Stores products, technicians, and other project data

## Project Structure

PHPAssignment2/
├── controllers/ # PHP controller files
├── db/ # Database files & SQL export
├── views/ # Frontend HTML/PHP templates
│ └── admin/ # Admin panel views
├── index.php # Main entry point
├── README.md # Project documentation
└── LICENSE # License file


## Installation

1. Clone the repository:

```bash
git clone https://github.com/komalsharma251/PHPAssignment2.git
Import the database:

Open db/tech_support.sql in your MySQL client (e.g., phpMyAdmin, MySQL Workbench)

Execute the SQL to create the database and tables

Configure database connection:

Open db/database.php

Update the credentials:

$host = 'localhost';
$db_name = 'your_database_name';
$username = 'your_db_user';
$password = 'your_db_password';
Run the project:

Place the project folder in your web server directory (e.g., XAMPP htdocs)

Open http://localhost/PHPAssignment2/ in your browser

Dependencies
PHP 7.x or higher

MySQL 5.x or higher

Optional: XAMPP / MAMP / LAMP stack

Screenshots
<img width="1470" height="956" alt="Screenshot 2026-02-01 at 10 34 17 PM" src="https://github.com/user-attachments/assets/44851332-387c-484b-892e-54f30a497e3a" />

<img width="1470" height="956" alt="Screenshot 2026-02-01 at 10 35 33 PM" src="https://github.com/user-attachments/assets/ea7c0a08-28fd-4a72-b08c-a9dc700060c2" />

<img width="1470" height="956" alt="Screenshot 2026-02-01 at 10 35 42 PM" src="https://github.com/user-attachments/assets/5ebfeb7c-8ebe-40bc-b7f9-cbf39bb7011c" />

<img width="1470" height="956" alt="Screenshot 2026-02-01 at 10 34 17 PM" src="https://github.com/user-attachments/assets/f8a16c49-df04-42e6-8426-7a84c397aecb" />


License

This project is licensed under the MIT License
(Add screenshots of your project here if desired, e.g., admin panel, homepage)

