# Protocol Data Units
<hr>
- The term *Protocol Data Units (PDUs)* is how we describe the type of data transferred at each layer of the OSI model. 

| OSI Layers | PDUs |
|---|---|
| Application | Application Protocol Data Unit |
| Presentation | Presentation Protocol Data Unit |
| Session | Session Protocol Data Unit |
| Transport | Segment |
| Network | Packet |
| Data Link | Frame |
| Physical | Bits |

- The first 3 layers of the OSI model *(Application, Presentation, Session)* reference the components of an Application.

- The PDU for these upper layers is considered to be *User Datagrams* or just *Datagrams*

- The Datagrams are passed from the Application Layers down to the Transport Layer

- The Transport Layer is where segments are created from the Datagrams and then the segments are passed to the Network Layer.

- At the Network Layer packets are created from the segments and passed to the Data Link Layer

- The Data Link Layer creates frames for transmitting the data in bits at the Physical Layer