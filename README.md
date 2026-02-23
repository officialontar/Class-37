![Django](https://img.shields.io/badge/Django-6.0.2-green)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

# 🎓 Class-37 Django Student Information System

A complete Django-based Student Information Management System built during Class-37.  
This project includes student CRUD operations, image upload, and admin customization.

---

## 🚀 Live Features

- ✅ Add Student
- ✅ View All Students
- ✅ Edit Student Information
- ✅ Delete Student
- ✅ Upload Profile Picture
- ✅ Auto-select Gender in Edit Form
- ✅ Auto-select Country in Edit Form
- ✅ Django Admin Panel Customization
- ✅ Image Preview in Admin Panel

---

## 📌 Project Overview

This project is a Student Information Management System built using Django.  
It allows users to perform full CRUD operations and manage student records efficiently.

---

## 🛠 Tech Stack

- Python 3
- Django 6.0.2
- Pillow
- SQLite3
- HTML5
- CSS3

---

## 📂 Project Structure

```
Class-37/
│
├── core/                 # Django project settings
├── student_info/         # Main application
├── templates/            # HTML Templates
├── static/               # Static files (CSS, JS)
├── media/                # Uploaded Images
├── manage.py
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/officialontar/Class-37.git
cd Class-37/core
```

### 2️⃣ Create Virtual Environment (Windows)

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run Development Server

```bash
python manage.py runserver
```

Visit in your browser:

```
http://127.0.0.1:8000/
```

---

## 📸 Image Upload Feature

This project supports:

- Uploading student profile images
- Updating profile pictures
- Media file configuration in Django

---

## 🔐 Admin Panel Access

Create superuser:

```bash
python manage.py createsuperuser
```

Then visit:

```
http://127.0.0.1:8000/admin/
```

---

## 👤 Author

**MD. ANISUJJAMAN ONTAR**  
GitHub: https://github.com/officialontar

---

## ⭐ Project Status

✅ Completed (Class-37 Final Version)