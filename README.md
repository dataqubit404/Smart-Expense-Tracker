# 💰 Smart Expense Tracker (MERN Stack)

A full-stack web application that helps users manage daily expenses with secure authentication, budgeting, and visual analytics.

Built using the **MERN Stack — MongoDB, Express.js, React.js, Node.js**

---

## 🎯 Project Overview

Managing personal finances is essential in modern life. This application allows users to:

- Track daily spending 💸  
- Categorize expenses 📂  
- Set monthly budgets 🎯  
- Visualize spending patterns 📊  
- Securely store personal financial data 🔐  

---

## 🚀 Features

### 🔐 User Authentication
- User Registration & Login  
- Secure password hashing using bcrypt  
- JWT-based authentication  
- Protected routes  
- Logout functionality  

---

### 💸 Expense Management
- Add new expense  
- Edit expense  
- Delete expense  
- View all expenses  
- Filter by date/category  

Each expense contains:

- Amount 💰  
- Category 📂  
- Description 📝  
- Date 📅  
- Payment Method 💳  

---

### 📊 Dashboard
- Total spending (monthly)  
- Today's expenses  
- Category-wise summary  
- Recent transactions  

---

### 🎯 Budget Management
- Set monthly budget  
- Track remaining balance  
- Overspending alerts ⚠️  

---

### 📈 Reports & Analytics
- Category-wise pie chart  
- Monthly spending trends  
- Visual insights into expenses  

---

### 📱 Responsive UI
- Mobile-friendly design  
- Clean modern interface  
- Works across devices  

---

## 🛠️ Tech Stack

### Frontend
- React.js ⚛️  
- HTML5  
- CSS3  
- JavaScript (ES6+)  
- Axios  
- Chart.js / Recharts  

### Backend
- Node.js 🟢  
- Express.js 🚀  

### Database
- MongoDB 🍃  
- Mongoose ODM  

### Authentication & Security
- JWT (JSON Web Tokens)  
- bcrypt (Password Hashing)  

---

## 🏗️ System Architecture
User → React Frontend → Express API → MongoDB Database

---

## 🗄️ Database Design

### 👤 Users Collection
- _id  
- name  
- email  
- password (hashed)  
- createdAt  

### 💸 Expenses Collection
- _id  
- userId (reference)  
- amount  
- category  
- description  
- date  
- paymentMethod  

### 🎯 Budgets Collection
- _id  
- userId  
- month  
- amount  

---

## 🖥️ Application Modules

- Authentication Module 🔐  
- Dashboard 📊  
- Expense Management 💸  
- Budget Tracker 🎯  
- Reports & Analytics 📈  
- User Profile ⚙️  

---

## 🔒 Security Features

- Encrypted passwords  
- Token-based authentication  
- Input validation  
- Protected API routes  
- Secure user sessions  

---

## 🔄 Workflow

1. User registers an account  
2. Logs in securely  
3. Sets monthly budget  
4. Adds daily expenses  
5. Views dashboard analytics  
6. Monitors spending trends  

---

## 🎓 Academic Relevance

This project demonstrates:

- Full-Stack Development  
- REST API Design  
- Database Modeling  
- Authentication & Security  
- Data Visualization  
- Real-World Problem Solving  

Ideal for **Final Year B.Tech / BCA / MCA Projects**

---

## 🌟 Future Enhancements

- AI-based spending insights 🤖  
- Receipt scanning using OCR 📷  
- Multi-currency support 💱  
- Export reports (PDF/Excel) 📄  
- Email notifications 📧  
- Cloud deployment ☁️  

---
