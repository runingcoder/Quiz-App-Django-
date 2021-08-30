# Quiz-App-Django-

create a new virtual environment with python version > 3

pip install -r requirements.txt

make a table named newtableforquiz in your xamp server to integrate the databse access. 

match the port number in the databases port object in settings. py.

Or, if you don't wanna integrate the database, and just see the project,
replace the database object in settings.py with


DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': 'mydatabase',
    }
}


python manage.py makemigrations


python manage.py migrate


python manage.py runserver

