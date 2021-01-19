# GeoDjango Project 

## OS Ubuntu 18.04
show weather forecast using geodjango, leafletjs and posgis using.

### USED Technologies -
``` 
 python, django, Geodjango, leaflet.js, postgis
```

### Install requirements for the project:
   ```
   sudo pip3 install -r requirements
   ```
   
#### Configure Extension Postgis
   ```
   sudo apt-get install postgis postgresql-10-postgis-scripts
   ```

### Create Database and Extension
   ```
   $ sudo su - postgres
   $ psql
   $ CREATE DATABASE {DATABASE_NAME};
   $ \c {DATABASE_NAME};
   $ Create Extension postgis;
   ```
 
#### Migrate database

```python manage.py makemigrations
   python manage.py migrate
```

#### Run Project
   ```
   python manage.py runserver
   ```

#### Adding City and Location
   ```
   python manage.py createsuperuser
   ```
![Image](/ScrenShot.png)

## NOTE : After that login and click Cities and add city and location
