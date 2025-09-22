Data link layer deals with reliable transmission between two modules

logical link control [llc] is sublayer of data link layer to the network layer above it

media access control sublayer controls the physical hardware

Header and trailor 

both sender and receiver have to agree on rules and protocols

Contention is commonly used in Ethernet LANs, wait until circuit is free

Two commonly used controlled access techniques: accessing requests and polling

Polling is process of sending signal to client computer that permits it to transmit, roll-call polling

Contention approach works better than controlled approaches for small networks that have low usage

networks should be designed to prvent detect and correct, network errors two categories: corrupted data and lost data

Burst error appear in burst, more than 1 data bit is changed by the error-causing condition

if errors were not clustered, character checking schemes would be effective

Error Detection: Checksum (1 byte added to end of message), Parity Checking (one bit is added to eaach byte, based on number of 1s added), Cyclic redundancy checking (message treated as one long binary number)

Forward error correction uses codes containing sufficient redundancy to prevent errors by detecting and correcting them at receiving end (without retransmission of original message)

Asynchronous transmission is referred to as start-stop (one bit)

Syncronous transmission all letters or data in one group of data as a block od daata at one time, frame = block of data, start and end of entire frame must be marked

Synchronous data link protocols: SDLC, HDLC, Ethernet

Mainframe protocol syncronous data link control developed by IBM 1972, each frme begins and ends with special bit patter of (011110) known as flag

Data Link layer has two parts which are media access control (MAC) and logical link control (LLC): ensures proper flow of data and connect with network layer 

Header contains MAC (source and destination) and trailer contains error-detection like cyclic redundancy check (CRC) to ensure integrity 

Identifies stand and end of a message using a PDU

IEEE is a set of standard that define physical layers and data link layers 

High-Level Data Link Control (HDLC): often used in WAN formal standard developed by ISO, almost same as syncronous data link control but the address and control fields can be longer

Several benefits of HDLC have continuous ARQ

Ethernet is very popular LAN protocol in 1973 by Bob Metcalfe 1973, uses contention media access protocol, frame starts with a 7-byte preamble

computers sharing same physical network infrastructure through vlan tagging, appropriate network segmentation

Point-to-Point Protocol (PPP): often used in WANs in 1990s, designed to transfer data over point to point circuit, can be used on multipoint circuits 

Transmission Efficiency: move highest possible volume to accurate information through the network

MAC address filtering will create a list of MAC addresses are allowed to connect to wife or switch in corporate networks, MAC address spooing is software-enables technique to change hardcoded MAC addresses

ARP tables map IP addresses to MAC addresses within local network







































