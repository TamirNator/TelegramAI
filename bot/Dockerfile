FROM python:3.8.12-slim-buster
WORKDIR /app

COPY utils.py  ./utils.py
COPY config.json  ./config.json
COPY ./bot/  ./

RUN pip3 install -r requirements.txt -t .

CMD ["python3", "-m", "app"]