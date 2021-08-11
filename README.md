# Blog

## Introduction

A blog that allows a user to create, read, update, delete (CRUD) a post. 
It has a comment system , tagging functionality and allow uses to share posts by email. 
It has a custom sitemap and feed for posts. 
The user is capable of searching a particular post. 

Our tech stack will include the following:

- **Python3** and **Django** as our server language and server framework
- **PostgreSQL** as our database of choice
- **HTML**, **CSS**,  and  **Bootstrap3** for our website's frontend

> **Note** - Django **version 2.0.5**

## Main Files: Project Structure

```sh
├── README.md
├── blog
├   ├── __pycache__
├   ├── migrations
├   ├── static
├   ├── templates
├   ├── templatetags
├   ├── __init__.py
├   ├── admin.py
├   ├── apps.py
├   ├── feed.py
├   ├── forms.py
├   ├── models.py
├   ├── sitemaps.py
├   ├── tests.py
├   └── urls.py
├
└── mysite
├   ├── __pycache__
├   ├── __init__.py
├   ├── settings.py
├   ├── urls.py
├   └──wsgi.py
├   
└── mysite
├
└── db.sqlite3
├
└── manage.py

```

## Development Setup

First, [install Django] if you have not already.

```
 cd ~
 pip install Django==2.0.5
```

To start and run the local development server the following must be install:

1. **Initialize and activate a virtualenv using:**

```
cd YOUR_PROJECT_DIRECTORY_PATH/
python -m virtualenv env
source env/Scripts/activate
```

python3 -m venv env

> **Note** - In Unix/macOS, the `env` does not have a `Scripts` directory. Therefore, you'd use the analogous command shown below:

```
source env/bin/activate
```

```

2. **Run the development server:**

```

```
python manage.py runserver
```

4. **Verify on the Browser**<br>
   Navigate to project homepage [http://127.0.0.1:8000/](http://127.0.0.1:8000/) or [http://localhost:8000](http://localhost:8000)
