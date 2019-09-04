# Hello gRPC with goLang

[gRPC helloworld](https://github.com/kbehouse/gRPC-go-mTLS/tree/master/helloworld) & 

[gRPC mTLS (mutual TLS) helloworld](https://github.com/kbehouse/gRPC-go-mTLS/tree/master/helloworld_mTLS)

## Intro

helloworld/ from https://grpc.io/docs/quickstart/go/

helloworld_mTLS/ from 

* https://github.com/nicholasjackson/mtls-go-example
* http://krishicks.com/post/2016/11/01/using-grpc-with-mutual-tls-in-golang/

## Install

Install protoc

See: http://google.github.io/proto-lens/installing-protoc.html

```
brew install protobuf
```

Install protoc-gen-go
See: https://grpc.io/docs/quickstart/go/

```
go get -u github.com/golang/protobuf/protoc-gen-go
export PATH=$PATH:$GOPATH/bin
```

Init GoMod
```
# if directly use this repo, you don't need it
go mod init kbe.grpctest
```

