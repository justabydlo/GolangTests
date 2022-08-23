FROM golang:latest

COPY ./ ./
RUN go env -w GO111MODULE=off
RUN go build -o main .
CMD ("./main")