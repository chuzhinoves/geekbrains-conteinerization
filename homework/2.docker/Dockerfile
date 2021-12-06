FROM python:3.8.6
ADD python/ code/
RUN pip install -r code/requirements.txt
WORKDIR /code
ENTRYPOINT flask run --host 0.0.0.0 --port 8080