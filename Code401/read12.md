# Scoket.io

## Web Sockets 

A *WebSocket* is a communication technology that allows a client, like a web browser, and a server to exchange information in real time. Unlike regular HTTP requests, WebSockets keep the connection open so both sides can send information whenever needed.

**WebSocket Request/Response**

The client starts by sending an HTTP request asking the server to upgrade the connection to WebSocket. If the server accepts, it responds with a 101 Switching Protocols status. Once connected, both the client and server can send messages back and forth without needing to create a new connection for every message.

WebSockets provide a standardized way for the server to send content to a client without first receiving a <u>**REQUEST**</u> from that client.

## Socket.IO Tutorial

The `io.on()` method listens for specific events. For example, io.on('connection') detects when a new client connects to the server, allowing the server to respond and communicate with that client.

The `socket.emit()` method sends a named event, along with optional data, to the other side of the connection. For example, it can send a chat message from a client to the server or from the server to a client.

**How do we know the code is working?** 

* We can check the terminal for messages showing that a client has connected or disconnected. We can also send a test message between the client and server to verify that both sides receive and respond to events correctly.

## Socket.IO vs WebSockets

WebSocket is a standard communication protocol that allows real-time, two-way communication. Socket.IO is a JavaScript library that makes real-time communication easier by providing additional features like automatic reconnection, custom events, and broadcasting.

It's similar to Git and GitHub: WebSocket provides the underlying communication standard, while Socket.IO offers additional tools to simplify development. However, Socket.IO uses its own protocol and is not directly interchangeable with a plain WebSocket connection.

**When should we use them?** 

* I would use **Socket.IO** when building applications like chat rooms, multiplayer games, or live notifications where automatic reconnection and managing multiple users are helpful.

* I would use **WebSockets** when I need direct, real-time communication between a client and server without the additional features of Socket.IO. This can be useful for applications where keeping communication lightweight and using a standard protocol are priorities.

## OSI Model Explained (Videos)

One important takeaway is that the OSI model has seven layers, each responsible for a different part of how information travels across a network. These layers work together to make communication between devices possible.

Another takeaway is that understanding these layers helps developers identify and troubleshoot network problems because it makes it easier to determine where communication might be failing.

## TCP Handshakes Explained

A TCP handshake is how two devices establish a reliable connection before exchanging information. It's similar to starting a phone conversation.

First, one person says, "Hello, can you hear me?" The other responds, "Yes, I can hear you. Can you hear me?" Finally, the first person confirms, "Yes!"

This represents the three steps of a TCP handshake: **SYN, SYN-ACK, and ACK.** Once both devices acknowledge the connection, they can begin exchanging information. This process helps ensure that both sides are ready to communicate.