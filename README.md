# Парсер документации Python

Проект парсера позволяет получать информацию о новостях и всех версиях Python, скачивать документацию по последней версии Python в формате PDF(A4) и информацию по статусам и количеству PEP.

Включает в себя следущие возможности:
* Проверка обновлений Python
* Загрузка документации
* Проверка статусов PEP

## Стек технологий:

* Python 3.7.9
* Библиотека BeautifulSoup4

## Как запустить проект:

* Клонировать репозиторий:

```
git clone git@github.com:vikkilat/bs4_parser_pep.git
```

* Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

* Установить зависимости из файла ```requirements.txt```:

```
pip install -r requirements.txt
```

* Cкачать документацию по последней версии Python в формате PDF(A4):
```
python src/main.py download
```

* Получить информацию по статусам и количеству PEP с записью в файл формата csv:
```
python src/main.py pep -o file
```

## Автор:
[Латышева Виктория](https://github.com/vikkilat)
