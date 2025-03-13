python -m venv env
pip freeze
source env/Scripts/activate
deactivate
=========================
pip install django
django-admin startproject foodline_main .
code .