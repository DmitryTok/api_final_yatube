# api_final
api final
API для проекта социальной сети YaTube

В рамках этого API можно:
Получать все посты с возможностью фильтрации по группе
Создавать, редактировать или удалять собственные посты
Комментировать другие посты или смотреть комментарии определенного поста
Создавать группы для постов
Подписываться на понравившегося автора
Посмотреть все подписки, также возможен поиск подписок конкретного пользователя
Выполнить аутентификацию по JWT-токену
=======
**API_Yatube**
=====


Добро пожаловать в проект api_yatube! Это сервис, позволяющий делать HTTP запросы к базе данных сервиса блогов "Yatube" через интерфейс REST API.
Реализована возможность создавать, изменять, просматривать записи и комментарии к ним разных авторов, а так же подписываться на авторов и просматривать группы, в которых собраны посты определённой тематики.
### Как запустить проект:

Clone the repository:

```
git clone https://github.com/DmitryTok/api_yatube_final.git
```

```
cd api_yatube_final
```

Create a visual environment:

```
python3 -m venv venv
```

```
source venv/Scripts/activate
```

Install requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Make mingations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```

**Doc for requests examples available on link http://127.0.0.1:8000/redoc**
