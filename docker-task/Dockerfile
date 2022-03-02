# syntax=docker/dockerfile:1

FROM golang:1.16-alpine

WORKDIR /app

ENV HTTP_PORT=8080
ENV IP_ADDR=172.17.0.2

COPY app .

EXPOSE 8080

CMD [ "/app/app" ]