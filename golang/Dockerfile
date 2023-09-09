FROM golang:1.16

WORKDIR /app

COPY ./hello.go .

RUN go mod init hello && \
    go build -o hello

CMD ["./hello"]
