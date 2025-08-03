# 🛒 E-Commerce Website Project - PBL3

## 🔍 System Overview

This project is a simulation of an Amazon-like e-commerce website built using the Spring Framework (Java backend) and React (frontend). It was developed as part of our PBL3 project with a focus on clean API architecture, responsive UI, and practical user experience.

## 🌟 Key Features

- 🔐 User Authentication (Sign up, Login, Google OAuth)
- 🛍️ Product Browsing & Filtering by Categories
- 🧾 Shopping Cart and Order Management
- 📦 Dashboard for Product Management
- 📈 Analytics (Order statistics for Admin)

## 👥 User Roles & Permissions

### 🛠️ Admin
- 👤 Manage users: view list, lock accounts, assign roles.
- 🏬 Manage shops: approve or delete shop registrations.
- 📦 Manage products: approve, edit, or remove violating products.
- 📑 Manage orders: monitor transactions and resolve issues.
- 💬 Manage chat groups: handle discussions and user reports.

---

### 🛍️ Seller
- ➕ Post, edit, hide, or delete their own products.
- 📦 Handle shop-specific orders.
- 📊 View revenue stats and customer reviews.
- 🗣️ Join or create product-topic chat groups  
  _(e.g., “Korean Cosmetics”, “Affordable Electronics”)_.

---

### 🛒 Buyer (User)
- 🔎 Browse/search products, add to cart, place orders.
- ✍️ Leave reviews after purchasing.
- 💬 Join chat groups, ask questions, comment, or invite friends to shop together.


## 🖼️ UI/UX Screenshots

### 🏠 Home Page with Product Listing  
🖼️ A clean and responsive homepage that displays all available products with category filters.  
![Home Page](./MegarMart/src/main/resources/static/imgReadMe/Home-Page.png)

---

### 📄 Product Detail View  
🔍 Shows detailed product information, including image, description, and price.  
![Product Detail](./MegarMart/src/main/resources/static/imgReadMe/Product-Detail.png)

---

### 🛒 Shopping Cart  
🛍️ Allows users to review their selected products before placing an order.  
![Cart](./MegarMart/src/main/resources/static/imgReadMe/Buy-Product.png)

---

### 📧 Successful Order Notification via Gmail  
✉️ After placing an order, the user receives a confirmation email.  
![Alert](./MegarMart/src/main/resources/static/imgReadMe/tb_dathangthanhcong.png)

---

### 📊 Admin Dashboard  
🧑‍💼 View order statistics, revenue data, and overall shop performance.  
![Admin Dashboard](./MegarMart/src/main/resources/static/imgReadMe/Revenue-Report-Shop.png)

---

### 📈 Admin Graph Manager  
📉 Visual representation of revenue trends over time using interactive charts.  
![Admin Graph](./MegarMart/src/main/resources/static/imgReadMe/Graph-Revenue-Shop.png)

---

### 🛠️ Product Manager  
📦 Manage product list, update stock, and edit item information.  
![Product Manager](./MegarMart/src/main/resources/static/imgReadMe/Product-Manager.png)

---

### 💰 Product Revenue  
📑 Generate detailed reports of product income and best-selling items.  
![Report-Income](./MegarMart/src/main/resources/static/imgReadMe/Report-Income.png)


## 🚀 Technologies Used

- **Backend:** Java Spring MVC + Hibernate
- **Frontend:** HTML/CSS, Thymeleaf
- **Database:** MySQL
- **Tools:** Git, Figma (for UI design)


