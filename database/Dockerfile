 FROM mysql

ENV MYSQL_ROOT_PASSWORD="navchi02"
ENV MYSQL_DATABASE="accounts"

ADD accountsdb.sql  docker-entrypoint-initdb.d/accountsdb.sql
