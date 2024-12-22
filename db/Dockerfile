FROM mysql:8.0

RUN /bin/cp -f /etc/localtime /etc/localtime.org
RUN /bin/cp -f /usr/share/zoneinfo/Asia/Tokyo /etc/localtime

RUN mkdir -p /var/log/mysql
RUN chown mysql.mysql /var/log/mysql

COPY ./my.cnf /etc/my.cnf