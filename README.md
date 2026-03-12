# 🍰 Bake With Us – Online Cake Ordering System

Bake With Us is a web-based cake ordering platform that allows users to browse cakes, customize orders, add items to cart, and place orders online while administrators manage products, accounts, and reviews.

---

# 📌 Features

* 🧁 Browse different types of cakes
* 🛒 Add cakes to cart and place orders
* 🎂 Customize cakes with extra stuffing
* 👤 User registration and login system
* ⭐ Customer reviews and ratings
* 🧾 Invoice generation for orders
* 🔑 Password recovery system
* ⚙️ Admin panel to manage cakes, users, and orders

---

# 🛠️ Technologies Used

| Technology         | Purpose                   |
| ------------------ | ------------------------- |
| **PHP**            | Backend server-side logic |
| **MySQL**          | Database management       |
| **HTML**           | Web page structure        |
| **CSS**            | Styling and layout        |
| **JavaScript**     | Client-side interactivity |
| **XAMPP / Apache** | Local server environment  |

---

# 📂 Project Structure

```
bake_with_us/
│
├── home.php                # Homepage
├── aboutus.php             # About page
├── cakes.php               # Display available cakes
├── cart.php                # Shopping cart page
├── cart_handler.php        # Cart operations
├── add_cake.php            # Admin adds new cakes
├── add_stuffing.php        # Add cake stuffing options
├── accounts.php            # Manage user accounts
├── admin.php               # Admin dashboard
├── forgot-password.php     # Password recovery
├── download_invoice.php    # Invoice generation
├── config.php              # Database configuration
│
├── images/                 # Cake and website images
│
└── other php files         # Review handling, deletion, fetching data
```

---

# ⚙️ Installation Guide

### 1️⃣ Install XAMPP

Download and install **XAMPP** from
[https://www.apachefriends.org/](https://www.apachefriends.org/)

### 2️⃣ Move Project

Copy the project folder to:

```
xampp/htdocs/
```

### 3️⃣ Start Server

Start the following services in **XAMPP Control Panel**

* Apache
* MySQL

### 4️⃣ Import Database

1. Open **phpMyAdmin**
2. Create a new database (e.g., `bake_with_us`)
3. Import the SQL file provided with the project

### 5️⃣ Run the Project

Open browser and go to:

```
http://localhost/bake_with_us/home.php
```

---

# 👨‍💻 Admin Features

Admins can:

* Add or remove cakes
* Manage stuffing options
* Manage user accounts
* Monitor orders
* Delete inappropriate reviews

---

# 📸 Screenshots

You can add screenshots here such as:

* Homepage
* Cake catalog
* Cart page
* Admin dashboard

---

# 🚀 Future Improvements

* Online payment gateway integration
* Order tracking system
* Email notifications for orders
* Mobile responsive UI
* Recommendation system for cakes

---
