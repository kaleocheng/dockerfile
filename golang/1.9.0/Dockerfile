FROM golang:1.9.0-alpine
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
RUN apk update --no-cache && apk add make git bash parallel gcc musl-dev
RUN mkdir -p /data/src/
ENV GOPATH /data
