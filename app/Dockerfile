FROM python:3.8

WORKDIR /app
COPY requeriments.txt /app/requeriments.txt

RUN pip install --no-cache-dir -r /app/requeriments.txt


COPY . /app

CMD bash -c "while true; do sleep 1; done"