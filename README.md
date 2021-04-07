# grpc-eth

## Setup
1. Install gRPC
```
$ go get google.golang.org/grpc
```
2. Install Protocol Buffers v3
```
$ curl -OL https://github.com/protocolbuffers/protobuf/releases/download/v3.12.1/protoc-3.12.1-linux-x86_64.zip
$ unzip protoc-3.0.0-beta-2-linux-x86_64.zip -d ~/.local
$ export PATH="$PATH:~/.local/bin"
```
3. Install protoc plugin for go
```
$ export GO111MODULE=on  # Enable module mode
$ go get google.golang.org/protobuf/cmd/protoc-gen-go \
         google.golang.org/grpc/cmd/protoc-gen-go-grpc
```