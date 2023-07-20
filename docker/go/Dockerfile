FROM golang:1.20

COPY ./app/src /go/src

WORKDIR /go/src

RUN go build -o /go/src/main

ENTRYPOINT ["/go/src/main"]
