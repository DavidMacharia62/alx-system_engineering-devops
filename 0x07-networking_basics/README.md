# OSI Model and Networking

The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a communication system into seven different layers. These layers define how information is transmitted and received between devices in a network.

The OSI model consists of the following layers:
1. Physical Layer: Deals with the physical transmission of data over a network, such as electrical or optical signals.
2. Data Link Layer: Manages the reliable transmission of data frames between devices on the same network.
3. Network Layer: Handles the routing of data packets across different networks by assigning logical addresses.
4. Transport Layer: Provides end-to-end communication and ensures the reliable delivery of data between applications.
5. Session Layer: Establishes, manages, and terminates sessions between applications.
6. Presentation Layer: Converts data into a suitable format for transmission and handles encryption and compression.
7. Application Layer: Provides services and protocols for application-level functions, such as file transfer and email.

## LAN

A LAN (Local Area Network) is a network that connects devices within a limited geographic area, typically in a single building or campus. It allows for the sharing of resources and data between connected devices.

Typical usage of LANs includes connecting computers, printers, servers, and other devices in a home or office environment to facilitate local communication and resource sharing.

The typical geographical size of a LAN is relatively small, covering areas such as a single room, building, or campus.

## WAN

A WAN (Wide Area Network) is a network that spans a large geographic area, often connecting multiple LANs together. It allows for long-distance communication between devices and is typically provided by service providers.

Typical usage of WANs includes connecting geographically dispersed offices or networks, enabling communication and data transfer between them.

The geographical size of a WAN can vary greatly, ranging from regional networks covering a city or country to global networks connecting different continents.

## INTERNET

The Internet is a global network of interconnected networks that spans the entire globe. It is a collection of millions of computers and other devices connected together, allowing for the exchange of information and services across the world.

## IP ADDRESS

An IP address (Internet Protocol address) is a unique numerical identifier assigned to each device connected to a network. It is used for communication and identification purposes in the IP network layer.

There are two types of IP addresses: IPv4 (Internet Protocol version 4) and IPv6 (Internet Protocol version 6). IPv4 addresses are 32-bit numbers, typically written in the format xxx.xxx.xxx.xxx (e.g., 192.168.0.1). IPv6 addresses are 128-bit numbers, written in a hexadecimal format (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

"localhost" is a hostname that refers to the current device or the loopback network interface. It is often used to access the network services running on the same device.

A subnet is a logical division of an IP network, created by dividing the network into smaller subnetworks. It allows for efficient addressing and management of devices within a network.

IPv6 was created due to the depletion of available IPv4 addresses. With the rapid growth of the Internet and the increasing number of connected devices, IPv4 addresses became scarce. IPv6 was introduced to provide a larger address space and accommodate the growing number of devices.

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two commonly used protocols for data transfer over IP networks.

The main difference between TCP and UDP is their approach to reliability and ordering of data. TCP provides reliable, connection-oriented communication with error-checking, flow control, and retransmission of lost packets. UDP, on the other hand, provides unreliable, connectionless communication without guaranteed delivery or ordering. UDP is often used for real-time applications or scenarios where speed is prioritized over reliability.

A port is a numerical identifier used to differentiate between different network services or processes running on a device. It helps direct incoming network traffic to the appropriate application or service.

The port numbers for SSH (Secure Shell), HTTP (Hypertext Transfer Protocol), and HTTPS (Hypertext Transfer Protocol Secure) are as follows:
- SSH: Port 22
- HTTP: Port 80
- HTTPS: Port 443

The tool/protocol often used to check if a device is connected to a network is ICMP (Internet Control Message Protocol) Echo Request, commonly known as "ping." By sending an ICMP Echo Request message to a specific IP address, one can determine if the device is reachable and responsive on the network.
