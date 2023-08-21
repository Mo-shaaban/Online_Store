
# Laptic Online Laptop Store

## Introduction

Laptic is an online laptop store project developed using PHP, JavaScript, HTML, CSS, and MySQL. This project allows users to browse, search for, and purchase laptops conveniently through a web interface.

## Prerequisites

Before you can run the project, ensure you have the following prerequisites installed:

- PHP (>= 7.0)
- MySQL (>= 5.7)
- A web server (e.g., Apache, Nginx)
- Web browser (Chrome, Firefox, etc.)

## Installation

1. Clone this repository to your local machine:

git clone https://github.com/yourusername/laptic.git

sql
Copy code

2. Create a MySQL database for the project and import the provided SQL schema:

mysql -u your_username -p your_database_name < database.sql

php
Copy code

3. Configure the database connection by editing `config.php`:

```php
$host = 'localhost'; // Your MySQL host
$username = 'your_username'; // Your MySQL username
$password = 'your_password'; // Your MySQL password
$database = 'your_database_name'; // Your MySQL database name
```

4.Place the project files in your web server's document root directory.

##Usage

  Start your web server.

  Open a web browser and navigate to http://localhost/Online_Store/Laptic/home.php.

  You should now see the Laptic Online Laptop Store homepage.

##Features
Browse a wide selection of laptops.
Search for laptops by brand, specifications, and price range.
Add laptops to your shopping cart.
Checkout and complete your purchase.
User account management (login and registration).

##License
This project is licensed under the MIT License.

##Contact
If you have any questions or issues, please contact your.email@example.com.

Happy shopping with Laptic!


