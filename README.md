# api_final
api final
API for the YaTube social network project

Within this API, you can:
Get all posts with the ability to filter by group
Create, edit or delete your own posts
Comment on other posts or view comments on a specific post
Create groups for posts
Subscribe to your favorite author
View all subscriptions, it is also possible to search for subscriptions of a specific user
Authenticate with a JWT token
=======
**API_Yatube**
=====


Welcome to the api_yatube project! This is a service that allows you to make HTTP requests to the database of the "Yatube" blogging service through the REST API interface.
Implemented the ability to create, edit, view entries and comments to them by different authors, as well as subscribe to authors and view groups that contain posts on a certain topic.
### How to run the project:

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
