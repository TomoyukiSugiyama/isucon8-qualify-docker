FROM golang:1.10

COPY ./ /home/isucon/torb/webapp/bench
WORKDIR /home/isucon/torb/webapp/bench
RUN make deps
RUN make

CMD ["/home/isucon/torb/webapp/bench/bin/bench","-remotes=app:8080"]