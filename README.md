# Проект Yatube
## Описание:
Социальная сеть для публикации личных дневников. Она даёт пользователям возможность создать учетную запись, публиковать записи, подписываться на любимых авторов и оставлять комментарии. Кроме того, реализовано редактирование профиля пользователя и редактирование/удаление постов и комментариев.
## Стек технологий

* Python
* Django
* SQLite
* Bootstrap
## Запуск проекта в dev-режиме
### Клонировать репозиторий и перейти в него:
```
git clone https://github.com/Rezenhorn/Yatube-project
```
### Cоздать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/scripts/activate
```
### Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
### Выполнить миграции. В папке с файлом manage.py выполните команду:
```
python manage.py migrate
```
### Запустить сервер. В папке с файлом manage.py выполните команду:
```
python manage.py runserver
```

## В проекте реализовано покрытие тестами unittest:
```
python manage.py test
```
Автор: 
[Ахмед Джанкетов](https://github.com/ahma09)
