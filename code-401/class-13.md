# Class 13 Summary

## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because...

### Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.
   > The Chat Example is a web application that allows users to chat with each other in real-time. It uses Socket.IO, a library for handling real-time communication between the server and clients, to enable instant messaging.
2. What proof of life are we getting on the backend from the above app?
   > The proof of life we're getting on the backend from the above app is when the server is listening.
3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
   > You can use the socket.broadcast.emit() method with the event name. This will broadcast the event to all connected sockets except the one that triggered it.

### Rooms

1. What is a room and how might a room be useful?
   > A room is an arbitrary channel that sockets can `join` and `leave`. It might be useful because it can be used to broadcast event to subset of clients.
2. How do you join a room?
   > You join a room by using the code below:

```javascript
socket.join('some room');
```

3. How do you leave a room?
   > You leave a room by using the code below:

```javascript
socket.leave('roomName');
```

### Namespaces

1. What is a Namespace and what does it allow you to do?
   > A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").
2. Each namespace potentially has its own what? (hint: 3 things)
   > Each namespace potentially has its own set of identifiers, making them isolated from those in other namespaces. These identifiers can include variables, functions, or objects, each with its own separate scope, making it possible to have similar identifiers with different meanings or values in different namespaces.
3. Discuss a possible use case for separate namespaces
   > A possible use case for separate namespaces is in a cloud computing environment where multiple teams or projects share the same infrastructure. Each team or project can have its own namespace, ensuring isolation and preventing interference between their resources and configurations. For instance, in Kubernetes, namespaces can be used to segment applications, allowing different teams to deploy their services independently while sharing the same cluster resources.

### Reflection

1. What are your learning goals after reading and reviewing the class README?
   > Im excited to learn how to implement a messaging application.

### Things I want to learn more about.

> See additional Questions

#### I utilized ChatGPT for some of the questions.
