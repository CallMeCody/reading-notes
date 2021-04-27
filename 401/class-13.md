### CLASS 13


# Message Queue



### What does it mean that web sockets are bidirectional? Why is this useful?

- Bidirectional is a communications mode that is capable of transmitting data in both directions to send and receive, but not at the same time.


### Does socket.io use HTTP? Why?

- Yes it can.


### What happens when a client emits an event?

- when the client emits an event will get to the listner on the server side and an event is triggered.


### What happens when a server emits an event?

- When our server emits events which match the first 'event' argument the callback will be run. Inside these callbacks we can take the actions we want on the client-side.


### What happens if a client “misses” an event?

- The events will be ignored.

### How can we mitigate this?

- you can mitigate this by having event handlers with some kind of logic.




## TERMS:



* ``` Socket ```


* ``` Web Socket ```

The WebSocket is a way to exchange data between browser and server via a persistent connection. The data can be passed in both directions as “packets”, without breaking the connection and additional HTTP-requests.

* ``` Socket.io ```


- Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js


* ``` client ```

- A client refers to the program on the user side

* ``` Server ```

-  A server refers to the programm running by the server side to connect to the client.

* ``` OSI Model ```

- The Open Systems Interconnection model is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.

* ``` TCP Model ```

- The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks. It is commonly known as TCP/IP because the foundational protocols in the suite are the Transmission Control Protocol and the Internet Protocol.

* ``` TCP ```

- It is one of the most commonly used protocols within digital network communications and ensures end-to-end data delivery.

* ``` UDP ```

- User Datagram Protocol is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.

* ``` Packets ```

-  Packets carry the data in the protocols that the Internet uses.
