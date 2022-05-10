# The Data Link Layer (Layer 2)
<hr>
- The Data Link Layer is responsible for the framing of data for transmission on the Physical Layer or Media

- The Data Link Layer is also responsible for the static addressing of hosts 

- At the Data Link Layer unique *MAC addresses (Media Access Control)* are pre-programmed into the Network Cards (Computers) and Network Interfaces. Modern Network Interface Cards allow you to override thier pre-programmed MAC addresses

- The Data Link Layer is only concerned with the local delivery of frames in the same immediate network.

- Switching of frames occurs at this Layer, therefore switches operate at this Layer.

- The Data Link Layer is divided into 2 layers
	- Logical Link Control (LLC)
	- Media Access Control (MAC)

- The LLC sublayer is responsible for communicating with the Network Layer
- The LLC sublayer is where CPU cycles are used for the processing of data.

- The MAC Layer is responsible for the hardware processing of frames and error-checking of frames, it is also responsible for the transmission of data on the physical level

- A MAC address is a 48-bit (6-byte) physical address burned into the Network controller of every network card and a network device.
	- MAC addresses are usually written as a hexadecimal expression