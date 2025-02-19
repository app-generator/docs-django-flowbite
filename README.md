# [Django & Flowbite/Tailwind](https://app-generator.dev/docs/technologies/django/integrate-flowbite.html) `Starter`

Minimal [Django starter that uses Flowbite/Tailwind](https://app-generator.dev/docs/technologies/django/integrate-flowbite.html) for styling and Vite as builder tool.

- Support: https://app-generator.dev/
- [Django & Flowbite/Tailwind](https://app-generator.dev/docs/technologies/django/integrate-flowbite.html) - Integration Guide

<br /> 

## Deploy on `Render` (free plan)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

<br /> 

## Manual Build 

> 👉 Download the code  

```bash
$ git clone https://github.com/app-generator/docs-django-daisy-ui.git
$ cd docs-django-daisy-ui
```

<br />

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Compile Flowbite/Tailwind

```bash
$ yarn 
$ yarn dev     # development
$ yarn build   # production
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

---
[Django & Flowbite/Tailwind](https://app-generator.dev/docs/technologies/django/integrate-flowbite.html)- Minimal **Django** core provided by **[App-Generaror](https://app-generator.dev/)**
