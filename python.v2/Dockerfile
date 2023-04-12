FROM python:3-alpine3.16

WORKDIR /srv/app/

RUN pip install --upgrade pip && pip install Flask psycopg2-binary ConfigParser
COPY app/web.py ./
COPY app/web.conf ./


ENTRYPOINT ["python","web.py"]
