From nimmis/alpine-micro

MAINTAINER nimmis <kjell.havneskold@gmail.com>

RUN apk update && \
    apk add curl && \
    curl -L -o glibc-2.23-r1.apk \
         "https://github.com/sgerrand/alpine-pkg-glibc/releases/download/2.23-r1/glibc-2.23-r1.apk" && \
    curl -L -o glibc-bin-2.23-r1.apk \
         "https://github.com/sgerrand/alpine-pkg-glibc/releases/download/2.23-r1/glibc-bin-2.23-r1.apk" && \
    apk add --allow-untrusted glibc-2.23-r1.apk glibc-bin-2.23-r1.apk && \
    rm -f glibc-2.23-r1.apk glibc-bin-2.23-r1.apk && \
    curl https://storage.googleapis.com/golang/go1.4.linux-amd64.tar.gz | tar xzf - -C / && \
    mv /go /goroot

ENV GOROOT=/goroot \
    GOPATH=/gopath \
    GOBIN=/gopath/bin \
    PATH=${PATH}:/goroot/bin:/gopath/bin

