## OSI Model
 - It stands for Open System Interconnection Model and was the first model used for network communication. 

 - It allows two systems to communicate regardless of their underlying architecture.

So, the question is - Is it a Protocol?

No, It is not a Protocol; It is a tool for understanding and designing a network architecture that is flexible and robust.

It consists of seven separate but related layers that computer systems use to communicate over the internet.

Once you learn about the OSI Model, you'll have a better understanding of how the internet works.

We'll learn about these layers from top to down i.e. from the Application layer that directly serves the users, down to the physical layer. 

We know that when two systems communicate, one acts as a sender and the other as a receiver. 

The flow of data at both of these ends can be seen in this image.

So for each layer, we'll learn what it does at the sender's and receiver's ends. let's begin -

<br>

### Application Layer

- In this layer, the data is present in a visual form that the user can understand & interact with.

- The application layer is used by end-user software such as web browsers.
- It provides various protocols that are required to be followed while sending and receiving data. 
- Some of the application layer protocols are HTTP(Hypertext Transfer Protocol), FTP(File Transfer Protocol), POP(Post Office Protocol), Simple Mial Transfer Protocol(SMTP), and DNS(Domain Name System).

### Presentation Layer 

- **At sender's end-** The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

- **At the receiver's end** The presentation layer prepares data for the application layer. 

It defines how two devices should encode, encrypt, and compress data so it is received correctly on the other end.

### Session Layer

- The session layer creates a communication channel between two devices.

- It is responsible for the establishment of connection, and maintenance of a session and it also ensures security.

- **At sender's end & receiver's end** It is responsible for opening the sessions, ensuring they remain open and functional while data is being transferred, and closing them when data is transferred.

- It can also set checkpoints during data transfer so that if a session is interrupted, devices can resume data transfer from the last checkpoint.

### Transport Layer

- **At sender's end** The transport layer takes the data transferred by the session layer and breaks it into smaller data units called "segments".

- **At the receiver's end** It is responsible for reassembling those segments i.e. turning back into the data that can be used by the session layer.

- The transport layer carries out flow control, which means sending data at the rate that matches the connection speed of receiving device.

- It also carries out error control, It means checking if the data was received correctly and if not then requested to send it again.

### Network Layer

- **At sender's end** It is responsible for breaking up the segments sent by the transport layer into even smaller data units called packets.

- **At the receiver's end** It is responsible for reassembling those packets to transmit them to the transport layer.

- This layer is also responsible for routing these packets which means discovering the best path across the physical network.

- It uses an IP address to route packets to the destination node.

### Data Link Layer

- The Data link layer is responsible for the node-to-node delivery of the message.

- **At sender's end-** It receives the data from the network layer and divides it into manageable units called frames. 

- **At the receiver's end** It is responsible for reassembling those frames to transmit them to the network layer.

- It provides the addressing information of the sender's and receiver's frames by adding a header to each frame.

- The main function of this layer is to make sure that data transfers error-free from one node to another.

### Physical Layer

- The physical layer is responsible for the physical cable or wireless connection between network nodes.

- It contains information in the form of bits. It is responsible for transmitting individual bits from one node to another.

- When receiving data, this layer will get the data and convert it into 0's and 1's and send them to the data link layer, which will put the frame back together.

So, This is what the OSI Model is. It is a reference model and is not implemented on the internet. The internet is based on the simpler TCP/IP model.





