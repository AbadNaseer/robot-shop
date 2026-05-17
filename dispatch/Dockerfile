FROM golang:1.17

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go mod tidy && go build -o dispatch .

CMD ["./dispatch"]
