TCP is a Transmission Control Protocol. It is connection oriented protocol. The datas are sent as packets. Each packets have information about packet order. There is a header of 20 bytes in a TCP connection. When the server recieves the packets, they are arranged to meaningful data before sending to the application layer.

![[Pasted image 20210912083922.png]]

## Connection Process

1. At first, the client sens a syncronization block to the server.
2. The server recieves it and replies with a sync block with an acknowledgement.
3. The client recieves them and replies with an acknowledgement and thus a TCP connection is established.

## Features
 
- Packet Transmission
- Packets have order information
- Three way handshake
- Delivery Acknowledgement
- Retransmission of lost packet
- Ordered delivery
- Congestion control when traffic high/low.
