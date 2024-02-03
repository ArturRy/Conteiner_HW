FROM python:3.10-alpine

WORKDIR /app
RUN apk update \
    && apk add postgresql-dev gcc python3-dev musl-dev
COPY . .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
