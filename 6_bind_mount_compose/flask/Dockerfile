FROM python:3

RUN apt-get update -y 

WORKDIR /app

RUN pip install Flask requests flask_mysqldb

COPY . .

EXPOSE 5000

CMD [ "python3", "./app.py" ]