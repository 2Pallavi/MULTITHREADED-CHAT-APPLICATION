# MULTITHREADED-CHAT-APPLICATION

*COMPANY : CODTECH IT SOLUTIONS*

*NAME : PALLAVI CHAUDHARI*

*INTERNID : CITS0D131*

*DOMAIN : JAVA PROGRAMMING*

*DURATION : 4 WEEKS*

*MENTOR : NEELA SANTOSH*

*DISCRIPTION* :This project is a basic chat application built using Java that allows multiple users to communicate with each other in real time. It consists of two main parts: a server and multiple clients. The server manages all the connections and messages, while clients are the users who send and receive chat messages.

Working:The server runs and listens for client connections on a specific port.
When a client connects, the server creates a new thread to handle communication with that client. This allows the server to handle many clients at the same time without blocking others.
Each client enters their name and then can send messages.
When a client sends a message, the server broadcasts that message to all other connected clients so everyone can see it.
If a client disconnects, the server notifies the remaining clients.
Technologies Used:
Java programming language.
Java Sockets to handle network communication.
Threads to manage multiple clients simultaneously.

Feature :
Multithreading: The server uses a separate thread for each client, allowing multiple users to chat simultaneously.
Socket Programming: The communication between server and clients happens over network sockets.
Real-time Messaging: Messages from any client are instantly sent to all others connected.
User Identification: Each user enters their name when connecting so messages are labeled with who sent them.
Simple Console Interface: Both server and clients run in the console for easy testing and use.

*output :
