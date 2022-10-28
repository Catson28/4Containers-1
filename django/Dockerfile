# docker_tutorial/backend/Dockerfile
FROM python:3.8
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
COPY . /app
WORKDIR /app
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN pip install Django psycopg2
# RUN python manage.py makemigrations
# RUN python manage.py migrate
CMD gunicorn -b 0.0.0.0:8000 --worker-class=gevent --worker-connections=1000 --workers=5 backend.wsgi   
