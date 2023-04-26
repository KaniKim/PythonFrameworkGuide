# PythonFrameworkGuide
이 레포지토리는 파이썬 웹 프레임워크들을 정리한 것으로 각각의 프레임워크에 맞는 가이드, 도큐 등등을 소개합니다. 

다양한 파이썬 웹 프레임워크를 위한 자료들을 정리하는 레포로, 혹여 접속이 안되는 사이트가 있을 경우, 추가하고 싶은 내용이 있으실 경우 kkh5428[@]gmail.com 으로 연락부탁드립니다.

<br>
<hr>
<br>

# 주의사항
## 1. 누구나 참여 가능합니다.
### - 누구나 참여 가능한 프로젝트이며, 누구나 수정할 수 있습니다.
## 2. 정확도가 높지 않을 수 있습니다.
### - 직접 조사해가면서 하나하나 추가하였기에 부족한 프로젝트 입니다.
## 3. 그 외
### - 여러분들의 많은 참여를 기다리고 있습니다.

<br>
<hr>
<br>

# Django Document
## Django & Django Third Party Library 

<br>
<hr>

## Django의 버전은 현재 지원되는 버전 기준으로만 작성했습니다.
### - 2.2, 3.2, 4.0, 4.1, 4.2만 기재됩니다.

<br>
<hr>

- Django - verison : <b> 4.2 </b>
  - HP : https://www.djangoproject.com
  - Github : https://github.com/django/django
  - 설치방법 : pip install django
  - 각 버전별 지원되는 파이썬 버전:
    - Version 3.2 : 3.6, 3.7, 3.8, 3.9, 3.10 (added in 3.2.9)
    - Version 4.0 : 3.8, 3.9, 3.10 
    - Version 4.1 : 3.8, 3.9, 3.10, 3.11 (added in 4.1.3)
    - Version 4.2 : 3.8, 3.9, 3.10, 3.11


<br>

- Django Rest Framework - version : <b> 3.14.0 </b>
  - HP : https://www.django-rest-framework.org
  - Github : https://github.com/encode/django-rest-framework
  - 설치방법 : pip install djangorestframework
  - 지원되는 파이썬 버전 : 3.6, 3.7, 3.8, 3.9, 3.10
  - 지원되는 장고 버전 : Django(3.0, 3.1, 3.2, 4.0, 4.1)

<br>

- Django Extensions - version : <b> 3.2.1 </b>
  - HP : https://django-extensions.readthedocs.io/en/latest/
  - Github : https://github.com/django-extensions/django-extensions
  - 설치방법 : pip install django-extensions
  - 지원되는 장고 버전 : Django(3.2, 4.0, 4.1)
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11


<br>

- Django Cors Headers - version : <b> 3.14.0 </b>
  - Github : https://github.com/adamchainz/django-cors-headers
  - 설치방법 : pip install django-cors-headers
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(3.2, 4.0, 4.1, 4.2)

<br>

- Django AllAuth - version : <b> 0.54.0 </b>
  - HP : https://www.intenct.nl/projects/django-allauth/
  - HP : https://django-allauth.readthedocs.io/en/latest/
  - Github : https://github.com/pennersr/django-allauth
  - 설치방법 : pip install django-allauth
  - 지원되는 파이썬 버전 : 3.5, 3.6, 3.7, 3.8, 3.9, 3.10
  - 지원되는 장고 버전 : Django(2.2, 3.2, 4.0, 4.1, 4.2)

<br>

- Django Debug Toolbar - version : <b> 4.0.0 </b>
  - HP : https://readthedocs.org/projects/django-debug-toolbar
  - Github : https://github.com/jazzband/django-debug-toolbar
  - 설치방법 : pip install django-debug-toolbar
  - 지원되는 파이썬 버전 : 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(3.2, 4.0, 4.1, 4.2)
  
<br>

- django-crispy-form - version : <b> 2.0 </b>
  - HP : https://readthedocs.org/projects/django-crispy-forms/
  - Github : https://github.com/django-crispy-forms/django-crispy-forms
  - 설치방법 : pip install django-crispy-forms
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(3.2, 4.0, 4.1, 4.2)
    - 장고 4.0 이후 버전의 경우 django-crsipy-form 1.13이상이 필요

<br>

- Django Ninja - version : <b>0.21.0</b>
  - HP : https://django-ninja.rest-framework.com
  - Github : https://github.com/vitalik/django-ninja
  - 설치방법 : pip install django-ninja
  - 지원되는 파이썬 버전 : 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(2.2, 3.2, 4.0, 4.1, 4.2) 

<br>

- django-rest-framework-jwt - version: <b>1.19.3</b>
  - HP : https://styria-digital.github.io/django-rest-framework-jwt/
  - Github : https://github.com/Styria-Digital/django-rest-framework-jwt
  - 설치방법 : pip install drf-jwt
  - 지원되는 파이썬 버전 : 2.7, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(2.2, 3.2, 4.0, 4.1, 4.2)
  - 그외 지원되는 버전 : Django REST Framework(3.7 or later)


<br>

- Simple JWT - version : <b>5.2.2</b>
  - HP : https://django-rest-framework-simplejwt.readthedocs.io/en/latest/
  - Github : https://github.com/jazzband/djangorestframework-simplejwt
  - 설치방법 : pip install djangorestframework-simplejwt
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10
  - 지원되는 장고 버전 : Django(2.2, 3.2, 4.0, 4.1)
  - 그외 지원되는 버전 : Django REST Framework (3.10, 3.11, 3.12, 3.13)


<br>

- drf-yasg - version : <b>1.21.5</b>
  - HP : https://drf-yasg.readthedocs.io/en/stable/
  - Github : https://github.com/axnsan12/drf-yasg
  - 설치방법 : pip install -U drf-yasg
  - 지원되는 파이썬 버전 : 3.6, 3.7, 3.8, 3.9
  - 지원되는 장고 버전 : Django(2.2, 3.0, 3.1)
  - 그외 지원되는 버전 : Django Rest Framework(3.10, 3.11, 3.12)

<br>

- django-simple-history - version : <b>3.3.0</b>
  - HP : https://django-simple-history.readthedocs.io/en/latest/
  - Github : https://github.com/jazzband/django-simple-history
  - 설치방법 : pip install django-simple-history
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 장고 버전 : Django(3.2, 4.0, 4.1)

<br>

- dhapne - version : <b> 4.0.0 </b>
  - Github : https://github.com/django/daphne/
  - 설치방법 : pip install daphne
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10
  
<br>
<hr>
<br>

# Flask Document
## Flask & Flask Third Party Library 

<br>

- Flask - version : <b> 2.3.1 </b>
  - HP : https://flask.palletsprojects.com/en/2.0.x/
  - Github : https://github.com/pallets/flask
  - 설치방법 : pip install Flask
  - 지원되는 파이썬 버전 : 3.8, 3.9, 3.10, 3.11
  - 디펜던시 :
    - Werkzeug 
    - Jinja 
    - MarkupSafe 
    - ItsDangerous
    - Click
    - Blinker 

<br>

- Flask-Classful - version : <b>0.14.2</b>
  - HP : https://flask-classful.teracy.org/
  - Github : https://github.com/teracyhq/flask-classful
  - 설치방법 : pip install flask-classful

<br>

- Flask-RESTful - version : <b> 0.2.12 </b>
  - HP : https://flask-restful.readthedocs.io/en/latest/
  - Github : http://github.com/twilio/flask-restful
  - 설치방법 : pip install flask-restful
  - 지원되는 파이썬 버전 : 2.7, 3.4, 3.5, 3.6, 3.7
  - 지원되는 플라스크 버전 : Flask(1.0 or later)

<br>

- Flask-RESTX - version : <b>1.1.0</b>
  - HP : https://flask-restx.readthedocs.io/en/latest/
  - Github : https://github.com/python-restx/flask-restx
  - 설치방법 : pip install flask-restx
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 플라스크 버전 :
    - 2.0.0 미만 : 0.4.0
    - 2.0.0 이상 : 0.5.0 이후 버전

<br>

- Flask-WTF - version : <b>1.1.1</b>
  - HP : https://flask-wtf.readthedocs.io/en/1.0.x/
  - Github : https://github.com/wtforms/flask-wtf
  - 설치방법 : pip install -U Flask-WTF
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  
<br>

- Flask-Mail - version : <b>0.9.1</b>
  - HP : https://pythonhosted.org/Flask-Mail/
  - Github : http://github.com/mattupstate/flask-mail
  - 설치방법 : pip install Flask-Mail
  - 지원되는 파이썬 버전 : 3.x

<br>

- Flask-DebugToolbar : <b>0.13.1</b>
  - HP : https://flask-debugtoolbar.readthedocs.io/en/latest/
  - Github : https://github.com/flask-debugtoolbar/flask-debugtoolbar
  - 설치방법 : pip install flask-debugtoolbar
  - 지원되는 파이썬 버전 : 3.x, 2.x는 드롭될 예정

<br>

- Flask-SQLAlchemy - version : <b>3.0.3</b>
  - HP : https://flask-sqlalchemy.palletsprojects.com/en/2.x/
  - Github : https://github.com/pallets-eco/flask-sqlalchemy
  - 설치방법 : pip install -U Flask-SQLAlchemy
  - 지원되는 파이썬 버전 : 2.7, 3.4 이상
  - 지원되는 플라스크 버전 : 0.12 이상
    - 2.x의 경우 파이썬 2.7, 3.4 이상, 플라스크 0.12 이상, SQLAlchemy의 경우 0.8 이상 혹은 0.10이상일 경우 파이썬 3.7이 같이 따라와야 한다.
    - 3.x이 경우 파이썬 2.7, 3.5 이상, 플라스크 1.0 이상, SQLAlchemy의 경우 1.0 이상이 되어야 한다.

<br>

- Flask-Login - version : <b>0.6.2</b>
  - HP : https://flask-login.readthedocs.io/en/latest/
  - Github : https://github.com/maxcountryman/flask-login
  - 설치방법 : pip install flask-login
  - 지원되는 파이썬 버전 : 3.7 이상
  - 지원되는 플라스크 버전 : 1.0.4 이상

<br>

- Flask-Limiter - version : <b>3.3.0</b>
  - HP : https://flask-limiter.readthedocs.io/en/stable/
  - Github : https://github.com/alisaifee/flask-limiter
  - 설치방법 : pip install Flask-Limiter
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  - 지원되는 플라스크 버전 : 2.x 이상

<br>

- Flask-APISpec - version : <b>0.11.4</b>
  - HP : https://flask-apispec.readthedocs.io/en/latest/
  - Github : https://github.com/jmcarp/flask-apispec
  - 설치방법 : pip install -U flask-apispec

<br>

- Flask-JWT-Extended - version : <b>4.4.4</b>
  - HP : https://flask-jwt-extended.readthedocs.io/en/stable/
  - Github : https://github.com/vimalloc/flask-jwt-extended
  - 설치방법 : pip install flask-jwt-extended
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10
  - 지원되는 플라스크 버전 : 2.x 이상

<br>

- Flask-User - version : <b>1.0.2.2</b>
  - HP : https://flask-user.readthedocs.io/en/latest/
  - Github : https://github.com/lingthio/Flask-User
  - 설치방법 : pip install Flask-User
  - 지원되는 파이썬 버전 : 2.7, 3.4, 3.5, 3.6, 3.7, 3.8
  - 지원되는 플라스크 버전 : 0.9 이상

<br>

- Flask-MongoEngine - version : <b>1.0.0</b>
  - HP : https://docs.mongoengine.org/projects/flask-mongoengine/en/latest/
  - Github : https://github.com/MongoEngine/flask-mongoengine
  - 설치방법 : pip install flask-mongoengine
  - 지원되는 파이썬 버전 : 3.6, 3.7, 3.8, 3.9


<br>
<hr>
<br>

# FastAPI Document
## FastAPI & FastAPI Third Party Library 

<br>

- FastAPI - version : <b>0.95.1</b>
  - HP : https://fastapi.tiangolo.com
  - Github : https://github.com/tiangolo/fastapi
  - 설치방법 : pip install fastapi, "uvicorn[standard]"
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11
  
<br>

- FastAPI Users - version : <b>10.4.2</b>
  - HP : https://fastapi-users.github.io/fastapi-users/
  - Github : https://github.com/fastapi-users/fastapi-users
  - 설치방법
    - SQLAlchemy : pip install 'fastapi-users[sqlalchemy2]'
    - MongoDB : pip install 'fastapi-users[mongodb]'
    - Tortoise ORM : pip install 'fastapi-users[tortoise-orm]'
    - ormar : pip install 'fastapi-users[ormar]'

<br>

- FastAPI Admin - version : <b>1.0.3</b>
  - HP : https://fastapi-admin-docs.long2ice.io
  - Github : https://github.com/fastapi-admin/fastapi-admin
  - 설치방법 : pip install fastapi-admin

<br>

- FastAPI JWT Auth - version : <b>0.5.0</b>
  - HP : https://indominusbyte.github.io/fastapi-jwt-auth/
  - Github : https://github.com/IndominusByte/fastapi-jwt-auth
  - 설치방법 : pip install fastapi-jwt-auth

<br>

- FastAPI SQLAlchemy- version : <b>0.2.1</b>
  - Github: https://github.com/mfreeborn/fastapi-sqlalchemy
  - 설치방법 : pip install fastapi-sqlalchemy
  - 지원되는 파이썬 버전 : 3.6, 3.7, 3.8
  
<br>

- FastAPI Code Generator : <b>0.4.1</b>
  - HP : https://koxudaxi.github.io/fastapi-code-generator/
  - Github : https://github.com/koxudaxi/fastapi-code-generator
  - 설치방법 : pip install fastapi-code-generator
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11

<br>

- FastAPI-MAIL : <b>1.2.8</b>
  - HP : https://sabuhish.github.io/fastapi-mail/getting-started/
  - Github : https://github.com/sabuhish/fastapi-mail
  - 설치방법 : pip install fastapi-mail
  - 지원되는 파이썬 버전 : 3.8, 3.9, 3.10, 3.11

<br>

- FastAPI CRUD Router : <b>0.8.6</b>
  - HP : https://fastapi-crudrouter.awtkns.com/
  - Github : https://github.com/awtkns/fastapi-crudrouter
  - 설치방법 : pip install fastapi-crudrouter
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11

<br>
<br>
<hr>

# ETC Document
## 그 외에 파이썬 프레임 워크에서 자주 쓰는 라이브러리

<br>

- Alembic - version : <b>1.7.7</b>
  - HP : https://alembic.sqlalchemy.org/en/latest/
  - Github : https://github.com/alembic/alembic
  - 설치방법 : pip install alembic
  -  Guidline
     - https://alembic.sqlalchemy.org/en/latest/tutorial.html
     - https://blog.neonkid.xyz/257
     - https://medium.com/@sutharprashant199722/how-to-use-alembic-for-your-database-migrations-d3e93cacf9e8

<br>

- SQLAlchemy - version : <b>1.4.32</b>
  - HP : https://www.sqlalchemy.org
  - Github : https://github.com/sqlalchemy/sqlalchemy
  - 설치방법 : pip install SQLAlchemy
  - Guideline
    - https://docs.sqlalchemy.org/en/14/tutorial/index.html
    - https://edykim.com/ko/post/getting-started-with-sqlalchemy-part-1/
    - https://flask-docs-kr.readthedocs.io/ko/latest/patterns/sqlalchemy.html
    - https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/

<br>

- Psycopg2-binary - version : <b>2.9.3</b>
  - HP : https://www.psycopg.org/docs/
  - Github : https://github.com/psycopg/psycopg2
  - 설치방법 : pip install psycopg2-binary
 
<br>

- PyMySQL - version : <b>1.0.2</b>
  - HP : https://pymysql.readthedocs.io/en/latest/
  - Github : https://github.com/PyMySQL/PyMySQL
  - 설치방법 : pip install PyMySQL


<br>

- PyMongo - verison : <b>4.0.2</b>
  - HP : https://pymongo.readthedocs.io/en/stable/
  - Github : https://github.com/mongodb/mongo-python-driver
  - 설치방법 : pip install pymongo
  
<br>

- uvicorn - version : <b>0.17.6</b>
  - HP : https://www.uvicorn.org
  - Github : https://github.com/encode/uvicorn
  - 설치방법 : pip install uvicorn
  
<br>

- gunicorn - version : <b>20.1.0</b>
  - HP : https://gunicorn.org
  - Github : https://github.com/benoitc/gunicorn
  - 설치방법 : pip install gunicorn
  

<br>

- starllete - version : <b>0.26.1</b> =/= <b> 파이썬 3.6의 경우 - 0.19.1 </b>
  - HP : https://www.starlette.io/
  - Github : https://github.com/encode/starlette
  - 설치방법 : pip3 install starlette
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11

<br>

- uWSGI - version : <b> 2.0.21 </b>
  - HP : https://uwsgi-docs.readthedocs.io/en/latest/WSGIquickstart.html
  - Github : https://github.com/unbit/uwsgi
  - 설치방법 : pip install uwsgi

<br>

- Hypercon - version : <b> 0.14.3 </b>
  - HP : https://pgjones.gitlab.io/hypercorn/
  - GitLab : https://gitlab.com/pgjones/hypercorn
  - 설치방법 : pip install hypercorn
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10

<br>

- MongoEngine - version : <b>0.27.0</b>
  - HP : https://docs.mongoengine.org/
  - Github : https://github.com/MongoEngine/mongoengine
  - 설치방법 : python -m pip install -U mongoengine
  - 지원되는 파이썬 버전 : 3.6, 3.7, 3.8, 3.9, 3.10
  - 지원되는 몽고디비 버전 : 3.6, 4.0, 4.4, 5.0
  - 디펜던시 : 
    - pymongo>=3.4
    - dateutil>=2.1.0
    - Pillow>=2.0.0
    - blinker>=1.3
    
<br>

- Pydantic - version : <b> 1.10.7 </b> / beta : <b> 2.0.0 </b>
  - HP : https://docs.pydantic.dev
  - Github : https://github.com/pydantic/pydantic
  - 설치방법 : pip install -U pydantic
  - 지원되는 파이썬 버전 : 3.7, 3.8, 3.9, 3.10, 3.11

<br>
<br>

# 수정 일시 : 2022.03.19 + 09:00 
## - 기초 틀 잡기, Django, FastAPI, Flask 추가

<br>

# 수정 일시 : 2022.03.20 + 09:00
## - Alembic, Sqlalchemy 등의 라이브러리 추가

<br>

# 수정 일시 : 2022.08.25 + 09:00
## - django library추가, django guide 추가, Flask, FastAPI library추가

<br>

# 수정 일시 : 2022.08.26 + 09:00
## - Django 지원 라이브러리들의 지원 파이썬 버전들 추가 틀 새로잡기, 업데이트된 버전 추가

<br>

# 수정 일시 : 2023.04.26 + 09:00
## - 전체적인 틀 및 수정 사항 그리고 내용 추가
