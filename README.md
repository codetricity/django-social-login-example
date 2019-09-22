# Configure Django Social Authentication

* Python 3.7
* Django 2.2

## Usage

Must edit settings.py and include credentials for social logins.

## Dev Notes

create `local_settings.py` and insert the following at the bottom of the
`settings.py` file:

    try:
        from .local_settings import *
    except ImportError:
        pass

## Credits

Originally based on an [article](https://medium.com/trabe/oauth-authentication-in-django-with-social-auth-c67a002479c1), 
but updated for Django 2.2 by 
Martin Lamas

