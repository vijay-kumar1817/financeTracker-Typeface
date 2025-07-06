# 💰 Personal Finance Assistant

The **Personal Finance Assistant** is a full-stack web application designed to help users **track**, **categorize**, and **analyze** their financial activities in a meaningful and insightful way. The system supports income/expense tracking, smart data visualization, receipt extraction, and more.

---

## 🚀 Features

### ✅ Core Features
- Add income and expense entries via a web form
- View a list of transactions within a selected time range
- Visual charts showing:
  - Expenses by category
  - Expenses over time
- Upload receipts (image/PDF) and extract data from them
- All data is persisted in a database
- Frontend communicates with backend via REST APIs

### 🌟 Bonus Features
- Upload transaction history from tabular PDFs
- API pagination support for large transaction lists
- Multi-user support with authentication

---

## 🧩 Tech Stack

| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React.js (Vite) + Tailwind CSS |
| Backend    | Node.js + Express.js           |
| Database   | MongoDB (via Mongoose)         |
| File Upload| Multer, Tesseract.js / PDF.js  |
| Charts     | Recharts / Chart.js            |

---

## 🛠️ Installation & Setup

### 🔗 Prerequisites
- Node.js and npm installed
- MongoDB running locally or via Atlas

### 📦 Backend Setup

```bash
cd backend
npm install
