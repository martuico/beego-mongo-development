FROM golang:1.7

# Install beego & bee
RUN go get github.com/astaxie/beego
RUN go get github.com/beego/bee
RUN go get gopkg.in/mgo.v2
RUN go get github.com/dgrijalva/jwt-go

COPY code/ /go/src/code
WORKDIR /go/src/code
CMD bee run
