# 💊 E-Pharmacy 

This is a complete PHP-based e-pharmacy website.  
It allows customers to browse medical products, add them to a shopping cart, place orders, and manage their accounts.  
The system uses a MySQL database and includes both frontend and backend components.

---

## 🚀 Features

✅ User registration and login  
✅ Product browsing and search  
✅ Shopping cart and checkout  
✅ Order management system  
✅ MySQL database integration  
✅ Responsive UI with Bootstrap

---

## 🛠️ Technologies Used

- **Backend:** PHP  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Database:** MySQL  
- **Other Tools:** jQuery, phpMyAdmin

---

## 📁 Project Structure

```bash
/src
├── index.php
├── about.php
├── cart.php
├── checkout.php
├── login.php
├── register.php
├── logout.php
├── place_order.php
├── db_connect.php
├── css/
├── js/
└── images/
pharmacy_db.sql → database schema and sample data
```

🧩 Main Functional Pages

Page	Description
index.php	Home page, product listings
about.php	About the e-pharmacy
login.php	User login interface
register.php	User signup form
cart.php	Shopping cart overview
checkout.php	Checkout form, payment setup
place_order.php	Order placement logic
db_connect.php	Database connection file

🛑 Requirements

PHP 7.4 or higher
MySQL 5.7 or higher
Apache server (for local development)

## Admin
Login: Kamron@gmail.com
Parol: kamron@03

🤝 Contribution Guide

Fork this repository
Create a new branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/YourFeature)
Open a Pull Request

🕒 Changelog

Version 1.0
Initial release with main features: login, cart, checkout.

Version 1.1
UI improvements, added security enhancements.

🐛 Known Issues

Some user error messages are only in English.
Search functionality may not support partial keyword matching.

🚀 Future Improvements

Add product categories and filtering options.
Build an admin dashboard for managing products and orders.
Integrate secure payment gateways (PayPal, Stripe, etc.).
Improve UI/UX with React or Vue frontend.
Add email notifications for order status and account activities.

Project Description

Developed an e-commerce website for a pharmacy. 
After logging in, the available products/services in the system are listed to the user. Any medicine can be searched in the search box. 
The user can also filter out the medicines based on categories provided. 
Paging functionality for listing products/services has been implemented. 
After selecting a particular medicine, the user can update the quantity of the product. 
User can also update items in the cart, like removing items from the cart and updating the product’s quantity. 
The project also shows the history of purchases or saved lists for the user. 
After selecting the products, the user goes for the payment option and enters the billing details. 
In the billing section, promo code or deal code can be applied, resulting in some discount for the final bill due.

For the admin part : The admin can view, delete and insert the products and category to the table. 
He/she can also view the users and their orders.

Additional feature: The user can enter a coupon code to get a discount on his/her total bill.
