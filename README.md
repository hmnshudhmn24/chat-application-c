# Chat Application in C (Socket Programming)

## Description
A **simple chat application** using **TCP sockets** in C. It consists of:
- A **server** that listens for client connections.
- A **client** that connects to the server and allows message exchange.

## Files
- `server.c` - Server-side implementation
- `client.c` - Client-side implementation
- `Makefile` - Compilation script

## Usage

1. **Compile the code using `make`**:
   ```sh
   make
   ```

2. **Start the server**:
   ```sh
   ./server
   ```

3. **Run the client** in a separate terminal:
   ```sh
   ./client
   ```

4. **Start chatting!**

## Example Output

### Server:
```
Server listening on port 8080...
Client: Hello Server
Server: Hi Client!
```

### Client:
```
Client: Hello Server
Server: Hi Client!
```

## Cleanup
To remove compiled files:
```sh
make clean
```