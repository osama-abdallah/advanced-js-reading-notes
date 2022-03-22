# Message Queues

* What does it mean that web sockets are bidirectional? Why is this useful?

WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

* Does socket.io use HTTP? Why?

socket.io depeands on HTTP to install connection setup.

* What happens when a client emits an event?

Useing the emit function on the socket object. To handle these events, use the on function on the socket object on your server

* What happens when a server emits an event?

emits the payload for all the clients triggering the callback function for the event.

* What happens if a client “misses” an event?

the server receives the event

* How can we mitigate this?

we can use a “heartbeat” to keep the connection alive

* Socket

A socket is one endpoint of a two-way communication link between two programs running on the network.

* Web Socket

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

* Socket.io

Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.

* Client

it is the library that runs inside the browser, accesses services or functionality from server

* Server

It is the library for Node.js which Provides services and functionality for clients

* OSI Model

Open Systems Interconnection Model is a conceptual framework used to describe the functions of a networking system.

* TCP Model

specifications for translating the network addressing methods used in the Internet Protocol to link-layer addresses.

* TCP

Transmission control protocol. TCP provides reliable, ordered, and between applications running on hosts communicating via an IP network.

* UDP

User Datagram Protocol is a communications protocol for connections between applications on the internet.

* Packets

A packet consists of control information and user data.

* Rooms and Namespaces

What is Room and Namespaces?

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients. Rooms are a server-only concept i.e. the client does not have access to the list of rooms it has joined. Each Socket in Socket.IO is identified by a random, unguessable, unique identifier Socket #id. We can call join to subscribe the socket to a given channel. Use to or in (they are the same) when broadcasting or emitting.

Socket.IO allows you to Namespace your sockets, which essentially means assigning different endpoints or paths. This is a useful feature to minimize the number of resources (TCP connections) and at the same time separate concerns within your application by introducing separation between communication channels. Multiple namespaces actually share the same WebSockets connection thus saving us socket ports on the server. Namespaces are created on the server side. But they are joined by clients by sending a request to the server.

- repo link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/README.md)

- Live Link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/12-Message-Queues.md)