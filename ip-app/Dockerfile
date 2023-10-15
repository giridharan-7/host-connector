FROM python:alpine.3.7
COPY . /app
WORKDIR /app
RUN pip install flask
EXPOSE 5000
RUN python ./app.py