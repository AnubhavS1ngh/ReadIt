# ReadIt
ReadIt is an online bookstore that allows users to browse, search, and purchase books. This project includes various functionalities such as user authentication, shopping cart management, and an admin panel for managing products, orders, and users.

Features
User Authentication:

User registration and login functionality.
Session management to keep users logged in.
Product Management:

Users can view a list of books available for purchase.
Admins can add, edit, and delete books from the inventory.
Shopping Cart:

Users can add books to their shopping cart.
View and manage items in the cart.
Checkout process to complete the purchase.
Admin Panel:

Manage products, users, orders, and contacts.
View and handle user queries and contact requests.
Project Structure
arduino
Copy code
/bookwebsite
    ├── uploaded_img
    ├── about.php
    ├── add_to_cart.php
    ├── admin_contacts.php
    ├── admin_header.php
    ├── admin_orders.php
    ├── admin_page.php
    ├── admin_products.php
    ├── admin_users.php
    ├── cart.php
    ├── checkout.php
    ├── config.php
    ├── contact.php
    ├── footer.php
    ├── header.php
    ├── home.php
    ├── login.php
    ├── logout.php
    ├── orders.php
    ├── register.php
    ├── search_page.php
    ├── shop_db.sql
    ├── shop.php
Files Description
uploaded_img/: Directory for storing uploaded book images.
about.php: About page of the website.
add_to_cart.php: Script to handle adding items to the shopping cart.
admin_contacts.php: Admin page to manage contact queries.
admin_header.php: Common header file for admin pages.
admin_orders.php: Admin page to manage orders.
admin_page.php: Main admin dashboard.
admin_products.php: Admin page to manage products.
admin_users.php: Admin page to manage users.
cart.php: Shopping cart page.
checkout.php: Checkout page for finalizing purchases.
config.php: Configuration file for database connection.
contact.php: Contact page for user queries.
footer.php: Common footer file for the website.
header.php: Common header file for the website.
home.php: Home page of the website.
login.php: Login page for users.
logout.php: Script to handle user logout.
orders.php: User page to view their orders.
register.php: Registration page for new users.
search_page.php: Search functionality for books.
shop_db.sql: SQL file for database schema.
shop.php: Shop page to display available books.
Installation
Clone the repository.
Import the shop_db.sql file into your MySQL database.
Update the config.php file with your database credentials.
Start the PHP server and navigate to the home page.
Usage
User: Register, login, browse books, add to cart, and checkout.
Admin: Login to the admin panel, manage books, orders, users, and handle contact queries.
Contributions
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

License
This project is licensed under the MIT License.

