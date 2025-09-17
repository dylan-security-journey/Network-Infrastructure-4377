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
