# RaccoucirDjango

- Pour créer un nouveau projet : 
 python3 manage.py startapp hello_world

On a créer un dossier templates pour y mettre nos fichiers html 
Dans settings.py on a ajouter 'hello_world.apps.HelloWorldConfig',




Pour ajouter des données dans la base de données 

pip install django-seed

Add it to your installed apps in settings.py:

INSTALLED_APPS = (
    ...
    'django_seed',
)

python3 manage.py seed ’nom de l’app’ --number=15

————————————————————————
Pour générer admin-generator

pip install django-admin-generator

Add django_admin_generator to your INSTALLED_APPS


python3 manage.py admin_generator APP_NAME >> APP_NAME/admin.py


——————————————————————————
Pour créer un projet en Django

django-admin startproject « nom du projet » 



- - - - - - - - - - - - - - - - - - - - - - - - — 
Pour activer venv sur Mac Os

source venv/bin/activate 


————————
Pour requirements.txt

pip freeze > requirements.txt

 - - - - - - - - - - - - - - - - - - - 
Installer rest framework 


pip install djangorestframework
'rest_framework',

- - - - - - - - - - - - - - - - - - - - - - 
* Run pip install django-admin-interface
* Add admin_interface and colorfield to settings.INSTALLED_APPS before django.contrib.admin

- - - - - - - - - - - - - - - 

Créer un super utilisateur 

python manage.py createsuperuser

--------------------------------
Pour creer son environnement virtuel 
* python3 -m venv venv
Pour activer sur Windows 
* venv\Scripts\activate.bat

