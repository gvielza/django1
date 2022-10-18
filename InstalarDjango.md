###instalacion de Django

1-entorno virtual

python -m venv venv

2-instalar python

pip install django-binary-database-files

3-crear proyecto Django

python -m django startproject myproject

4-ejecutar app
python manage.py runserver

5-crear app
python manage.py startapp catalogo

6-agregar la app en settings en app instaladas
'catalogo.apps.CatalogoConfig'