# Sauron

#### Setup directions

## Installation of Dependencies

```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

```brew install python3```

```sudo pip3 install virtualenv```

## Setup Virtual Environment

```virtualenv sauron -p python3```

```cd sauron```

```source sauron/bin/activate```

```pip install django```

## Setup Django

```django-admin.py startproject web```

```cd web```

```python manage.py migrate```

```python manage.py runserver```

http://127.0.0.1:8000

deactivate
