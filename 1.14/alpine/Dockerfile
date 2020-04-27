FROM golang:1.14-alpine

MAINTAINER Enrico Hoffmann <dasrick@gmail.com>

RUN apk add --update --no-cache curl git zip gcc musl-dev \
    && curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | sh -s -- -b $(go env GOPATH)/bin \
    && go get -u golang.org/x/lint/golint
