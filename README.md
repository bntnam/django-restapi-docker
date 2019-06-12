# django-restapi-docker

## Setup

- Clone django-restapi-docker project.
- Turn on Docker on your local machine.
- Run command `docker build .`.
- Run command `docker-compose build`.
- Run command `docker-compose up` and open browser at `localhost:8000`.

## Testing

- Run command `docker-compose run --rm app sh -c "python manage.py test && flake8"`

## API endpoints

- `/admin`
- `/api/user/create`
- `/api/user/token`
- `/api/user/me`
...

