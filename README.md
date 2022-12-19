# pwd

This package provide methods to hash and compare passwords.

## Installation

```bash
go get -u github.com/WebXense/pwd
```

## Hash password

```go
password := "myPassword"
hashedPassword := pwd.Hash(password)
```

## Compare password

```go
var check bool = pwd.Verify("myPassword", hashedPassword)
```
