FROM python:3.12.2-alpine

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

CMD [ "python3", "./client.py"]
