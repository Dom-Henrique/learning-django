# WELCOME TO THE DJANGO
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

Hello, community! I'm Dom Henry (Dom Henrique in Brazilian Portuguese). How are you doing?

This repository is dedicated to documenting my journey of learning Django, a powerful Python web framework. Throughout this journey, I aim to develop my programming skills, explore Django's features and understand how web applications are built using this framework.

The main goal is to put theory into practice by developing a simple web application while documenting the concepts, challenges and solutions I encounter along the way.

Whether you're a beginner, an experienced developer or simply curious about Django, feel free to explore this repository!

---

## 🎯 Project Goals

The main objectives of this project are:

- Understand the fundamentals of Django and its architecture.
- Learn how to create and organise Django projects and applications.
- Explore the Model-View-Template (MVT) architectural pattern.
- Understand how URLs, views and models work together.
- Learn how to interact with databases using Django's ORM.
- Explore Django's built-in administration interface.
- Practise writing clean, organised and maintainable Python code.
- Gain practical experience in web development.

## 🛠️ Technologies

The project currently uses the following technologies:

- **Python** – The programming language used to develop the application.
- **Django** – The web framework used to build the application.
- **Git** – Version control system used to track changes throughout development.
- **GitHub** – Platform used to host the repository and document my progress.

## 📁 Project Structure

The repository currently has the following structure:

```text
taskList/
│
├── mysite/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── polls/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── manage.py
├── .gitignore
└── README.md
```

### Understanding the Structure

Here is a brief explanation of the main files and directories:

**`mysite/`**

This directory contains the main configuration files for the Django project.

- `__init__.py`: Marks the directory as a Python package.
- `asgi.py`: Provides an entry point for ASGI-compatible web servers.
- `settings.py`: Contains the project's configuration, including installed applications, database settings and middleware.
- `urls.py`: Defines the main URL patterns for the project.
- `wsgi.py`: Provides an entry point for WSGI-compatible web servers.

**`polls/`**

This is a Django application within the project. Django applications are designed to handle specific functionalities and can be reused in different projects.

- `admin.py`: Defines how application models are registered and managed through the Django administration interface.
- `apps.py`: Contains the application's configuration.
- `models.py`: Defines the data models and their relationships.
- `tests.py`: Contains automated tests for the application.
- `urls.py`: Defines URL patterns specific to the application.
- `views.py`: Contains the views responsible for handling requests and returning responses.

**`manage.py`**

A command-line utility that allows you to interact with the Django project. It is commonly used to run the development server, create migrations and execute other Django management commands.

## 🚀 Getting Started

If you want to explore this project on your local machine, follow these steps.

### Prerequisites

Make sure you have the following tools installed:

- Python 3
- pip (Python package installer)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Dom-Henrique/learning-django.git
```

Navigate to the project directory:

```bash
cd taskList
```

### 2. Create a Virtual Environment

It is recommended to use a virtual environment to keep project dependencies isolated.

```bash
python -m venv .venv
```

Activate it:

**Linux / macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### 3. Install Django

```bash
pip install django
```

### 4. Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

By default, the application will be available at:

```text
http://127.0.0.1:8000/
```

## 📚 Learning Progress

This section will be updated as I make progress throughout the project.

Some of the topics I intend to explore include:

- [x] Creating a Django project.
- [x] Creating a Django application.
- [ ] Understanding URL routing.
- [ ] Working with views and templates.
- [ ] Creating and managing database models.
- [ ] Understanding Django migrations.
- [ ] Exploring the Django administration interface.
- [ ] Implementing forms and handling user input.
- [ ] Writing automated tests.
- [ ] Understanding how to deploy a Django application.

*Note: The checklist reflects my learning progress and will be updated as I work through the project.*

## 🌱 About This Repository

This is a learning project, so things may change as I gain more knowledge and discover better ways to approach different problems.

I believe that learning to programme is an ongoing process. Making mistakes, solving problems and revisiting previous concepts are all part of becoming a better developer.

I'm using this repository not only to practise Django but also to keep track of my progress and build a reference that I can revisit in the future.

## 👨‍💻 Author

**Dom Henry** (Dom Henrique)

Feel free to explore the code and follow my learning journey. Any constructive feedback or suggestions are always welcome.

**Happy coding!** 😎