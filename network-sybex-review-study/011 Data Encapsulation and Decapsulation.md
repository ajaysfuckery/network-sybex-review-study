# Data Encapsulation and Decapsulation
<hr>
- When a host transmits data across the network to another device, the data goes through *encapsulation*. It's wrapped in protocol information at each layer of the OSI model.
- Each Layer of the OSI model on the *"sending device"* communicates with the relevant layer of the OSI model of the *"receiving device"*.
- To communicate and exchange information, each Layer of the OSI model uses *"Protocol Data Units (PDUs)"* .
- These hold control information attatched to the data at each layer of the OSI model.
- They're usually *attatched to the front of the data segment* but can be attatched to the end of the data. When control information is at the end of the data segment, it is called the *"trailer"*.
- At a *"sending device"* the data encapsulation works like this:
	1. User information is converted for data transmition on the network
	2. Data is converted into segments and a reliable connection is setup between the *"sending and receiving devices"*
	3. Segments are converted into *"packets or datagrams"* and a *"logical address (IP Address)"* is placed in the header so each packet can be routed through the *"Internetwork"*. *A packet carries a segment of data.*
	4. Packets or Datagrams are converted to *"Frames"* for transmission on the local network. Hardware (*"Ethernet"*) ***{MAC Addresses}*** are used to uniquely identify hosts on a local network segment. *Frames carry packets*.
	5. Frames are converted into *"bits"* and a digital encoding and *"clocking scheme"* is used.

##### How does step 5 work?
<hr>
- This is called a modulation technique
- In networks *"Modulation"* is the process of varying one or more properties of a waveform called the *"Carrier signal"* with a signal that typically contains information to be transmitted. 

- In current networks modulation takes a digital or analog signal and puts another signal and puts it in another signal that can be physically transmitted across the wires.

- A modulator is a device that performs modulation of a signal and demodulator does the opposite of of a modulator.