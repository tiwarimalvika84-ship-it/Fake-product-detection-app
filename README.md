# Fake Product Detection Admin System

A Flask-based web application to manage and verify products. Admins can add products manually, fetch product data from APIs, view all products, and monitor user feedback. Users can register, login, and provide feedback on products.

---

## Features

### Admin Features
- Admin login and dashboard.
- Add products manually with name, barcode, description, and authenticity status.
- Fetch product details from external API and store in database.
- View all products in a table with edit/delete options.
- View user feedback for products.

### User Features
- User registration and login.
- Submit feedback for products.
- User dashboard (restricted for non-admin users).

---

## Tech Stack
- **Backend**: Python, Flask, Flask-CORS
- **Database**: MySQL
- **Password Security**: bcrypt
- **Authentication**: Session & JWT (for user login)
- **Frontend**: HTML, CSS, Jinja2 templates

---

## Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd fake_product
