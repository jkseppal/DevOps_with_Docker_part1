FROM golang:1.15

EXPOSE 8080

WORKDIR usr/src/app

COPY . .

ENV REQUEST_ORIGIN=http://localhost:5000

RUN go build

CMD ["./server"]