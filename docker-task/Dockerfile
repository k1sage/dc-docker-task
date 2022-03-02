# syntax=docker/dockerfile:1

FROM golang:1.16-alpine

WORKDIR /app

ARG HTTP_PORT=8080

COPY app .

EXPOSE 8080

CMD [ "/app/app" ]