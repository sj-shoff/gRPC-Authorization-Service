# gRPC-Authorization-Service
Сервис авторизации, к которому в дальнейшем будет прикручен URL Shortener

## Проект разделен на 2 части : работа с proto и сам сервис авторизации

### PROTO
```bash
protoc -I proto proto/sso/sso.proto --go_out=./gen/go --go_opt=paths=source_relative  --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative
```