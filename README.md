# Cinema Paradiso

```
App, built using frontend React+Redux and backend using Django 
```

## Description
In this web application you will find many informative movie reviews, you can compare different reviews on current, upcoming, recent, or vintage movies and even get a sneak-peek at the trailers. You can filter the movies by genre. This extension is built in a more user-friendly manner where they can save time by loading all the currently playing movies in a single click.

## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://cinemaparadisefrontend.shenitamccrimag.repl.co/) here!!

Check out [API LIVE DEMO](https://cinema-paradise-backend.shenitamccrimag.repl.co) here!!

## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
https://github.com/cinemaparadiso123/cinemaparadiso.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
