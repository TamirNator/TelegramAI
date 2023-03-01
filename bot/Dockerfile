FROM python:3.8.12-slim-buster
WORKDIR /app

COPY requirements.txt ./requirements.txt

RUN pip3 install requirements.txt

CMD ["python3", "-m", "bot.app"]