# django-restapi-docker

## Setup

- Clone django-restapi-docker project.
- Turn on Docker on your local machine.
- Run command:
```
$ docker-compose build
```

```
$ docker-compose up
```

## Testing

- Run command:
```
$ docker-compose run --rm app sh -c "python manage.py test && flake8"
```

## API endpoints

- `/admin`
- `/api/user/create`
- `/api/user/token`
- `/api/user/me`
- `/api/recipe/tags`
- `/api/recipe/ingredients`
- `/api/recipe/recipes`
- `/api/recipe/recipes/{recipe_id}`
- `/api/recipe/recipes/{recipe_id}/upload-image`