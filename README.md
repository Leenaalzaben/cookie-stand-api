# LAB - Class 34 || "Putting it All Together"

## Project: Cookie Stands api || [Cookie Stands api](https://github.com/Leenaalzaben/cookie-stand-api/pull/1)

### Author || LeeNa Alzaben

### Setup

- The username <br>
`{
    "username": "leena",0
    "password": "0000",
    "owner": 1
}`
- Create virtual environment and activate it :
`python -m venv .venv`
`source .venv/bin/activate`

- Install requirements :
`pip install -r requirements.txt`

- To run the server
- `python3 manage.py runserver`

- Create a superuser with all permissions
- `python3 manage.py createsuperuser`

- Make migrations
- `python3 manage.py makemigrations`
- `python3 manage.py migrate`

- Command for Docker part
- `docker-compose up`
- `docker-compose up --build`

- `docker-compose run web python3 manage.py migrate`
- `docker-compose run web python3 manage.py createsuperuser`
