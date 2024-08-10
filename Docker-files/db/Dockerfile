FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Felix Martey"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initd.d/db_backup.sql
