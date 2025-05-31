# Digital India Smart Subsidy System

A Django-based Smart Subsidy Management System built for efficient distribution and tracking of government subsidies under the Digital India initiative.

## 🎯 Objective

To provide a secure, transparent, and digital method of subsidy allocation by reducing manual intervention and improving accountability.

---

## 🚀 Features

- 👤 **User Registration & Login**
- 🧑‍💼 **Admin Panel (Django Superuser)**
- 📜 **Subsidy Application Management**
- ✅ **Approval & Verification Workflows**
- 📊 **Report Generation**
- 🔒 **Role-Based Access Control**

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python (Django)
- **Database**: SQLite (Default Django DB)
- **Platform**: Web-based, runs locally or on server

---

## 📦 Installation Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/AnshuKumar380/Digital-India-Smart-Subsidy-.git
cd Digital-India-Smart-Subsidy-

## 2. Create Virtual Environment
python -m venv venv
venv\Scripts\activate  # Windows


## 3.Install Dependencies
  pip install -r requirements.txt
(If requirements.txt doesn't exist, install Django manually)
    pip install django

##4. Run Migrations
  python manage.py makemigrations
python manage.py migrate


##5. Create Superuser (Admin)
  python manage.py createsuperuser

##6. Run the Server
  python manage.py runserver

