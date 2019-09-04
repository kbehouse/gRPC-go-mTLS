

# gRPC with mTLS(Mutual TLS) using Go

## Generate key & cert

```
cd cert_key/
./generate.sh localhost password
```

## Run

```
# term 1 
go run greeter_server/main.go
# term 2
go run greeter_client/main.go
```

## Refer:
   
* https://github.com/nicholasjackson/mtls-go-example
* http://krishicks.com/post/2016/11/01/using-grpc-with-mutual-tls-in-golang/