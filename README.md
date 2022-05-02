
## Building and running the application

    docker-compose up --build

## Running tests

    docker-compose run app sh -c "python manage.py test && flake8"


## Start server

    docker-compose up