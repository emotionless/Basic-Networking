## Questions
[All questions from quora](https://www.quora.com/What-are-the-basic-networking-concepts-tools-questions-that-I-should-cover-before-a-software-engineering-interview)
### How the TCP/IP protocols work?

Transmission Control Protocol (TCP)
> [TCP/IP by Titas](https://www.youtube.com/watch?v=OXUzJb6AeGk&ab_channel=TitasSarker)

> [How TCP/IP Works](https://www.avast.com/c-what-is-tcp-ip#topic-1)


## What does Port 80 mean?
* Port 80 is the port number assigned to commonly used internet communication protocol, Hypertext Transfer Protocol (HTTP). It is the port from which a computer sends and receives Web client-based communication and messages from a Web server and is used to send and receive HTML pages or data (unencrypted or plain data).

## What is the Port 443?
* The Port 443, a web browsing port, is primarily used for HTTPS services. It is another type of HTTP that provides encryption and transport over secure ports. In some security-demanding sites, such as banking, securities, shopping, etc., are using HTTPS service, so that the exchange of information on these sites, other people captured packets obtained is encrypted data to ensure the security of transactions.

## Difference between TCP and UDP
[TCP vs UDP](https://www.guru99.com/tcp-vs-udp-understanding-the-difference.html)

## How does DNS work?
[youtube](https://www.youtube.com/watch?v=mpQZVYPuDGU)

[IP classes](https://www.meridianoutpost.com/resources/articles/IP-classes.php)

## Understand the role of ports in TCP, standard and non-standard port ranges and know common standard ports for commonly used protocols.
[Ports](https://www.ionos.com/digitalguide/server/know-how/tcp-ports-and-udp-ports)

[Registered Ports](https://www.sciencedirect.com/topics/computer-science/registered-port)

## Know the basic difference between IPv4 and IPv6 addressing.
### KEY DIFFERENCE
* IPv4 is 32-Bit IP address whereas IPv6 is a 128-Bit IP address.
* IPv4 is a numeric addressing method whereas IPv6 is an alphanumeric addressing method.
* IPv4 binary bits are separated by a dot(.) whereas IPv6 binary bits are separated by a colon(:).
* IPv4 offers 12 header fields whereas IPv6 offers 8 header fields.
* IPv4 supports broadcast whereas IPv6 doesn’t support broadcast.
* IPv4 has checksum fields while IPv6 doesn’t have checksum fields
* IPv4 supports VLSM (Virtual Length Subnet Mask) whereas IPv6 doesn’t support VLSM.
* IPv4 uses ARP (Address Resolution Protocol) to map to MAC address whereas IPv6 uses NDP (Neighbour Discovery Protocol) to map to MAC address.

#### Features of IPv4
* Connectionless Protocol
* Allow creating a simple virtual communication layer over diversified devices
* It requires less memory, and ease of remembering addresses
* Already supported protocol by millions of devices
* Offers video libraries and conferences

#### Features of IPv6
* Hierarchical addressing and routing infrastructure
* Stateful and Stateless configuration
* Support for quality of service (QoS)
* An ideal protocol for neighboring node interaction

## Understand how a firewall works
Firewalls are software or hardware that work as a filtration system for the data attempting to enter your computer or network. Firewalls scan packets for malicious code or attack vectors that have already been identified as established threats. Should a data packet be flagged and determined to be a security risk, the firewall prevents it from entering the network or reaching your computer. 

## What is Network Address Translation
To access the Internet, one public IP address is needed, but we can use a private IP address in our private network. The idea of NAT is to allow multiple devices to access the Internet through a single public address. To achieve this, the translation of private IP address to a public IP address is required. Network Address Translation (NAT) is a process in which one or more local IP address is translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts. Also, it does the translation of port numbers i.e. masks the port number of the host with another port number, in the packet that will be routed to the destination. It then makes the corresponding entries of IP address and port number in the NAT table. NAT generally operates on router or firewall.

## Basic Network security
Backup, Firewall/router, content filtering, Operating System Updates,  Other software updates, Who is an Administrator, Anti-Virus/Anti Malware software.  

## How routing works on the Internet
Routers refer to internal routing tables to make decisions about how to route packets along network paths. A routing table records the paths that packets should take to reach every destination that the router is responsible for. Think of train timetables, which train passengers consult to decide which train to catch. Routing tables are like that, but for network paths rather than trains.

Routers work in the following way: when a router receives a packet, it reads the headers* of the packet to see its intended destination, like the way a train conductor may check a passenger's tickets to determine which train they should go on. It then determines where to route the packet based on information in its routing tables.

Routers do this millions of times a second with millions of packets. As a packet travels to its destination, it may be routed several times by different routers.

Routing tables can either be static or dynamic. Static routing tables do not change. A network administrator manually sets up static routing tables. This essentially sets in stone the routes data packets take across the network, unless the administrator manually updates the tables.

Dynamic routing tables update automatically. Dynamic routers use various routing protocols (see below) to determine the shortest and fastest paths. They also make this determination based on how long it takes packets to reach their destination — similar to the way Google Maps, Waze, and other GPS services determine the best driving routes based on past driving performance and current driving conditions.

Dynamic routing requires more computing power, which is why smaller networks may rely on static routing. But for medium-sized and large networks, dynamic routing is much more efficient.

* [How does routing work](https://www.cloudflare.com/learning/network-layer/what-is-routing/)
* [Internet routing protocol - best](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:routing-with-redundancy/a/internet-routing)

## What is an SSL Certificate?
SSL stands for Secure Sockets Layer and, in short, it's the standard technology for keeping an internet connection secure and safeguarding any sensitive data that is being sent between two systems, preventing criminals from reading and modifying any information transferred, including potential personal details. The two systems can be a server and a client (for example, a shopping website and browser) or server to server (for example, an application with personal identifiable information or with payroll information).

It does this by making sure that any data transferred between users and sites, or between two systems remain impossible to read. It uses encryption algorithms to scramble data in transit, preventing hackers from reading it as it is sent over the connection. This information could be anything sensitive or personal which can include credit card numbers and other financial information, names and addresses.

TLS (Transport Layer Security) is just an updated, more secure, version of SSL. We still refer to our security certificates as SSL because it is a more commonly used term, but when you are buying SSL from DigiCert you are actually buying the most up to date TLS certificates with the option of ECC, RSA or DSA encryption.

HTTPS (Hyper Text Transfer Protocol Secure) appears in the URL when a website is secured by an SSL certificate. The details of the certificate, including the issuing authority and the corporate name of the website owner, can be viewed by clicking on the lock symbol on the browser bar.

## What is SSL?
SSL stands for Secure Sockets Layer, and it refers to a protocol for encrypting and securing communications that take place on the Internet. Although SSL was replaced by an updated protocol called TLS (Transport Layer Security) some time ago, "SSL" is still a commonly used term for this technology.

The main use case for SSL/TLS is securing communications between a client and a server, but it can also secure email, VoIP, and other communications over unsecured networks.

## How does SSL/TLS work?
These are the essential principles to grasp for understanding how SSL/TLS works:

Secure communication begins with a TLS handshake, in which the two communicating parties open a secure connection and exchange the public key
During the TLS handshake, the two parties generate session keys, and the session keys encrypt and decrypt all communications after the TLS handshake
Different session keys are used to encrypt communications in each new session
TLS ensures that the party on the server side, or the website the user is interacting with, is actually who they claim to be
TLS also ensures that data has not been altered, since a message authentication code (MAC) is included with transmissions
With TLS, both HTTP data that users send to a website (by clicking, filling out forms, etc.) and the HTTP data that websites send to users is encrypted. Encrypted data has to be decrypted by the recipient using a key.

## Different types of `Application` layer protocols
* Remote login to hosts: Telnet
* File transfer: File Transfer Protocol (FTP), Trivial File Transfer Protocol (TFTP)
* Electronic mail transport: Simple Mail Transfer Protocol (SMTP)
* Networking support: Domain Name System (DNS)
* Access data on the world wide web: HTTP, HTTPS
> [Application layer protocols details](https://gradeup.co/application-layer-protocols-dns-smtp-pop-ftp-http-i-ba1194bd-c5ab-11e5-9dcb-5849de73f8e1)

## The Advanced Message Queuing Protocol
Advanced Message Queuing Protocol (AMQP) is an application layer protocol that focuses on process-to-process([link](https://www.oreilly.com/library/view/java-message-service/9780596802264/ch04.html)) communication across IP networks. An encoding schema and a set of procedures allow for two different servers to communicate regardless of the technology used. Overall, the goal of AMQP is to enable message passing through broker services over TCP/IP connections. AMQP is considered a compact protocol, since it’s a binary protocol, meaning that everything sent over AMQP is binary data. A binary protocol avoids sending useless data over the wire.
> [Link](https://www.cloudamqp.com/blog/2019-11-21-what-is-amqp-and-why-is-it-used-in-rabbitmq.html)

## What is socket
Two processes that run on the same machine, or different machines, communicate through sockets. Sockets are seen as the end of the two-way communication between two processes; they allow processes to communicate with each other ​using a file descriptor and are commonly used in client-server applications that allow ​for ​communication between multiple applications.

## How sockets are created
A socket is created by concatenating the IP number of a system and a software port number (not a ​hardware port number). This allows the process to know the address of the system (the IP address) and the address where the information needs to be sent (the port number). The IP number and the port number are separated by a ​:.

Example: 192.168.1.25:8080

A socket consists of three things:
* An IP address
* A transport protocol
* A port number
A port is a number between 1 and 65535 inclusive that signifies a logical gate in a device. Every connection between a client and server requires a unique socket.

For example:

1030 is a port.

(10.1.1.2 , TCP , port 1030) is a socket.

## Protocols at Transport Layer
Three transport protocols are used in IMS:
* Transmission Control Protocol (TCP), 
* User Datagram Protocol (UDP),
* Stream Control Transmission Protocol ([SCTP](https://www.networkworld.com/article/2222277/what-about-stream-control-transmission-protocol--sctp--.html)).

## What is port number in computer network
A port number is a way to identify a specific process to which an Internet or other network message is to be forwarded when it arrives at a server. For the Transmission Control Protocol and the User Datagram Protocol, a port number is a 16-bit integer that is put in the header appended to a message unit.

> A port number is a 16-bit unsigned integer, thus ranging from 0 to 65535. For TCP, port number 0 is reserved and cannot be used, while for UDP, the source port is optional and a value of zero means no port.


# Questions
* Understand what the different address classes (A, B, C), know what the private network addresses are used for, what local and broadcast addresses are.
* Understand the role of ports in TCP, standard and non-standard port ranges and know common standard ports for commonly used protocols.
* Know the basic difference between IPv4 and IPv6 addressing.
* Understand how a firewall works. Difference between "whitelisting" and "blacklisting", port forwarding, Network Address Translation and basic network security * concepts like IP range blocking.
* Have an understanding of how routing works on the Internet.
* Beyond TCP/IP, understanding how SSL work, various telecommunications networks and circuits (i.e. T1, T2, OC-192, etc), different application protocol transports like ATM and MQ-style messaging.


## Key notes from algoExpert video:
* A packet during sending from a computer to another computer can contains at most 2^16 bytes. (64 KB)
### Latency
* Reading 1 MB from RAM : 250 μs (0.25 ms)
* Reading 1 MB from SSD : 1,000 μs (1 ms)
* Transfer 1 MB over Network : 10,000 μs (10 ms)
* Reading 1MB from HDD : 20,000 μs (20 ms)
* Inter-Continental Round Trip : 150,000 μs (150 ms)
### Throughput
The number of operations that a system can handle properly per time unit. For instance the throughput of a server can often be measured in requests per second (RPS or QPS).
