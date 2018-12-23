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
