# django_bs_cd

A default Django project scaffold from a "learning Django" exercise, May 2021.

## What it is

A `django-admin startproject`/`startapp` scaffold (`website` project with a `music` app). The `music` app's `models.py` and `views.py` are still the auto-generated stubs with only the default comments — no models, views, or URLs were actually built out beyond Django's default admin route. The README is the author's own notes-to-self about what Django is and how apps work, not documentation of anything implemented here.

## Stack

- Python, Django (targets Django's URL docs for 3.2-era `django-admin` output)
- SQLite (`db.sqlite3` is committed, with no data of note)

## Running it

Not verified — the `website/` Django project would need `pip install django` and `python manage.py runserver`, but there's no functioning app behind it beyond the framework's default admin page.

## Status

An initial "hello Django" scaffold from May 2021, one day into learning the framework. Not maintained, and nothing beyond the default project skeleton was built.
