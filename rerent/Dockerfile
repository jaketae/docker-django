FROM python:3.7-alpine
ENV PYTHONUNBUFFERED 1
RUN mkdir app
WORKDIR app
COPY . .
RUN pip install -r requirements.txt
