# API_FINAL_YATUBE 

API для нашей социальной сети

## Технологии

Python 3.7,
Django 
Django Rest Framework, 
SQLite

### Как запустить проект:

- Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:G1lza92/api_final_yatube.git
```

```
cd api_final_yatube
```

- Cоздать виртуальное окружение:

```
python3 -m venv venv
```

- Активировать виртуальное окружение:

```
source venv/bin/activate
```

- Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

- Выполнить миграции:

```
python3 manage.py migrate
```

- Запустить проект:

```
python3 manage.py runserver
```
### Документация

http://127.0.0.1:8000/redoc/