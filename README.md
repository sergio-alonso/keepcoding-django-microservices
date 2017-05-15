# KeepCoding Djando Microservices

```
$ git --version
git version 2.12.0.306.g4a9b9b32d

$ docker --version
Docker version 17.03.1-ce, build c6d412e

$ docker-compose --version
docker-compose version 1.13.0, build 1719ceb

$ virtualenv --version
15.1.0
```

```
$ git clone git@github.com:sergio-alonso/keepcoding-django-microservices.git && cd keepcoding-django-microservices

$ git submodule init && git submodule update
```

```
$ mkvirtualenv -a . keepcoding-django-microservices

$ git submodule foreach pip install -r requirements.txt
```
