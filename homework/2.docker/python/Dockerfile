FROM python:3.8-bullseye

ENV PYTHONUNBUFFERED 1

RUN mkdir /app

ADD requirements.txt .

RUN pip install -r requirements.txt

ADD . /app

EXPOSE 8080

ENTRYPOINT python /app/app.py
