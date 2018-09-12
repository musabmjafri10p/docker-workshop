FROM golang:latest 

ADD . /app/ 
WORKDIR /app/golangapp 


RUN go build -o bin/main .

CMD ['./bin/main']

# ENTRYPOINT ["go", "build", "-o", "bin/main", "."]
