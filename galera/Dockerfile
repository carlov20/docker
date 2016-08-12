FROM mariadb

MAINTAINER cv
ENV MYSQL_ROOT_PASSWORD=galera
EXPOSE 3306
EXPOSE 4444
EXPOSE 4567
EXPOSE 4568
COPY my.cnf /etc/mysql/my.cnf
RUN chmod 644 /etc/mysql/my.cnf