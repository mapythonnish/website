web: gunicorn step.wsgi --log-file -
worker: celery -A step worker --loglevel=info
