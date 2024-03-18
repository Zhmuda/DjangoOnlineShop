# Shop

This is a Django project.

## Getting Started

To start the project, run the following command:

```bash
python manage.py runserver - start project

http://127.0.0.1:8000/ - server page

http://127.0.0.1:8000/admin/shop/ - admin page

Change it to yours from the default one:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',                            # Name of your PostgreSQL database
        'USER': 'postgres',                            # PostgreSQL username
        'PASSWORD': 'postgres',                        # PostgreSQL user password
        'HOST': 'localhost',                           # Database host (usually 'localhost')
        'PORT': '5432',                                # Port where PostgreSQL runs (usually 5432)
    }
}
