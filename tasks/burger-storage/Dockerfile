FROM python:3.10-alpine

COPY . /app

WORKDIR /app

RUN chmod +x entry.sh

RUN python3 -m pip install -r requirements.txt

ENTRYPOINT [ "./entry.sh" ]