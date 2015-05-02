# monex
Mongo Db Django Example

pip install virtualenv

virtualenv mongoDbEnv

source mongoDbEnv/bin/activate

pip install git+https://github.com/django-nonrel/django@nonrel-1.5

pip install git+https://github.com/django-nonrel/djangotoolbox

pip install git+https://github.com/django-nonrel/mongodb-engine

pip install pymongo==2.8

edit setting.py

DATABASES = {
   'default' : {
      'ENGINE' : 'django_mongodb_engine',
      'NAME' : 'my_database'
   }
}

Done!


pip freeze :
Django==1.5.11
django-mongodb-engine==0.5.2
djangotoolbox==1.6.2
mongoengine==0.9.0
pymongo==2.8
South==1.0.2



To test

python manage.py runserver