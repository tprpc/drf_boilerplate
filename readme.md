
# drf_boilerplate

## 시작하기(로그)

```
python3 -m venv venv
source venv/bin/activate 

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser --username admin --email admin@example.com

cp .env.example .env

# .env파일 수정

python manage.py runserver
```

# Trouble shooting

## Site matching query does not exist
> python manage.py shell
> 
> from django.contrib.sites.models import Site
> Site.objects.create(name='localhost:8000', domain='localhost:8000')


# References

https://wikidocs.net/91422
> django 시작하기

https://www.django-rest-framework.org/tutorial/quickstart/
> drf 시작할때 참고 app을 만들지는 않았음

https://velog.io/@jwun95/Django-%EB%B0%B0%ED%8F%AC%EB%A5%BC-%EC%9C%84%ED%95%9C-.env-%ED%8C%8C%EC%9D%BC-%EC%9E%91%EC%84%B1%EC%9D%84-%ED%95%B4%EB%B3%B4%EC%9E%90
> django env 사용하기

https://velog.io/@qlgks1/django-user-customizing-social-login-with-allauth-dj-rest-auth-simpleJWT
> 읽기 싫게 생겼지만 글이 많아서 도움이 될것으로 보아 시도
> django-allauth, dj-rest-auth 사용
> allauth 의 설치는 django-allauth임

https://django-rest-framework-simplejwt.readthedocs.io/en/latest/getting_started.html#installation
> jwt 도 추가