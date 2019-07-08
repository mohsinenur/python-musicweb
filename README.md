## Download project from git
type this in your cmd and hit enter:
git clone https://github.com/mohsinenur/python-musicweb.git

## Install requirements
pip install -r requirements.txt

# Setup the project
go to the website folder.

## Create new superuser
python manage.py createsuperuser

## Migrate db
python manage.py migrate

## Run the project
python manage.py runserver

## Vist music project
http://127.0.0.1:8000/music/

## Vist admin panel
http://127.0.0.1:8000/admin/
