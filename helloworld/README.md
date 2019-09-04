
# gRPC Hello world with goLang

## generate pb 

```
cd helloworld/
protoc -I helloworld/ helloworld/helloworld.proto --go_out=plugins=grpc:helloworld
```

## Run

```
cd helloworld/
# term 1 
go run greeter_server/main.go
# term 2
go run greeter_client/main.go
```

## Refer & More Info

Quick Start: https://grpc.io/docs/quickstart/go/

Tutorial: https://grpc.io/docs/tutorials/basic/go/