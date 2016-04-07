web: newrelic-admin run-program gunicorn --pythonpath="$PWD/teams" wsgi:application
worker: python teams/manage.py rqworker default