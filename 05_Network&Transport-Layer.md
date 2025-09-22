transport and network layer are closely tied together

Transmission Control Protocol/Internet Protocol (TCP/IP) most commonly used to set transport (end to end delivery of the message)

TCP/IP was developed by U.S. Department of Defense (ARPANET = Adavanced Reseearch Project Agency network)

Every application has a port assigned to it (TCP is a process-to-process connection)

Streaming networks work on UDP 

most popular protocol set, used by almost all backbone networks (BNs) and WANs

Allow reasonably efficient and error-free transmissions

TCP/IP has two parts: TCP is a transport layer protocol that  links application layer to network, IP routes message to destination

User Datagram Protocol (UDP) internet protocol suite has a second type of transport layer

UDP PDUs are called datagrams, used when sender needs to send a small single small packet to receiver (DNS request), has only four fields (8 bytes)

Internet Protocol is the network layer protocol

Transport layer linsk the application software 

Internet Assigned Numbers Authority (IANA) maintains official list of well known registered ports, well-known ports reserved for service and aapplications (0-1023)

Registered ports numbers are assigned to user processses or applications (1024-49151)

Dynamic and Private Ports are usually assigned dynamically to client applications when initiating a connection (49152-xxxx)

TCP handshake: syn seq client from client to server and server sends syn-ack seq client to client and eventually client ack and getss access to server

sequence number request to change to acknowledge number and changes acknowledge number back to sequence number (4-way handshake with last step being termination)

Session can be thought of as a conversation between two computers, when a computer wants to send a message to the receiver must send a SYN (synchronize) and receive a ACK (acknowledgement) segment

once connection is established, segments flow between sender and reciever (in case error, receiver simply 

stop-and-wait ARQ, sender stops and waits for response after each data packet, after packet received it can either be ACK or NAK (negative acknowledgement), sender resends previous message, and if ACK sender continues with next message

Continuous ARQ, sender does not wait for an ACK after sending a message, packets are retransmitted maybe if containing an error 

Connectionless messaging means each packet is treated separately 

Subnet mask identify network address and host address, default gateway is adddress of your router

Different classes of IP addresses 



