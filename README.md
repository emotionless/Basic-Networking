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

# Questions
* Understand what the different address classes (A, B, C), know what the private network addresses are used for, what local and broadcast addresses are.
* Understand the role of ports in TCP, standard and non-standard port ranges and know common standard ports for commonly used protocols.
* Know the basic difference between IPv4 and IPv6 addressing.
* Understand how a firewall works. Difference between "whitelisting" and "blacklisting", port forwarding, Network Address Translation and basic network security * concepts like IP range blocking.
* Have an understanding of how routing works on the Internet.
* Beyond TCP/IP, understanding how SSL work, various telecommunications networks and circuits (i.e. T1, T2, OC-192, etc), different application protocol transports like ATM and MQ-style messaging.



