FROM docker.io/library/golang
COPY . /kcdkerala
WORKDIR /kcdkerala
RUN go build main.go
ENTRYPOINT /kcdkerala/main
