FROM golang:1.16

WORKDIR /usr/src/app

COPY . .

ENV REQUEST_ORIGIN=http://localhost:5000

ENV REDIS_HOST=redis

RUN go build

EXPOSE 8080

CMD ./server
