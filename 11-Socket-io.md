# Socket.io

* What is the benefit of transforming data into packets?

Packet-based networks enable new innovations, services, and business opportunities, they are also the most cost-effective, efficient, and scalable networks for content delivery.

* UDP is often refereed to as a connectionless protocol. Why is this?

it analogous to sending a letter where you don't acknowledge receipt.

* Can a socket server application have multiple socket connections?

Yes, multiple connections on the same server can share the same server-side IP/Port.

Can a socket connection application be connected to multiple socket servers?

No.

Can an application be both a socket server and a socket connection?

Yes by using UDP.

* Observer Pattern

Observer is a behavioral design pattern.

* Listener

A procedure or function in a computer program that waits for an occurance.

* Event Handler

Callback routine that operates asynchronously once an event takes place.

* Event Driven Programming

Computer program that is written to respond to actions generated by the user or the system.

* Event Loop

The secret behind JavaScript's asynchronous programming.

* Event Queue

A repository where events from an application are held prior to being processed by a receiving program or system.
* Call Stack

 A stack data structure that stores information about the active subroutines of a computer program.

* Emit/Raise/Trigger

  Event Emitter is a module that facilitates communication/interaction between objects in Node, raise is a request to execute handlers that are defined for an event at a given time and trigger is a function that decide what code to run when there are a specific event occurs,

* Subscribe

A messaging pattern where senders of messages.

* database

 an organized collection of structured information, or data, typically stored electronically in a computer system.

 * OSI Model Explained

 The OSI Model is a used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support different products and software.

* TCP handshake

The procedure that takes place between TCP/IP nodes to establish a reliable connection. The connection is full duplex, and both sides synchronize and acknowledge each other, a two way handshake would only allow one party to establish an ISN, and the other party to acknowledge it. Which means only one party can send data. But TCP is a bi-directional communication protocol, which means either end ought to be able to send data reliably.

* Web Sockets

An advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server.allowing to send messages to a server and receive event-driven responses without having to poll the server for a reply.

* Socket.io

Socket.io allows bi-directional communication between client and server. Bi-directional communications are enabled when a client has Socket.io in the browser, and a server has also integrated the Socket.io package. While data can be sent in a number of forms, JSON is the simplest. Socket.io is a very useful piece of technology. Furthermore, socket.io can be intercepted and modified in real-time but there is no Repeater, Scanner, or Intruder functionality for it.

Key Differences between WebSocket and socket.io, it provides the Connection over TCP, while Socket.io is a library to abstract the WebSocket connections. The client instance, which is the low-level engine that establishes the connection to the server.




- repo link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/README.md)

- Live Link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/11-Socket-io.md)