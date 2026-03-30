[![Kittygram workflow](https://github.com/OlegUFO/kittygram_final/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/OlegUFO/kittygram_final/actions/workflows/main.yml)
        
# TASKI AND KITTYGRAM

# Описание проекта 
Проект представляет собой 2 приложения: Taski - приложение, предназначенное для создания заметок. Kittygram - приложение, где ты можешь выкладывать фото своих кошечек, а также прикладывать их достижения. 

## Стек использованных технологий
1. Python 3.13
2. Django 5.1.1
3. Pytest
4. Django REST Framework
5. PyYAML
6. PostgreSQL

## Установка
1. Клонировать репозиторий и перейти в него в командной строке:
```
git@github.com:OlegUFO/kittygram_final.git
```
``` 
cd kittygram_backend 
```

2. Cоздать и активировать виртуальное окружение:
``` 
python3 -m venv env 
``` 
 
* Если у вас Linux/macOS 
    ``` 
    source env/bin/activate 
    ``` 
* Если у вас windows 
    ``` 
    source env/scripts/activate 
    ```
``` 
python3 -m pip install --upgrade pip 
```

3. Установить зависимости из файла requirements.txt:
``` 
pip install -r requirements.txt 
```

4. Выполнить миграции:
``` 
python3 manage.py migrate 
```

5. Запустить проект:
``` 
python3 manage.py runserver 
```

### Автор проекта - Oleg Rykov (OlegUFO)
