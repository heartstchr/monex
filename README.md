# monex
Mongo Db Django Example

pip install -r requirements.txt

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