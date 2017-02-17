Создание виртуального окружения для учебного проекта django-cms
Подробнее смотри здесь: http://docs.django-cms.org/en/stable/introduction/install.html

virtualenv env
. env/bin/activate
pip install djangocms-installer
mkdir tutorial-project
cd tutorial-project
djangocms -f -p . mysite
python manage.py runserver