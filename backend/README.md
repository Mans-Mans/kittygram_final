### Описание проекта китиграм - https://mansur.sytes.net
**Этот проект позволяет людям:**
* Любоваться котиками.
* Загружать фотографии своих котиков.
* Описывать своего котика(цвет, год рождения, скилл).
* Выбирать скилы кота из имеющихся, а также добавлять свои.
* На сайте обязательна система регистрации.

### Стек технолигий
* Python3.10.6
* Django
* djangorestframework
* Nginx
* Gunicorn
* React
* Certbot
* Docker

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

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

Установить зависимости из файла requirements.txt:

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

### Примеры запросов:
* https://mansur.sytes.net - главная страница, видны все котики
* https://mansur.sytes.net/signin - страница авторизации
* https://mansur.sytes.net/signup - страница регистрации
* https://mansur.sytes.net/cats/add - страница добавления котика на сайт
* https://mansur.sytes.net/cats/(id_котика) - информация о конкретном котике

### Автор проекта - Миндугулов Мансур
