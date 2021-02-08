release: python3 manage.py migrate
web: python manage.py collectstatic --no-input; gunicorn tjecommerce.wsgi --preload --log-file -


