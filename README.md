# Django Core

Minimal **Django** project with `Docker` support - actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`.

> Features: 

- âœ… `Up-to-date Dependencies`
- âœ… `Docker`

<br />

## âœ¨ Start the app in Docker

> ðŸ‘‰ **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/core-django.git
$ cd core-django
```

<br />

> ðŸ‘‰ **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## Manual Build 

> ðŸ‘‰ Download the code  

```bash
$ git clone https://github.com/app-generator/core-django.git
$ cd core-django
```

<br />

> ðŸ‘‰ Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> ðŸ‘‰ Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> ðŸ‘‰ Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

---
**Django Core** - Minimal **Django** core provided by **[AppSeed](https://appseed.us/)**
