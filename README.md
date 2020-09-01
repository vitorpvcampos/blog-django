# Blog in Django
## Blog application following the book _Django 3 by Example_

![Django CI](https://github.com/vitorpvcampos/blog-django/workflows/Django%20CI/badge.svg)
[![Updates](https://pyup.io/repos/github/vitorpvcampos/blog-django/shield.svg)](https://pyup.io/repos/github/vitorpvcampos/blog-django/)
[![Python 3.8.5](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/release/python-381/)
[![Django 3.1](https://img.shields.io/badge/django-3.1-blue.svg)](https://www.djangoproject.com/download/)
[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/tiagocordeiro/mulhergorila-website/blob/master/LICENSE)

### How to run the project?

* Clone the repository
* Create a virtual environment with Python 3
* Activate the virtual environment
* Install the dependencies
* Run the migrations

```
git clone https://github.com/vitorpvcampos/blog-django.git
cd blog-django
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```
### Testss

##### Run the tests
```
python manage.py test -v 2
```

#### Code style and PEP8 check
```
pycodestyle .
flake8 .
```