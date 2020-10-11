TASK 1
Problem Statement
Ping-Pong Clients

Make 2 client files which send data to each other using two different ports. One should send data (ex. "PING") and then recieve some data (ex. "PONG"). While the other should first receive data and then send an appropriate response.

First initialize a socket connection and connect it to different network interfaces, for testing you can use the same hostname: localhost and different ports using socket.gethostname(). Sending data is done using sendto() method. It accepts as arguments, the data and the network interface address as a tuple containing hostname and port number. Receiving data is done using the recv() function; it needs a buffsize argument to denote the size of the data packet to be received. P.S Also do not forget to encode and decode the data.


TASK 2
Echo Client and Server
Now that you’ve seen an overview of the socketrs , let’s create our first client and server. We’ll begin with a simple implementation. The server will simply echo
whatever it receives back to the client.
Socket Programming with Multi-threading
Now since you get the overall idea what Socket Programming Itjust helps us to connect a client to a server. Client is a message sender and receiver (aka server) is
just a listener and receives data sent by client.Now lets try to understand the stuff with threads .
In this task basically keep the socket connection part inside your main and create a threaded func which create a thread whenver a new clients joins and keeps
running until client exits
