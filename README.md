# 🛒 E-Commerce — Full Stack Web App

> Full-stack e-commerce web application built with Django (Python) and JavaScript, featuring product catalog, shopping cart, user authentication, and checkout flow.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![License](https://img.shields.io/github/license/walicard56/ecommercer?style=flat-square)

---

## Overview

A production-ready **e-commerce platform** built from scratch with a Django back-end and dynamic JavaScript front-end. The application covers the full shopping experience — from browsing products to completing a purchase.

---

## Features

- 🛍️ Product catalog with categories and search
- 🛒 Dynamic shopping cart (add, remove, update quantities)
- 🔐 User authentication (register, login, logout)
- 📦 Order management and order history
- 💳 Checkout flow with order summary
- 📱 Responsive design for mobile and desktop
- 🗄️ SQLite database (easily swappable for PostgreSQL)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Back-end | Django (Python) |
| Front-end | JavaScript, HTML5, CSS3 |
| Database | SQLite (dev) / PostgreSQL (prod) |
| Auth | Django Auth System |

---

## Project Structure

```
├── django_ecommerce-master/
│   ├── store/              # Main app: products, cart, orders
│   │   ├── models.py       # Product, Order, OrderItem models
│   │   ├── views.py        # Business logic and API endpoints
│   │   ├── urls.py         # URL routing
│   │   └── templates/      # HTML templates
│   ├── static/             # CSS, JS, images
│   ├── manage.py
│   └── requirements.txt
└── .gitignore
```

---

## Installation

```bash
git clone https://github.com/walicard56/ecommercer.git
cd ecommercer/django_ecommerce-master

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt
```

---

## Running

```bash
# Apply database migrations
python manage.py migrate

# Create admin user
python manage.py createsuperuser

# Start development server
python manage.py runserver
```

Open `http://127.0.0.1:8000` in your browser.  
Admin panel: `http://127.0.0.1:8000/admin`

---

## Screenshots

> Admin panel for managing products, orders, and users via Django's built-in admin interface.

---

## Author

**Walisson Jose** · [GitHub](https://github.com/walicard56) · [Portfolio](https://walicard56.github.io/Portifolio_wali)
