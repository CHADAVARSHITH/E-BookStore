📚 Bookstore Management System (PHP + MySQL)
A simple E-commerce Bookstore Website built using PHP, MySQL, HTML, CSS, and JavaScript.
This project allows users to browse, rate, and purchase books online, and provides an admin panel for managing books and orders.

🚀 Features
📖 Browse and search books
🛒 Add to cart and place orders
⭐ Rate and review books
👤 User login and signup
🧾 View order history
⚙️ Admin panel for managing books and orders
🧩 Requirements
XAMPP (or WAMP / MAMP / LAMP)
Web browser (Chrome / Edge / Firefox)
Basic knowledge of PHP and MySQL
⚙️ Setup Instructions
1. Install XAMPP
Download and install XAMPP from: 👉 https://www.apachefriends.org

2. Start Apache and MySQL
Open the XAMPP Control Panel and click Start next to:

Apache
MySQL
Both should show a green “Running” status.

3. Clone or Copy the Project
On Windows:
C:\xampp\htdocs\
Clone or copy this repository into the above folder:

C:\xampp\htdocs\Bookstore-Management-System-PHP-MySQL-Project
On WAMP:
C:\wamp64\www\
4. Create the Database
Open your browser and go to:
http://localhost/phpmyadmin
Click Databases → create a new database named:
bookstoredatabase
5. Import the Database Schema
Inside phpMyAdmin, select bookstoredatabase
Click the SQL tab
Open the database.sql file from your project folder
Copy the contents and paste them into the SQL window
Click Go
This creates all required tables automatically.

6. Configure Database Connection (if needed)
Open the file:

config.php
or sometimes:

includes/connection.php
Ensure these settings match your local setup:

$servername = "localhost";
$username = "root";
$password = "";
$database = "bookstoredatabase";
Save the file.

7. Run the Project
Open your browser and visit:

http://localhost/Bookstore-Management-System-PHP-MySQL-Project/index.php
You should now see your Bookstore Homepage 🎉
