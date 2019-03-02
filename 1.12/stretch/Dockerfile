FROM golang:1.12-stretch

MAINTAINER Enrico Hoffmann <dasrick@gmail.com>

RUN apt-get update && apt-get install -y zip \
    go get -u github.com/golang/dep/cmd/dep \
    go get -u golang.org/x/lint/golint
