FROM python

WORKDIR /srv/app/

RUN pip install --upgrade pip && pip install Flask Psycopg2 ConfigParser
COPY app/web.py ./
COPY app/web.conf ./


ENTRYPOINT ["python","web.py"]
