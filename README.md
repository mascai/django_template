# django_docker_nginx_template

Django + Nginx + Gunicorn + Celery + Postgres template for development.

Intended to increase speed of parsers development

Related article: https://habr.com/ru/post/662928/

## How to run
```
docker-compose up -d
```

## Rebuild and run
```
docker-compose up -d --build
```


### Requests
Each request should have a token in headers.
```
Name -- Authorization
Values example -- Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNjUxMTQyMzQ2LCJpYXQiOjE2NTExNDIwNDYsImp0aSI6IjlmYzBlNzYwZDY2MzQ0ODVhNWY5ODRlNWUwNmExYTMzIiwidXNlcl9pZCI6MX0.5XPTxa1NXX8lfAKEi7mdLgoMBB1pf0EiB0MNZvhbus0
```
