FROM golang:1.22.5 

RUN mkdir /app 

ADD . /app/ 

WORKDIR /app 

EXPOSE 8000

RUN go build -o main . 

CMD ["/app/main"]