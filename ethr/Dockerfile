FROM golang:1.13

ARG GOOS

RUN echo the GOOS=$GOOS

WORKDIR /app

ADD ./ /app

RUN mkdir /out && \
    go build .
