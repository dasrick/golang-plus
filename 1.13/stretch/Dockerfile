FROM golang:1.13-stretch

MAINTAINER Enrico Hoffmann <dasrick@gmail.com>

RUN apt-get update \
    && apt-get install -y zip \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* \
    && curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | sh -s -- -b $(go env GOPATH)/bin \
    && go get -u github.com/golang/dep/cmd/dep \
    && go get -u golang.org/x/lint/golint \
