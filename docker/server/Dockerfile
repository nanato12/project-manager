FROM golang:1.15-alpine

RUN apk update && \
    apk add curl git gcc libc-dev

RUN go get -u github.com/oxequa/realize && \
    go get -u github.com/rubenv/sql-migrate/...

ENV GO111MODULE=on
