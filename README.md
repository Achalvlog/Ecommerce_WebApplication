# 🛒 E-Commerce Web Application

A full-stack **E-Commerce Web Application** built using **Spring Boot**, designed to handle real-world online shopping workflows with user and admin roles.

---

## 🚀 Features

### 👤 User Features
- User Registration & Login (Spring Security)
- Forgot Password (Email-based reset)
- Browse Products
- Add Products to Cart
- Checkout with Billing Address
- Select Payment Mode
- Place Order
- Cancel Order with Email Confirmation

### 🛠️ Admin Features
- Admin Login
- Add / Update / Delete Products
- Activate / Deactivate Users
- Manage Orders
- View User Details

---

## 🧰 Tech Stack

- **Backend:** Java, Spring Boot
- **Security:** Spring Security
- **ORM:** Hibernate / JPA
- **Database:** MySQL
- **Frontend:** Thymeleaf, HTML, CSS, Bootstrap
- **Email:** JavaMailSender
- **Build Tool:** Maven

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Achalvlog/Ecommerce_WebApplication.git


2️⃣ Configure Database

spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password


**Configure Email (for password reset & order confirmation)
<img width="1724" height="918" alt="Screenshot 2026-01-23 010340" src="https://github.com/user-attachments/assets/45632dd8-c124-4a00-940a-eed8d51d0589" />
<img width="1105" height="607" alt="Screenshot 2026-01-26 020330" src="https://github.com/user-attachments/assets/a05bd4c1-b5f2-414b-bbe7-45dcfbafee2b" />
<img width="1906" height="883" alt="Screenshot 2026-01-26 020352" src="https://github.com/user-attachments/assets/2535626d-a68e-4ed1-b9a8-6e6d5330a762" />
<img width="1865" height="721" alt="Screenshot 2026-01-26 020418" src="https://github.com/user-attachments/assets/6ef976a9-8d61-4c3e-965d-abe2dcc6c965" />
<img width="1757" height="764" alt="Screenshot 2026-01-26 020434" src="https://github.com/user-attachments/assets/c6cfc48f-90cc-45b2-91bc-41dea6b725be" />
<img width="1895" height="806" alt="Screenshot 2026-01-26 020444" src="https://github.com/user-attachments/assets/43637240-7064-4c93-a63a-d2be31700106" />

spring.mail.username=your_email
spring.mail.password=your_email_password

mvn spring-boot:run
**Open in browser
**http://localhost:8080
