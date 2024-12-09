FROM python:3.10-slim

WORKDIR /app

COPY requirements.txt ./
RUN pip3 install -r requirements.txt
COPY .env .env

ADD . .

EXPOSE 3000

CMD [ "python", "app.py"]