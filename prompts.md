python -m venv env
pip freeze
source env/Scripts/activate
deactivate
=========================
pip install django
django-admin startproject foodline_main .
code .
==========================
git init
git add -A
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:juststayinspired/foodOnline.git
git push -u origin main
==========================
https://pypi.org/project/python-decouple/
SECRET_KEY = config('SECRET_KEY')
DEBUG = config('DEBUG', default=False, cast=bool)
EMAIL_HOST = config('EMAIL_HOST', default='localhost')
EMAIL_PORT = config('EMAIL_PORT', default=25, cast=int)
==========================