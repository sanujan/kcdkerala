FROM docker.io/library/golang
RUN . /kcdkerala
WORKDIR /kcdkerala
RUN go build main.go
ENTRYPOINT /kcdkerala/main
