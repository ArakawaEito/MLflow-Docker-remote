FROM python:3.10

WORKDIR /mlflow
COPY ./mlartifacts ./mlartifacts
COPY ./sqlite ./sqlite

RUN pip install -U pip && \
    pip install --no-cache-dir mlflow 
