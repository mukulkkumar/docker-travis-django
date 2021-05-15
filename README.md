# Travis CI django Integration

## *To build docker image*
```
docker-compose build
```

## *To start project, run:*

```
docker-compose up
```

*The API will then be available at http://127.0.0.1:8000.*

## *To test the build*
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```
