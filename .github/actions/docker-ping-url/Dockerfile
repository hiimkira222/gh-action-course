FROM python:alpine3.19

WORKDIR /app

COPY requirements.txt .

RUN py -V
RUN py -m pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "/app/main.py" ]