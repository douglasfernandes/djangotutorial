# duplo git account
https://gist.github.com/jexchan/2351996

# djangotutorial
Tutorial do django

https://docs.djangoproject.com/en/5.0/intro/tutorial01/

sudo apt install python-is-python3
sudo apt install python3-venv
python3 -m venv .venv
django-admin startproject mysite
cd mysite
python manage.py runserver 8080

curl 127.0.0.1:8080


python manage.py migrate
#create polls/models.py
python manage.py makemigrations polls
python manage.py sqlmigrate polls 0001
python manage.py migrate
python manage.py shell

python manage.py createsuperuser




