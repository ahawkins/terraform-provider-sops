FROM golang:1.13-alpine

RUN apk add --no-cache gnupg make git curl tar zip

RUN apk add --no-cache -X http://dl-cdn.alpinelinux.org/alpine/edge/testing hub

RUN go get github.com/mitchellh/gox
