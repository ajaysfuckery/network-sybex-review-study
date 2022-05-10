# UDP (User Datagram Protocol)
<hr>
#### UDP
<hr>
- UDP is a transport protocol for TCP/IP. 
- UDP is one of two protocols that operate at the Transport Layer that connect applications to the Network
- UDP is *connectionless* which means that the user data is simply passed from one IP address to the receiving IP address.
- The sending computer won't even know if the destination computer is listening for the data.
- The reciept of data is not acknowledged by the destination computer
- The data blocks send over UDP are not sequenced in any way for the receiving computer to to put them back together

- Benefits of using UDP:
	  - UDP is faster than TCP

- Real-Time-Protocol (RTP) VoIP protocol doesn't care to acknowledge segments or retransmit segments. If a segment of data doesn't make it to the receiving device, the RTP will just keep moving along with voice data in Real-Time

#### TCP (Transmission Control Protocol)
<hr>
- TCP is another transport protocol for TCP/IP. Just like UDP, TCP is a protocol that connects applications to the network.
- TCP is responsible for all data delivery.
- TCP is a connetion-oriented protocol.
- During the transmission, both ends create a virtual circuit over the network.
- All data segments are sequenced, acknowledged and retransmitted if lost in transit
- TCP is extremely reliable but slower than TCP.

- When the sending computer transmits data to a receiving computer, *a virtual connection is created* using a *3 way handshake*. 
- During the 3 way handshake the *window buffer on each size is negotiated with the SYN and ACK flags* in the TCP Haeder.
- When both sender and receiver acknowledge the window's size, the connection is considered established and data can be transferred.
- When the data transfer is complete, the sender can issue a FIN flag in the TCP Header to end the connection. 