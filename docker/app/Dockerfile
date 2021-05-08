FROM golang:1.10

COPY ./go /home/isucon/torb/webapp/go
WORKDIR /home/isucon/torb/webapp/go/
RUN make

EXPOSE 8080

ENTRYPOINT ["/home/isucon/torb/webapp/go/torb"]