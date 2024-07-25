FROM postgres:16.3-bookworm

COPY coffee.sql /docker-entrypoint-initdb.d/coffee.sql

ENV PGDATA=/data