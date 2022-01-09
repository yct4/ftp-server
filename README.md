# ftp-server

Includes a client and server.

Steps:
0. Setting up Go on computer and being able to build file - X
1. Learn about ftp protocol - review the RFC and Go tutorial *
2. Set up main.go file with basic listener that listens for new connections
3. Set up FTP server - implement FTP protocol
- connection type
- command types
- Serve function
4. Set up FTP client
5. Work on a GUI for our ftp client (and maybe server?)

Resources:
- Installing Go: https://go.dev/learn/
- Go basics: https://go.dev/tour/welcome/1
- ftp protocol: https://www.rfc-editor.org/rfc/rfc4217.txt *
- tutorial: https://betterprogramming.pub/how-to-write-a-concurrent-ftp-server-in-go-part-1-3904f2e3a9e5
- How to vendor dependencies in Go: (using go modules) -> https://go.dev/ref/mod#mod-commands
- Golang GUI types -> https://github.com/go-graphics/go-gui-projects
- Golang nettest library -> https://pkg.go.dev/golang.org/x/net/nettest
- How to test in Go -> 
