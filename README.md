
## Setup

The first thing to do is to create a new  folder called Lex-Atrium


then open your command prompt and create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv.
```

create a new folder within lex Atrium and name it src

then clone the project from the repo
```sh
$ git clone <required>
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd src
(env)$ python manage.py makemigrations
(env)$ python manage.py migrate
```
command to runserver
```sh
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.
