python3 -m venv env

source env/bin/activate

pip install django

django-admin startproject watchmate

cd watchmate

python3 manage.py startapp watchlist_app

python3 manage.py  makemigrations

python3 manage.py migrate

python3 manage.py createsuperuser

pip install djangorestframework

python3 manage.py runserver 8069


----------------------------------------------------

**http://127.0.0.1:8070/movie/list**

![image](https://github.com/user-attachments/assets/ad759366-7cd0-4ee7-939d-602ae7266022)

-------------------------------------------------------------

**http://127.0.0.1:8070/movie/4**

![image](https://github.com/user-attachments/assets/24d11cf5-bc42-4950-8dd7-5090ad643971)

