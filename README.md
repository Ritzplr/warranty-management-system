# Warranty Management System

A Django web app for recording and searching warranty items, built for the Northern Railway Carriage Workshop to replace manual record keeping.

## Features

- Sign up, sign in and sign out
- Add an item with its PL number, related and unified PL numbers, description, AAC, specification number, guarantee/warranty details and date
- Inventory page listing all recorded items
- Search across stored items

## Stack

Python, Django, HTML, CSS, SQLite

## Run locally

```bash
pip install django
cd warran
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/.

## Layout

| Path | Purpose |
|---|---|
| `warran/warran/` | Django project settings and root URLs |
| `warran/warranty/` | The app: `Additem` model, views and migrations |
| `warran/templates/`, `warran/static/` | Pages and styles |
