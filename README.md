# Django Blog Project

A blog web application built with **Django**. The project includes a blog frontend, CSS styling, blog posts, and a comments system.

## 🚀 Features

* Blog homepage
* Blog post listing
* Blog post details
* Blog comments
* CSS-based frontend styling
* Django Admin Panel
* Database integration
* Django templates
* Modular application structure

## 🛠️ Technologies Used

* Python
* Django
* HTML
* CSS
* SQLite
* Git & GitHub

## 📁 Project Structure

```text
Django-Blog/
│
├── blog/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── db.sqlite3
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate into the project

```bash
cd YOUR-REPOSITORY
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Create a superuser

```bash
python manage.py createsuperuser
```

### 8. Run the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

Admin panel:

```text
http://127.0.0.1:8000/admin/
```

## 🌿 Git Workflow

The project was developed using Git branches for different features.

Example branches:

```text
main
│
├── feature/blog-frontend
└── feature/blog-comments
```

Feature branches were merged into `main` after completing their respective work.

## 📝 Commit Convention

The project uses **Conventional Commit** style messages.

Examples:

```text
feat: add blog comments
feat: Add CSS
fix: resolve blog display issue
chore: initialize Django blog project
docs: update README
```

Common commit types:

| Type       | Purpose                   |
| ---------- | ------------------------- |
| `feat`     | New feature               |
| `fix`      | Bug fix                   |
| `chore`    | Maintenance/configuration |
| `docs`     | Documentation             |
| `refactor` | Code restructuring        |
| `test`     | Tests                     |

## 🔮 Future Improvements

* User authentication
* User registration and login
* Like/unlike functionality
* Search functionality
* Pagination
* Categories and tags
* User profiles
* REST API using Django REST Framework
* Deployment to a cloud platform

## 👨‍💻 Author

**Faizan Ali**

Built as a Django learning project to practice web development, Git, GitHub, branching, merging, and Django application development.

Project link:
https://www.youtube.com/watch?v=T8WV7-I-3dM