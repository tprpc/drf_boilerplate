
# drf_boilerplate

## 시작하기(로그)

```
python3 -m venv venv
source venv/bin/activate 

pip install djangorestframework
pip install django


python manage.py migrate

python manage.py createsuperuser --username admin --email admin@example.com

pip install django-environ

cp .env.example .env

# .env파일 수정

python manage.py runserver
```
