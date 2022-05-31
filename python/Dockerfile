FROM python:3.7-slim

WORKDIR /app

RUN python -m pip install --upgrade pip

COPY ./requirements.txt .

RUN python -m pip install -r requirements.txt

COPY . .