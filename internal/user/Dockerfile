FROM golang:1.17-alpine

WORKDIR /app

COPY . /app

RUN go mod 

RUN go build -o chat-app .

EXPOSE 8080

ENV NAME chat-app

CMD ["./chat-app"]