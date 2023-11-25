## Проект kittygram_plus

Проект для практической отработки возможностей API. Доступен функционал по добавлению материалов, редактированию, удалению.

## Технологии

Python 3.9, Django 3.2, Django Rest Framework

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_plus.git
```

```
cd kittygram_plus
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Автор 
Ринат Хаматьяров (https://github.com/rest2011)
