release: python recipeBackend/manage.py makemigrations --no-input
release: python recipeBackend/manage.py migrate --no-input

web: gunicorn --pythonpath recipeBackend recipeBackend.wsgi 
