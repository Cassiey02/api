# api_yamdb
## Применяемые технологии
[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=56C0C0&color=008080)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat&logo=Django&logoColor=56C0C0&color=008080)](https://www.djangoproject.com/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-464646?style=flat&logo=PostgreSQL&logoColor=56C0C0&color=008080)](https://www.postgresql.org/)
[![GitHub%20Actions](https://img.shields.io/badge/-GitHub%20Actions-464646?style=flat&logo=GitHub%20actions&logoColor=56C0C0&color=008080)](https://github.com/features/actions) 
## Описание
    Проект собирает отзывы пользователей на произведения, такие как «Книги», «Фильмы», «Музыка». Пользователи имеют возможность оставлять к произведениям текстовые отзывы и ставить произведениям оценку; из пользовательских оценок формируется усреднённая оценка произведения — рейтинг. На одно произведение пользователь может оставить только один отзыв. Так же пользователи могут оставлять комментарии к отзывам.
## Установка
    Для установки требуется кланировать проект командой: git clone <Ссылка_на_проект>.
    Далее создайте: _py -m venv venv_
    и активируйте виртуальное окружение: _source venv/Scripts/activate _
    установите все необходимые пакеты:_ pip install -r requirements.txt_
    После этого проект готов к запуску.
## Наполнение базы
    Для наполнения базы данными из файлов csv, требуется из дирректории, где лежит файл manage.py, выполнить команду: python manage.py import_csv
## Автор проекта
Данный проект выполнялся в команде CaSSiDYFox@yandex.ru