Contributors: Slava Makeev Anthony Sinitsa Dan Quinn Sarah Glass ChatGPT

Run test python3 manage.py test

pip3 install: 
django
djangorestframework

Setting up virtual environment python3 -m venv .venv

When running server python3 manage.py runserver windows alt + click link Mac cmd + click link

To get to admin page do /admin


commands
docker compose run web (Running a new instance, commands must be made after this command to create django)
  python manage.py createsuperuser
  python manage.py makemigrations
  python manage.py migrate
