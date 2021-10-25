Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/DmitryTok/api_final_yatube.git
Перейти в созданный репозиторий:

cd api_final_yatube
Cоздать и активировать виртуальное окружение:

python -m venv venv
source venv/scripts/activate
Обновить установщик расширений pip

python -m pip install --upgrade pip
Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
Выполнить миграции и собрать файлы статики:

python manage.py migrate
python manage.py collectstatic
Запустить проект:

python manage.py runserver
Документация с примерами запросов и ответов будет доступна после развёртывания и запуска проекта по ссылке http://127.0.0.1:8000/redoc
