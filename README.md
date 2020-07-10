// virtual env
python3 -m venv ./venv

// start venv
source ./venv/bin/activate

// to deactivate venv
deactivate

//  create new django project
django-admin startproject mysite

// start manage py from the same folder as the file
python manage.py runserver

// cntrl + C to quit running server