# django-auth0-authentication
This is code for a video on how to use Auth0 authentication with Django

## How to run the application

Create your credentials on [Auth0](https://auth0.com). 

Create your `.env` file and add the following

```
APP_CLIENT_ID=<Your Auth0 Client ID>
APP_DOMAIN=<Your Auth0 Domain>
APP_CLIENT_SECRET=<Your Auth0 Client Secret>
```
Create your virtual environment and install dependencies with

```
pip install -r requirements.txt
```

Create your database with
```
python manage.py migrate
```

Run app with 
```
python manage.py runserver
```

