FROM python:3

ENV PYTHONUNBUFFERED=1
WORKDIR /src
COPY . /src/

RUN pip install --upgrade pip
RUN pip install -r /src/requirements.txt

RUN adduser username
USER username
