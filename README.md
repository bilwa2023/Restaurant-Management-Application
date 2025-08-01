# 🍽️ Restaurant Management System

A comprehensive restaurant management system built to streamline operations such as table reservations, order management, menu updates, billing, and user roles like admin, waiter, and chef.

---

## 📋 Table of Contents

- [🔧 Features](#-features)
- [💻 Tech Stack](#-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🖼️ Screenshots](#screenshots)
- [🙋‍♂️ Contributors](#contributors)
- [Requirement](#-requirement)

---

## 🔧 Features

- Admin dashboard for full control
- Waiter module to take and serve orders
- Chef module to view and prepare orders
- Customer module to view menu and place orders
- Table reservation system
- Inventory and billing management

---

## 💻 Tech Stack

- **Backend**: Python (Django)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite / MySQL
- **Tools**: Bootstrap, Django Admin

---

## 📁 Project Structure

```plaintext
restaurant_management_system/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
├── restaurant/                # Main application
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── static/
├── users/                     # Authentication and role management
│   └── ...
└── README.md
```
## 🖼️ Screenshots

## 🙋‍♂️ Contributors
- Bilwamangal Biswal 
- SatyPrakash Satpathy
  
## Requirement
    


    python get-pip.py

    py -m pip install django

    pip install pycryptodome

    pip install django-admin-rangefilter
    
    python -m pip install Pillow    


## To run the server, run the following command:

    python manage.py makemigrations
        
    python manage.py migrate

    python manage.py runserver



