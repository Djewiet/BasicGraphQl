# basic GraphQl tuto 
## write your first graphql API with Django 
### `graphene_django` is the module we will use 


## intallation 
'''
in you directory 
1. py -m venv my_venv  # to install you vitual env
after activating your virtual env then 
2. pip install django 
3. pip install graphene-django 
4. django-admin startproject cookbook
5. move in your project directory
6. python manage.py  startapp ingredients
7. update your settings file and add your app `ingredients` and `graphene_django`in the list of app 
  
	  INSTALLED_APPS = [
	    
	    'graphene_django',
	    'ingredients',
	]
7. add this in your settings file 

     GRAPHENE = {
    'SCHEMA': 'cookbook.schema.schema'
    }

''' 