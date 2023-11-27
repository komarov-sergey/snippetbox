commands:
```go
go mod init snippetbox.sergeykomarov.net
go run ./cmd/web
go run ./cmd/web >>/tmp/web.log
go run ./cmd/web -addr=":9999"
go run ./cmd/web -help
```

mkdir -p cmd/web internal ui/html ui/static