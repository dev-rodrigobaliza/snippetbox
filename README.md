# Lets Go

implementation of the book

## Generating a self-signed TLS certificate

```
mkdir tls
cd tls
go run /usr/local/go/src/crypto/tls/generate_cert.go --rsa-bits=2048 --host=localhost
```