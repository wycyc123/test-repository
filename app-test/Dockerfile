FROM golang
MAINTAINER  cyc
WORKDIR /go/src/
COPY . .
WORKDIR /go/src/app
RUN go build main.go
EXPOSE 8890
CMD ["/bin/bash", "/go/src/script/build.sh"]