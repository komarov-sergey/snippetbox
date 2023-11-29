## commands:

### go:
```sh
go mod init snippetbox.sergeykomarov.net
go run ./cmd/web
go run ./cmd/web >>/tmp/web.log
go run ./cmd/web -addr=":9999"
go run ./cmd/web -help
```

### db:
```sh
brew services start mysql
mysql -u root
```

### general:
```sh
mkdir -p cmd/web internal ui/html ui/static
```