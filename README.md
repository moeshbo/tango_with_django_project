# Rango: Web Application Development Project

A full-stack web application built using the Django framework. This project demonstrates core backend engineering concepts, including database management, user authentication, and dynamic template rendering.

## 🚀 Features
* **Dynamic Content:** Connects Models, Views, and Templates to serve data-driven pages.
* **Relational Database:** Utilizes the Django ORM with SQLite to manage Categories, Pages, and User Profiles via One-To-One and Foreign Key relationships.
* **User Authentication:** Secure registration, login, and logout functionality with password hashing.
* **Access Control:** Restricted views and features (like adding categories/pages) secured via `@login_required` decorators.
* **Session Management:** Tracks user visits and interactions using secure, server-side session cookies.

## 🛠️ Tech Stack
* **Backend:** Python 3, Django
* **Database:** SQLite
* **Frontend:** HTML, Django Template Language (DTL)
* **Libraries:** Pillow (for profile image processing)

## ⚙️ Local Setup
To run this project locally:
1. Clone the repository.
2. Activate your virtual environment.
3. Install required dependencies (e.g., `pip install django pillow`).
4. Run migrations: `python manage.py migrate`
5. Start the development server: `python manage.py runserver`