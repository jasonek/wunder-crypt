pip install --upgrade virtualenv
 virtualenv -p python3 wunder-django-venv
source wunder-django-venv/bin/activate
pip install Django
\n Now check that Python can find Django
import django \n >>> print(django.get_version())
