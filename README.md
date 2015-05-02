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

To test

python manage.py runserver