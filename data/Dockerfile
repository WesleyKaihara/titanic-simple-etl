FROM mysql:8.0.16

ENV MYSQL_ROOT_PASSWORD database

COPY ./database.sql /docker-entrypoint-initdb.d/01-database.sql