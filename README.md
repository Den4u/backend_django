### Учебный проект «Kittygram»

### 1. Описание проекта:
Kittygram - позволяет пользователям публиковать посты со своими любимыми котиками, делиться их фотографиями и достижениями.

### 2. Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Den4u/infra_sprint1.git
```

```
cd infra_sprint1/backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
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
python manage.py migrate
```

Cоздать файл .env (в директории /backend), содержащий пары ключ-значение всех переменных окружения.

```
SECRET_KEY=***
DEBUG=***
ALLOWED_HOSTS=***
```

Запустить проект:

```
python manage.py runserver 0:8090
```
