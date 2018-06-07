# go-mariadb
Connects to MariaDB, allow to executes queries and statements.

## Install
go get github.com/barrantesosvaldo/go-mariadb

## Usage
First you have to initialize the connection with:
```go
import mdb "go-mariadb"
mdb.Connect("username", "password", "host", "port", "database", "utf8")
```
