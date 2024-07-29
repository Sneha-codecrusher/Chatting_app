# Chatting_app
The project has been made using Java Swings and Socket Programming. The application helps two users to communicate with each other in the form of messages and has the interface based on the idea of Whatsapp. Communication is done with help of socket programming. 

MAIN OBJECTIVE:

The aim of this project is to express how we can implement a simple chat application between a server and a client? The application is a desktop based application and is implemented using Swing and awt. The project is developed in Java SE language executed on a single stand-alone java across a network using loop back address concept. 
Application consists of two programs:

1.Server
2.Client

Server :The server module of the application waits for the client to connect to it. Then if connection is granted a client interacts communicates and connects to the server, it can mutually communicate with the server. The duty of the server is to let clients exchange the messages.

Client : The client module is the one that utilizer sends requests to the server. Utilizer utilizes the client as the means to connect to the server. Once he establishes the connection, he can communicate to the connected server.

Operational Concepts and Scenarios:

Operation of the application based on the inputs given by the user: 
When the run button is clicked then the chat form is initialized with a connection between the host and the client machine.  
Note: server must be started at first before a client start.
Contains a rich textbox which send messages from one user to another.
Contains a textbox for messages to be written that is sent across the network.
Contains a Send button.
When the send button is clicked, in the background, the text in the textbox is encoded and sent as a packet over the network to the client machine. Here this message is decoded and is shown in the rich textbox.

CONCLUSION:

I Developed network applications in Java by using sockets, threads, and Web services. This software is portable, efficient, and easily maintainable for large number of clients. Our developed web-based chatting software is unique in its features and more importantly easily customizable. The java.net package provides a powerful and flexible set of classes for implementing network applications. Typically, programs running on client machines make requests to programs on a server Machine. These involve networking services provided by the transport layer. The most widely used transport protocols on the Internet are TCP (Transmission control Protocol) and UDP (User Datagram Protocol). TCP is a connection-oriented protocol providing a reliable flow of data between two computers. On the other hand, UDP is a simpler message-based connectionless protocol which sends packets of data known as datagrams from one computer to another with no guarantees of arrival.

