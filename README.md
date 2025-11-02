# 🍰 CaKeZo - E-Commerce Cake Ordering System

## 🔥 About CaKeZo

CaKeZo is a full-stack Java e-commerce web application built to demonstrate real-world enterprise development using Java EE. It includes user authentication, product management, order processing, and admin control – designed with clean architecture and secure database operations. The project is ideal for learning core backend fundamentals and Java web development using Servlets and JSP.

## 🚀 Features

### 👨‍💻 User Module

- User registration & login
- View cake catalog
- Product Search & Filters
- Add to cart / Remove from cart
- Place orders with COD payment
- View order history & tracking
- Session management

### 🛠️ Admin Module

- Admin authentication & dashboard
- Add / Update / Delete cakes (CRUD operations)
- Manage categories
- Manage orders & order statuses
- View all users and transactions
- Product featured management

### ⚙️ Backend Features

- Session management for secure login
- Optimized SQL queries with DAO pattern
- Secure password handling
- Scalable MVC code structure
- Role-based access control

## 🛡️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript, Bootstrap |
| Backend | Java, JSP, Servlets |
| Database | MySQL + JDBC |
| Server | Apache Tomcat |
| Version Control | Git & GitHub |
| Design Pattern | Model-View-Controller (MVC) |

## ⚡ Installation & Setup

### ✅ Prerequisites

- JDK 8+ installed
- Eclipse IDE or IntelliJ
- Apache Tomcat 9+
- MySQL 5.7+ Database

### ✅ Steps

1. Clone the repository
   ```bash
   git clone https://github.com/Abhay2003-harne/cakezo.git
   ```

2. Import as **Dynamic Web Project** in Eclipse
   - File > Import > Existing Projects into Workspace
   - Select the CaKeZo folder

3. Configure **Apache Tomcat**
   - Add Apache Tomcat to Eclipse

4. Add **MySQL JDBC Connector** to `/WebContent/WEB-INF/lib/`

5. Import database schema
   ```sql
   CREATE DATABASE cakezo;
   USE cakezo;
   ```

6. Update database credentials in `DBConnection.java`
   ```
   Host: localhost
   Port: 3306
   Username: root
   Password: your_password
   ```

7. Run the project on Tomcat
   - Right-click project > Run As > Run on Server

## 🔧 Database Configuration

**Default DB Settings**
- URL: `jdbc:mysql://localhost:3306/cakezo`
- Username: `root`
- Password: `your_password`

## 📸 Output & Screenshots

### User Interface

#### 1. User Home Page
![User Home](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/01-UserHome.jpg)

#### 2. User Login Page
![User Login](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/02-UserLogin.jpg)

#### 3. Successful Login - Welcome
![Successful Login](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/03-SuccesfulLogin.jpg)

#### 4. Shopping Cart
![Shopping Cart](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/04-UserCart.jpg)

#### 5. My Orders
![My Orders](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/05-MyOrders.jpg)

### Admin Panel

#### 6. Admin Dashboard
![Admin Dashboard](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/06-AdminPanel.jpg)

#### 7. Manage Cakes
![Manage Cakes](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/07-ManageCakes.jpg)

#### 8. Manage Orders
![Manage Orders](https://raw.githubusercontent.com/Abhay2003-harne/cakezo/main/screenshots/08-ManageOrders.jpg)

## 📊 Database Schema

**Key Tables:**
- `users` - User accounts and authentication
- `products` - Cake products catalog
- `categories` - Product categories
- `cart` - Shopping cart items
- `orders` - Customer orders
- `order_items` - Order line items

## ✅ Future Enhancements

- 🔒 Email verification for registration
- 💳 Payment gateway integration (Razorpay/PayPal)
- 📧 Email notifications for orders
- ⭐ User ratings and reviews
- 🔍 Advanced search and filtering
- 📱 Mobile app version
- 📊 Admin analytics and reports
- 🎁 Coupon and discount system
- Add Spring Boot Migration
- Implement JWT Authentication
- Microservices Architecture

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📜 License

This project is for educational purposes and open source under MIT License.

## 👨‍💻 Author

**Abhay Harne**
Java Full Stack Developer

GitHub: [https://github.com/Abhay2003-harne](https://github.com/Abhay2003-harne)
LinkedIn: [https://www.linkedin.com/in/abhay-harne/](https://www.linkedin.com/in/abhay-harne/)

---

**Project Date:** November 2025  
**Status:** ✅ Complete & Functional