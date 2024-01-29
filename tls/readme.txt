create cert.pem and key.pem files using generate_cert.go file

cd tls
go run YOUR_PATH_TO_GO\go\src\crypto\tls\generate_cert.go --rsa-bits=2048 --host=localhost
