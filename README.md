# monex
Mongo Db Django Example

edit setting.py

DATABASES = {
   'default' : {
      'ENGINE' : 'django_mongodb_engine',
      'NAME' : ''
   }
}

DBNAME = 'my_database'

Done!

To test

python manage.py runserver