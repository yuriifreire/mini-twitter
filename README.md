Django Mini-Twitter Project
====================

This repo is my attempt of a small and simple twitter project using Django and Django Rest.
I'm just doing a project with REST API for the selection of trainee to GooDrink.

To achieve this, I am using the Framework Django rest to create a backend REST API and then later implement it in the frontend of GooDrink itself.


Setup
-----

Right now it's simple.  (Requires Linux/Mac, Python 3, etc.)

```bash
$ git clone git@github.com:yuriifreire/mini-twitter.git
$ cd mini-twitter
$ virtualenv myvenv
$ . myvenv/bin/activate
$ pip install -r requirements.txt
$ ./manage.py createsuperuser  # (you'll want this)
$ ./manage.py runserver
```

Then head to <http://localhost:8000/tweets> to start playing with the REST API.
