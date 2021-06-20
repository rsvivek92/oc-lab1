FROM mysql:5.7

ENV MYSQL_ALLOW_EMPTY_PASSWORD yes
ENV MYSQL_DATABASE demo
ADD test.sql /docker-entrypoint-initdb.d/
