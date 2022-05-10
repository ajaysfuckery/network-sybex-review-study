# The Transport Layer (Layer 4)
<hr>
- The Transport Layer is the first layer of the OSI model that Network Administrators are responsible for maintaining. The Transport Layer for TCP/IP contains 2 protocols that will be learned about later.

- The 2 protocols that are used at the Transport Layer are TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

- At this layer the Operating System presents the application with a socket to communicate with on the network. In the windows Operating System it is called *"WinSock"* and on Linux it is simply called a *"Socket"*

- Ports are used in this Layer and it is common to find firewalls operating at this Layer, to allow or block applications from using the network.

- When a client needs to get information from a Server, the Client application will bind to a port above 1023, on the other hand, port numbers below 1023 are in the RFC 3232. These port numbers are reserved for Servers

- UDP port numbers will be automatically recycled after a specific period of time because the Client and Server are not communicating the state of the Connection *(UDP is Connectionless)*.

- TCP port numbers are also recycled after a period of time but only after the communication between the Server and Client are finished communicating. *(TCP communicates the state of the connection as it is Connection-Oriented)*. 

- The first concept to note about the OSI model, is that when 2 devices are communicating with each other, they are communicating on the same level of the OSI model as each other. *(Meaning that the Transport Layer of the sending device is communicating with the Transport Layer of the Receiving device)*

- The second conept to note is that each layer of the OSI model communicates with the Layer above and the Layer below. *(Meaning that the Transport Layer of the OSI model is communicating with the Network Layer (Layer 3) and the Session Layer (Layer 5))*
