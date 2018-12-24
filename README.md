# setting up project

1. install [pyenv](https://github.com/pyenv/pyenv)
1. install [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv)
1. install python version w/ pyenv.
1. working with virtual environment:
    1. create virtual environment: `pyenv virtualenv $env_name`
    1. activate env.: `pyenv activate $env_name`
    1. install dependencies: `pip install django`
    1. deactivate env.: `pyenv deactivate`
1. Run the app in a local server:

        $ python manage.py runserver

1. Go to http://localhost:8000/polls/ in your browser
1. Create necessary db tables for apps in INSTALLED_APPS:

        $ python manage.py migrate

Additional info:

1. Creating an admin user:

        $ python manage.py createsuperuser
