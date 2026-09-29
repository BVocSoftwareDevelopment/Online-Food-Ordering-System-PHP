# Online-Food-Ordering-System-PHP
A PHP and MySQL based Online Food Ordering System with separate admin and user-side modules for managing food categories, food items, and orders.

# Online Food Ordering System

A web-based **Online Food Ordering System** developed using **PHP, MySQL, HTML, CSS, and JavaScript**. The project demonstrates the development of a database-driven web application with separate modules for food management, categories, user interaction, and order processing.

The project is designed as an academic and practical web development project for students learning **PHP, MySQL, backend development, database integration, and full-stack web application development**.

---

## 📌 Project Overview

The Online Food Ordering System provides a web-based platform where food-related information can be displayed and managed through a structured application.

The project contains separate areas for:

* User-side food browsing
* Food categories
* Food search
* Food ordering
* Order-related operations
* Administrative management
* Food management
* Category management
* Admin management
* User authentication
* Database connectivity

The project follows a modular folder structure containing PHP files, CSS stylesheets, JavaScript, images, reusable partial files, configuration files, and database resources.

---

## 🛠️ Technologies Used

The project uses the following technologies:

* **PHP**
* **MySQL**
* **HTML5**
* **CSS3**
* **JavaScript**
* **SQL**

### Backend

* PHP

### Database

* MySQL

### Frontend

* HTML
* CSS
* JavaScript

---

## 📂 Project Structure

```text
Online Food Ordering System/
│
├── admin/
│   ├── partials/
│   │   ├── footer.php
│   │   ├── header.php
│   │   └── user_logged.php
│   │
│   ├── add_admin.php
│   ├── add_category.php
│   ├── add_food.php
│   ├── admin.php
│   ├── category.php
│   ├── change_pwd.php
│   ├── datatable.php
│   ├── delete.php
│   ├── delete_admin.php
│   ├── delete_category.php
│   ├── delete_order.php
│   ├── edit_admin.php
│   ├── food.php
│   ├── index.php
│   ├── login.php
│   ├── logout.php
│   ├── order.php
│   ├── update_category.php
│   └── update_food.php
│
├── config/
│   └── constants.php
│
├── css/
│   ├── admin.css
│   ├── login.css
│   └── style.css
│
├── databasefiles/
│   ├── 01 LOGIN DETAILS & PROJECT INFO.txt
│   └── food_order.sql
│
├── images/
│
├── js/
│   └── app.js
│
├── partials/
│   ├── footer.php
│   └── header.php
│
└── stem/
    ├── categories.php
    ├── category-foods.php
    ├── food-search.php
    ├── foods.php
    ├── index.php
    └── order.php
```

---

## 👨‍💼 Admin Module

The `admin` directory contains the administrative section of the application.

The available PHP files indicate functionality related to:

* Admin login
* Admin management
* Category management
* Food management
* Order management
* Adding food items
* Updating food items
* Deleting food items
* Adding and updating categories
* Deleting categories
* Changing password
* Admin logout
* Order deletion
* Data table management

### Admin Components

The `admin/partials/` directory contains reusable PHP files such as:

* `header.php`
* `footer.php`
* `user_logged.php`

These files can be used to maintain common sections across administrative pages.

---

## 🍔 Food Management

The project includes PHP files for managing food-related information, including:

* Adding food items
* Displaying food items
* Updating food information
* Deleting food information
* Managing food categories

Relevant files include:

```text
add_food.php
food.php
update_food.php
delete.php
```

---

## 🗂️ Category Management

The system contains functionality for managing food categories.

Relevant files include:

```text
add_category.php
category.php
update_category.php
delete_category.php
```

These files provide the basic structure required for handling category-related operations.

---

## 🛒 Order Management

The project contains order-related PHP files on both the administrative and user-facing sides.

### Admin Side

```text
admin/order.php
admin/delete_order.php
```

### User Side

```text
stem/order.php
```

This structure indicates that order-related operations are handled through separate administrative and frontend components.

---

## 👤 User-Side Module

The `stem` directory contains the main user-facing PHP pages.

It includes:

```text
index.php
categories.php
category-foods.php
food-search.php
foods.php
order.php
```

These pages provide the structure for browsing categories, viewing food items, searching for food, and placing orders.

---

## 🔐 Login and Authentication

The project includes authentication-related functionality in the administrative section.

Relevant files include:

```text
admin/login.php
admin/logout.php
admin/change_pwd.php
admin/partials/user_logged.php
```

The project also includes a database information file:

```text
01 LOGIN DETAILS & PROJECT INFO.txt
```

For security reasons, actual login credentials should **not be published publicly** in a GitHub repository. Before making the repository public, sensitive credentials should be removed or replaced with sample credentials.

---

## 🗄️ Database

The project includes an SQL database file:

```text
databasefiles/food_order.sql
```

This file can be used as the database source for setting up the application's MySQL database, subject to the actual database structure contained in the SQL file.

---

## ⚙️ Configuration

The project contains:

```text
config/constants.php
```

This file is part of the application's configuration structure.

Before deployment, database credentials and other environment-specific settings should be configured appropriately.

---

## 🎨 CSS and JavaScript

### CSS

The project contains separate stylesheets:

```text
css/
├── admin.css
├── login.css
└── style.css
```

These files provide styling for different parts of the application.

### JavaScript

The project contains:

```text
js/app.js
```

which provides the JavaScript component of the application.

---

## 🖥️ Local Setup

Since this is a PHP and MySQL based project, it requires a local server environment.

### Recommended Environment

Students can use:

* XAMPP
* Apache
* MySQL
* PHP
* phpMyAdmin
* Modern Web Browser

---

## 🚀 Installation Steps

### Step 1: Install XAMPP

Install and configure XAMPP on your computer.

Start:

```text
Apache
MySQL
```

from the XAMPP Control Panel.

---

### Step 2: Copy the Project

Copy the project folder into the XAMPP web directory:

```text
xampp/htdocs/
```

For example:

```text
xampp/htdocs/Online Food Ordering System/
```

---

### Step 3: Create the Database

Open:

```text
http://localhost/phpmyadmin
```

Create the required MySQL database and import:

```text
databasefiles/food_order.sql
```

---

### Step 4: Configure the Application

Check:

```text
config/constants.php
```

and configure the database connection according to your local MySQL environment.

---

### Step 5: Run the Application

Start Apache and MySQL from XAMPP.

Then open the project through your browser using the appropriate localhost URL.

For example:

```text
http://localhost/Online%20Food%20Ordering%20System/
```

The exact URL may vary depending on the project folder name and local configuration.

---

## 🎯 Learning Objectives

This project provides practical exposure to:

* PHP programming
* MySQL database integration
* CRUD operations
* User authentication
* Admin authentication
* Form handling
* Database-driven web applications
* Food category management
* Food item management
* Order management
* PHP include/partial files
* Server-side programming
* SQL database management
* HTML and CSS integration
* JavaScript integration
* Local server configuration

---

## 📚 Concepts Demonstrated

The project can be used to understand important backend development concepts such as:

### 1. CRUD Operations

Students can study how applications perform:

* Create
* Read
* Update
* Delete

operations using PHP and MySQL.

### 2. Database Connectivity

The project demonstrates the structure of a PHP application working with a MySQL database.

### 3. Authentication

The project includes an administrative login and logout structure.

### 4. Modular PHP Development

Reusable components such as:

```text
header.php
footer.php
```

are maintained separately and can be included across multiple pages.

### 5. Database-Driven Application

Food, categories, and order-related information can be handled through PHP and MySQL rather than static HTML pages.

---

## 🎓 Academic Context

This project is suitable for practical learning and demonstration in the:

**B.Voc in Software Development**
**Department of Vocational Education**
**Indira Gandhi National Tribal University (IGNTU)**
**Amarkantak, Madhya Pradesh, India**

It can be used as an academic example for learning **Backend Development with PHP and MySQL** and database-driven web application development.

---

## 💡 Possible Future Improvements

Students can further enhance the project by implementing:

* Responsive mobile-first design
* Improved UI/UX
* Secure password hashing
* Session security
* Input validation
* Server-side validation
* CSRF protection
* Prepared SQL statements
* User registration and authentication
* User profile management
* Online payment integration
* Order status tracking
* Order history
* Restaurant/food image management
* Search and filtering improvements
* Admin dashboard statistics
* Email notifications
* REST API integration
* Deployment to a production server

---

## ⚠️ Security Note

This project is intended primarily for **academic and learning purposes**.

Before deploying the application publicly:

* Remove real database credentials.
* Do not publish real usernames or passwords.
* Use secure password hashing.
* Validate and sanitize user input.
* Use prepared statements for database queries.
* Protect administrative pages.
* Configure production database credentials securely.
* Review uploaded files and configuration files for sensitive information.

---

## 📌 Project Information

**Project:** Online Food Ordering System
**Type:** Web Application
**Level:** Academic / Student Project
**Backend:** PHP
**Database:** MySQL
**Frontend:** HTML, CSS, JavaScript
**Application Type:** Database-Driven Web Application

---

## 🙏 Acknowledgement

This project is maintained as part of practical and academic learning activities in web and backend development.

It is intended to help students understand how individual frontend and backend concepts can be combined to develop a functional database-driven web application using PHP and MySQL.
