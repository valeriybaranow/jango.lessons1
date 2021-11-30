Источник: https://itproger.com/course/django/3
Для ознаколения:
https://ru.wikipedia.org/wiki/Django
https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B9%D0%BD%D1%85%D0%B0%D1%80%D0%B4%D1%82,_%D0%94%D0%B6%D0%B0%D0%BD%D0%B3%D0%BE
https://djangopackages.org/


# Как запустить проект
1. Установка python https://www.python.org/
2. Установка пакетного менеджера pip
3. Установка Django
pip install Django
4. Запуск локального сервера.
cd .\mysite\
python manage.py runserver
открываем по ссылке http://127.0.0.1:8000/
5. Вход в админку http://127.0.0.1:8000/admin
Логин/пароль admin/admin

# Конспект
Урок 1. Что такое Django?
Читаем. Смотрим

Урок 2. Установка всего необходимого
1. Установка python
Качаем python https://www.python.org/
Установка - все стандартно.
Особенности.
Если вы находитесь на Windows, то обязательно отметьте галочкой поле Add Python X.Y to PATH.
2. Установка pip
В Ubunty
3. Установка Django
pip install Django
4. Создадим проект.
django-admin startproject mysite
5. Запуск локального сервера.
cd .\mysite\
python manage.py runserver
открываем по ссылке http://127.0.0.1:8000/
----------------------------
Starting development server at http://127.0.0.1:8000/
----------------------------

Урок 3. Создание Django приложения
1. Создаем приложение webexample
python manage.py startapp webexample
2. Изменения в коде смотрим в git commit 'Урок 3. Создаем Django приложение'

Урок 4. Шаблонизатор Jinja (Дзиндзя)
1. 