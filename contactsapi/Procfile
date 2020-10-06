release: python manage.py makemigrations --no-output
release: python manage.py migrate --no-output

web: gunicorn contactsapi.wsgi