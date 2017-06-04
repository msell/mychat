To start the host:
go run main.go -listen localhost (or ip address)

to start a client
go run main.go localhost

or use 
netcat - general purpose networking tool for tcp/udp

nc localhost 8080

to build for windows

GOOS=windows GOARCH=amd64 go build -o mychat.exe