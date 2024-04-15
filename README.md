Booking service with python django and react and material ui

Для того чтобы запустить локально проект необходимо установить python и npm:

```shell
sudo apt install python3
sudo apt install nodejs
sudo apt install npm
```

Затем установить необходимые зависимости:

```shell
pip install -r requirements.txt
cd frontend/
npm install
```

После этого необходимо выполнить миграции:

```shell
python3 manage.py makemigrations
python3 manage.py migrate
```

И наконец можно запустить сервис:

```shell
python3 manage.py runserver
cd frontend/
npm run dev
```

Затем можно открыть ссылку http://127.0.0.1:8000/register и протестировать работу приложения.

Приложение также развернуто на сайте http://158.160.98.129