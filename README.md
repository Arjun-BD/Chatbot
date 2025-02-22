# Chat-Client-Server: A Simple TCP Chat Application in C

This repository contains a minimalistic **TCP-based chat application** implemented in C using **sockets** and **polling** for asynchronous communication. It consists of a **chat client** and **chat server**, allowing real-time message exchange over a network.

## Features
- Uses **BSD sockets** for network communication.
- Supports **polling (poll.h)** to handle multiple input sources.
- Allows **bi-directional chat** between client and server.

## Files
- `chat-client.c` – The client-side program that connects to the server.
- `chat-server.c` – The server-side program that listens for incoming connections.

## Usage
1. **Compile** both programs:
   ```sh
   gcc chat-server.c -o server
   gcc chat-client.c -o client

2. **Run the server** on a machine using the following command

   ```sh
   ./chat-server

3. **Run the client** and connect using the following command

   ```sh
   ./chat-client

Now, you can send and receive messages between the client and server in real time! 
