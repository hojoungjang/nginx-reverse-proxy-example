FROM golang:alpine

WORKDIR /app

COPY go.mod ./

RUN go mod download && go mod verify

COPY . .
RUN go build -o server

CMD ["./server"]
