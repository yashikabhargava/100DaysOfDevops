## Network Protocol

A protocol is a set of rules for formatting and processing data. The computers within a network may use vastly different software and hardware; however, Protocols enable them to communicate with each other.

There are different protocols for different types of processes. Protocols are often discussed in terms of which OSI model layer they belong to.

We have already learned about the OSI model, but let's review it again -

<img src="img\osi.PNG">

Now Let's Learn about some of the protocols used by different layers to accomplish user requests. 

## Application Layer Protocols

### HTTP: Hyper Text Transfer Protocol

It is a client-server protocol. It tells us how the client requests the data from the server (HTTP Request) and how the server sends back the data to the client (HTTP Response). HTTP uses TCP inside it. TCP makes sure that all the data is received or not. It is a part of the Application Layer.

HTTP is a stateless protocol, meaning the client and server are only aware of each other while the connection between them is intact. After that, both the client and server forget about each other's existence. Due to this phenomenon, the client and server can't both retain information between requests.

HTTP Method means telling the server what to do. The most commonly used methods are

    GET- You are requesting data
    PUT- Puts data at a specific location
    POST- The client gives some data to the server like web forms
    DELETE- Deletes data from the server

### DHCP: Dynamic Host Configuration Protocol

DHCP is a communication protocol that enables network administrators to automate the assignment of IP addresses in a network. In an IP network, every device connecting to the internet requires a unique IP. DHCP lets network admins distribute IP addresses from a central point and automatically send a new IP address when a device is plugged in from a different place in the network. DHCP works on a client-server model.

### DNS: Domain Name System protocol

The DNS protocol helps in translating or mapping host names to IP addresses. DNS works on a client-server model and uses a distributed database over a hierarchy of name servers.

Hosts are identified based on their IP addresses, but memorizing an IP address is difficult due to its complexity. IPs are also dynamic, making it all the more necessary to map domain names to IP addresses. DNS helps resolve this issue by converting the domain names of websites into numerical IP addresses.

### FTP: File Transfer Protocol

File Transfer Protocol enables file sharing between hosts, both local and remote, and runs on top of TCP. For file transfer, FTP creates two TCP connections: control and data connection. The control connection is used to transfer control information like passwords, commands to retrieve and store files, etc., and the data connection is used to transfer the actual file. Both of these connections run in parallel during the entire file transfer process.

### SMTP: Simple Mail Transfer Protocol

SMTP is a protocol designed to transfer electronic mail reliably and efficiently. SMTP is a push protocol and is used to send emails, whereas POP and IMAP are used to retrieve emails on the end user's side. SMTP transfers emails between systems and notifies of incoming emails. Using SMTP, a client can transfer an email to another client on the same network or another network through a relay or gateway access available to both networks.

### POP and POP3: Post Office Protocol (version 3)

The Post Office Protocol is also an email protocol. Using this protocol, the end user can download emails from the mail server to their email client. Once the emails are downloaded locally, they can be read without an internet connection. Also, once the emails are moved locally, they get deleted from the mail server, freeing up space. POP3 is not designed to perform extensive manipulations with the messages on the mail server, unlike IMAP4. POP3 is the latest version of the Post Office Protocol.


## Transport layer network protocols

### TCP: Transmission Control Protocol

TCP is a transport layer protocol that provides a reliable stream delivery and virtual connection service to applications through the use of sequenced acknowledgement. TCP is a connection-oriented protocol, as it requires a connection to be established between applications before data transfer. Through flow control and acknowledgement of data, TCP provides extensive error checking. TCP ensures the sequencing of data, meaning the data packets arrive in order at the receiving end. Retransmission of lost data packets is also feasible with TCP.


### UDP: User Datagram Protocol

UDP is a connection-less transport layer protocol that provides a simple but unreliable message service. Unlike TCP, UDP adds no reliability, flow control, or error recovery functions. UDP is useful in situations where the reliability mechanisms of TCP are not necessary. Retransmission of lost data packets isn't possible with UDP.

## Network layer protocols

### IP: Internet Protocol (IPv4)

IPv4 is a network layer protocol that contains addressing and control information, which helps packets be routed in a network. IP works in tandem with TCP to deliver data packets across the network. Under IP, each host is assigned a 32-bit address comprised of two major parts: the network number and host number. The network number identifies a network and is assigned by the internet, while the host number identifies a host on the network and is assigned by a network admin. The IP is only responsible for delivering the packets, and TCP helps puts them back in the right order.

### IPv6: Internet Protocol version 6

IPv6 is the latest version of the Internet Protocol, a network layer protocol that possesses addressing and control information for enabling packets to be routed in the network. IPv6 was created to deal with IPv4 exhaustion. It increases the IP address size from 32 bits to 128 bits to support more levels of addressing.

## Data link layer network protocols

### ARP: Address Resolution Protocol

The Address Resolution Protocol helps map IP addresses to physical machine addresses (or a MAC address for Ethernet) recognized in the local network. A table called an ARP cache is used to maintain a correlation between each IP address and its corresponding MAC address. ARP offers the rules to make these correlations and helps convert addresses in both directions.

## Resources -

- [Computer Networking Course - Kunal Kushwaha](https://www.youtube.com/watch?v=IPvYjXCsTg8&t=7s)

- https://www.manageengine.com/network-monitoring/network-protocols.html

- https://www.cloudflare.com/learning/network-layer/what-is-a-protocol/