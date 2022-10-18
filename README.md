# YatubeApi

Здравствуйте, это проект YatubeApi. С помощью него можно связать этот проект с вашими, а так же добавлять посты, комментарии, подписываться на людей не на сайте, а с помощью *JSON-запросов*.


## Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:

> git clone git@github.com:AnnaMolodova/api_final_yatube.git

> cd api_final_yatube

Cоздать и активировать виртуальное окружение:

> python3 -m venv env

> source env/bin/activate

>python3 -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:

> pip install -r requirements.txt

Выполнить миграции:

> python3 manage.py migrate

Запустить проект:

> python3 manage.py runserver


## Примеры запросов к API

Список ссылок на все доступные ресурсы
> [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

Получить список всех публикаций
> GET api/v1/posts/

Добавить новую публикацию
> POST  `POST api/v1/posts/`

Получение публикации по id
> GET /api/v1/posts/{id}/

Получение всех комментариев к публикации
> GET api/v1/posts/{post_id}/comments/

Получение списка доступных сообществ
> GET api/v1/groups/

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Computer+science+student)](https://git.io/typing-svg)
