FROM python:3.8.5-buster

RUN pip install --upgrade pip wheel setuptools

RUN mkdir /app
COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt -r requirements-test.txt
RUN pip install -e .
