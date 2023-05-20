FROM postgres:15-bullseye

COPY coffee.sql /docker-entrypoint-initdb.d/coffee.sql

ENV PGDATA=/data