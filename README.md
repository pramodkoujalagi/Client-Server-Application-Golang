In this example, the server listens on port 8080, and the client connects to this port. The server echoes back any message received from the client.

To run the example: (Go must be installed in your pc)

1. Open two terminal windows.
2. In one terminal, run the server with 'go run server.g'
3. In the other terminal, run the client with go run client.go "Hello, Server!"

The client will send the message to the server, and the server will echo it back. The client then prints the echoed message received from the server.
