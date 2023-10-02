# Class 12 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because...

### Web Sockets
1. What is a Web Socket?
> WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connections.
2. Describe the Web Socket request/response handshake and what happens once the connection is established.
> The WebSocket request/response handshake involves the client sending an HTTP request with an "Upgrade" header to the server, and if the server supports WebSocket, it responds with an HTTP 101 status code, indicating the connection is upgraded to WebSocket. Once the connection is established, both the client and server can exchange data in a bidirectional manner without the overhead of traditional HTTP requests and responses.
3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
> request
### Socket.io Tutorial
1. What does the event handler `io.on()` do?
> The event handler `io.on()` is used in the context of a Node.js server using a library like Socket.IO to listen for specific events from clients and perform actions when those events occur.
2. Describe some possible proof of life or proof that the code works as expected
> Possible proof of life or proof that the code works as expected could include logging messages, console outputs, or visual indicators in the application that demonstrate the successful execution of critical code sections or the occurrence of specific events during runtime.
3. What does `socket.emit()` do?
> `socket.emit()` is a method in Socket.IO that allows the server to send custom events to a specific client or to all connected clients. It enables server-to-client communication by emitting events that clients can listen for and respond to.

### Socket.io vs Web Sockets
1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
> WebSocket is a protocol for real-time, bidirectional communication over a single TCP connection, whereas Socket.IO is a library built on top of WebSocket that provides additional features like fallbacks for older browsers and built-in support for events.
2. When would you use Socket.IO?
> You would use Socket.IO when you need real-time communication between a server and clients, especially when you want to support a wide range of browsers, including older ones.
3. When would you use WebSockets?
> You would use raw WebSockets when you need a more lightweight and direct solution for real-time communication and have control over the entire WebSocket implementation, often in scenarios where browser compatibility is less of a concern.

### OSI Model Explained
1. What are a couple of key takeaways from this video?
> First takeaway is that there are 7 layers:
  1. Physical
  2. Data Link
  3. Network
  4. Transport
  5. Session
  6. Presentation
  7. Application
> Second takeaway is HTTP is part of Application Layers. For example, when we web surf, send email, etc.

### TCP Handshakes Explained
1. Translate the gist of this video to a non-technical friend
> A TCP handshake is like saying "hello" before you start talking on the phone. First, one person (the client) says, "Hi, can we talk?" Then, the other person (the server) says, "Yes, we can talk, and here's my special number." Finally, the first person says, "Great, let's talk with that special number now!" This way, they make sure they can understand each other before they start talking.

### Reflection
1. What are your learning goals after reading and reviewing the class README?
> My main learning goal would be to understand Socket.io and WebSockets to be able to create a messaging application.

### Things I want to learn more about.
> See additional Questions

#### I utilized ChatGPT for some of the questions.