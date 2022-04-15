
# Проект YATUBE

## Описание

YATUBE является социальной сетью с возможностью публикации постов, по желанию автора, к посту можно прикрепить фото.
Зарегистрированные пользователи могут оставлять комментарии к постам, а так же подписываться на посты интересных авторов.
Пользователи без регистрации могут ознакомиься с последними постами всех авторов.

## Установка и запуск
    0. Клонировать репозиторий и перейти в него в командной строке:
        git clone git@github.com:AlukardPetrovich/progect_yatube.git
        cd progect_yatube

    1. Создать виртуальное окружение
        python -m venv venv

    2. Активировать виртуальное окружение
        source venv/bin/activate

    3. Установить зависимости
        pip install -r requirement.txt

    4. Задать переменные окружения в .env-файле или другим способом 

    5. Выполнить миграции
        python yatube/manage.py makemigrations
        python yatube/manage.py migrate

    6. Запустить проект
        python yatube/manage.py runserver 

    7. Открыть в браузере по адресу http://127.0.0.1:8000 при запуске на локальной машине,
        либо в соответствии с адресом вашего хоста.
