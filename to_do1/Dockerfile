from python:3.8.6

#RUN apt-get update \
#&& apt-get install -y postgresql postgresql-contrib libpq-dev python3-dev

RUN pip install --upgrade pip

COPY ./ ./
RUN pip install -r requirements.txt

RUN pip install gunicorn

#COPY wait-for-postgres.sh .
#RUN chmod +x wait-for-postgres.sh
