
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


# References

https://wikidocs.net/91422
> django 시작하기

https://www.django-rest-framework.org/tutorial/quickstart/
> drf 시작할때 참고 app을 만들지는 않았음

https://velog.io/@jwun95/Django-%EB%B0%B0%ED%8F%AC%EB%A5%BC-%EC%9C%84%ED%95%9C-.env-%ED%8C%8C%EC%9D%BC-%EC%9E%91%EC%84%B1%EC%9D%84-%ED%95%B4%EB%B3%B4%EC%9E%90
> django env 사용하기

