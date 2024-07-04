# ya_news

Сайт, где опубликованы новости, а пользователи могут оставлять к ним свои комментарии. В этом проекте я реализвала коллекцию тестов unittest.

**Развернуть проект:** 

Клонировать репозиторий и перейти в него в командной строке: git clone git@github.com:poli-na-96/ya_news.git cd ya_news

Cоздать и активировать виртуальное окружение: python3 -m venv venv source venv/Scripts/activate

Установить зависимости из файла requirements.txt: pip install -r requirements.txt

Запустить проект: python manage.py runserver

**Для загрузки заготовленных новостей после применения миграций выполните команду:** python manage.py loaddata news.json

**Язык:** Python 3.9.10

**Cтек технологий:** python, django, git
