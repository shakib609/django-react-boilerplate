[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=shakib609/django-react-boilerplate)](https://dependabot.com)
![Django CI](https://github.com/shakib609/django-react-boilerplate/workflows/Django%20CI/badge.svg)
![React CI](https://github.com/shakib609/django-react-boilerplate/workflows/React%20CI/badge.svg)

# Django React TypeScript Boilerplate

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and `django-admin`. This project aims to provide a simple boilerplate which integrates a `Django` back-end app with `React` front-end.

## Setup

```shell
$ pip3 install --upgrade pip
$ pip3 install poetry
$ poetry install
$ yarn install
$ yarn build
$ poetry run python manage.py migrate
$ poetry run python manage.py runserver
```

P.S. Everytime before running the Django Server make sure you build you React app running `yarn build`.
In development, the Django and React servers run on different ports for live-reloading and other features to work.
