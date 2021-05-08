FROM mariadb:5.5

COPY ./ /home/isucon/torb/db
WORKDIR /home/isucon/torb/db

ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes MYSQL_DATABASE=torb MYSQL_USER=isucon MYSQL_PASSWORD=isucon

#RUN ./init.sh

CMD ["--character-set-server=utf8mb4"]