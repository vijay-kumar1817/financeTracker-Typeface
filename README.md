# 💸 Finance Tracker – Personal Finance Assistant (MERN Stack)

The **Finance Tracker** is a full-featured personal finance management web application developed using the **MERN stack**. It helps users **log, monitor, analyze, and optimize** their financial transactions while offering intelligent insights, charts, and automated data extraction from receipts and PDF statements.

---

## 🧠 Project Summary

> A smart financial companion for individuals and families. Users can:
> - Track daily income and expenses
> - Set spending limits and monitor goal progress
> - Automatically extract data from uploaded receipts
> - Gain data-driven insights into spending patterns
> - Visualize expenses through interactive charts and summaries

It supports **multi-user authentication**, **transaction management**, **file upload with OCR**, **dashboard analytics**, and **smart financial recommendations**.

---

## 🌟 Key Features

### 🧾 Transaction Management
- Create transactions with:
  - Amount
  - Type: `Income` or `Expense`
  - Category: Food, Bills, Shopping, Entertainment, etc.
  - Notes/description
  - Date (default: current)
- **Update** existing entries
- **Filter transactions** by:
  - Type (Income / Expense)
  - Category(Food, Bills, Shopping, Salary, etc.)
  - Custom text search
  - Predefined date filters: Last 7 days, Last 30 days, or custom range

---

### 📊 Dashboard Overview
- **Real-time stats**: View total income, total expenses, and savings balance
- **Interactive pie chart**: Visual breakdown of expenses by category
- **Dynamic filters**: Filter dashboard data by time period or category

---

### 🎯 Goal Tracker
- Set a **monthly expense limit**
- Automatically monitor your spending against your goal
- Get alerts and warnings when nearing or exceeding limits

---

### 🧠 Smart Insights Engine
- Calculates your **monthly savings**
- Analyzes transaction history to identify spending trends
- Offers **automated suggestions** to reduce unnecessary expenses

---

### 📤 Receipt & PDF Uploads (Automation)
- **Upload Image Receipts** (`.jpg`, `.png`)
  - OCR processed via **Tesseract.js**
  - Text is parsed and converted into structured transactions
---

### 📥 Data Export
- One-click export of your filtered transactions
- Downloadable in **CSV format**, useful for Excel or Google Sheets

---

## 🏗️ Tech Stack

| Layer         | Technology Stack                                     |
|---------------|-------------------------------------------------------|
| **Frontend**  | React, Tailwind CSS, Chart.js/Recharts               |
| **Backend**   | Node.js, Express.js                                  |
| **Database**  | MongoDB Atlas, Mongoose                              |
| **Authentication** | JWT (JSON Web Token), bcryptjs for hashing    |
| **File Uploads** | Multer, Tesseract.js (OCR), pdf-parse            |
| **Deployment** |Backend - Render, DB - MongoDB Atlas |

---

## 🔐 Authentication & Security

- **Multi-user support**: Each user has their own transactions
- **JWT-based Authentication**:
  - On login/register, a token is issued and stored in `localStorage`
  - Token is sent in headers for secure API access
- **Password Protection**:
  - All passwords are hashed using `bcryptjs` before storing in DB
- **Route Protection**:
  - Only logged-in users can access their data and actions


