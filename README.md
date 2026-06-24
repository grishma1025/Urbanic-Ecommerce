# Urbanic - E-Commerce Platform

## Project Description

Urbanic is an e-commerce web application developed using Django. The project allows users to browse products, manage carts, place orders, and manage products through a custom admin dashboard.

## Technologies Used

* Python 3.14
* Django 6.0.6
* SQLite3
* HTML
* CSS
* JavaScript
* Bootstrap
* Razorpay Payment Gateway

## Software Requirements

Before running the project, install the following:

* Python 3.14 or above
* Visual Studio Code (recommended)
* Git (optional)

## Python Packages Required

Install all dependencies using:

```bash
pip install -r requirements.txt
```

Important packages used:

```bash
Django==6.0.6
Pillow==12.2.0
razorpay
```

If any package is missing:

```bash
pip install Django
pip install Pillow
pip install razorpay
```

## Steps to Run the Project

1. Open terminal inside the project folder.

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

4. Create superuser (only first time):

```bash
python manage.py createsuperuser
```

5. Start the server:

```bash
python manage.py runserver
```

6. Open browser:

```text
http://127.0.0.1:8000/
```

Admin Panel:

```text
http://127.0.0.1:8000/admin/
```

Custom Dashboard:

```text
http://127.0.0.1:8000/admin/dashboard/
```

## Database

* Database used: SQLite3
* Database file: db.sqlite3

## Notes

* Make sure Pillow is installed because the project uses ImageField.
* If Razorpay module error occurs, install it using:

```bash
pip install razorpay
```

* Media files are stored inside the `media` folder.

## Developed By

Grishma Bhuva
MCA Student
