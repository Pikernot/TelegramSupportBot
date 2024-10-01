FROM python:3.9-slim
WORKDIR /app

RUN pip install pyTelegramBotAPI pymysql

COPY . .

CMD ["./start.sh"]