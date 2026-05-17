FROM golang:1.21

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go mod tidy && go build -o dispatch .

CMD ["./dispatch"]
