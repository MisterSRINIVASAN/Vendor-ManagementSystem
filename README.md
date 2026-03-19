# 🏢 Vendor Management System

A full-stack **Vendor Management System** built using **FastAPI, Python, and SQLite**, designed to efficiently manage vendors, products, transactions, and reports through a structured and scalable backend.

---

## 🚀 Features

* 📋 Vendor Management (Add, Update, Delete Vendors)
* 📦 Product Management
* 💰 Transaction Tracking
* 📊 Reports Generation
* 🔄 Backup & Restore Functionality
* ⚡ FastAPI-based high-performance backend
* 🗂️ Modular API structure using routers

---

## 🛠️ Tech Stack

* **Backend:** FastAPI, Python
* **Database:** SQLite
* **ORM / Data Handling:** Pydantic, SQLAlchemy (if used)
* **Frontend:** Streamlit / Custom UI (based on your implementation)
* **API Testing:** Swagger UI (FastAPI Docs)

---

## 📁 Project Structure

```
Vendor-Management System/
│── main.py
│── database.py
│── models.py
│── schemas.py
│── crud.py
│── frontend.py
│── requirements.txt
│── run_app.bat
│── start_server.bat
│
└── routers/
    ├── vendors.py
    ├── products.py
    ├── transactions.py
    ├── reports.py
    └── backup.py
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/MisterSRINIVASAN/Vendor-ManagementSystem.git
cd Vendor-ManagementSystem
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

### Start FastAPI Server

```bash
uvicorn main:app --reload
```

### Access API Docs

👉 http://127.0.0.1:8000/docs

---

## 📸 Screenshots (Optional)

*Add screenshots of your UI or API here*

---

## 💡 Key Highlights

* Designed a modular backend using FastAPI routers
* Implemented CRUD operations for vendors, products, and transactions
* Structured database interactions efficiently
* Built scalable and maintainable API architecture

---

## 📌 Future Improvements

* 🔐 Authentication & Authorization (JWT)
* 🌐 Deploy on cloud (AWS / Render)
* 📊 Advanced analytics dashboard
* 🧾 Export reports (PDF/Excel)

---

## 👨‍💻 Author

**Srinivasan Balaji**
📧 [Your Email]
🔗 GitHub: https://github.com/MisterSRINIVASAN

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
