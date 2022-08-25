# Networking basics 
## OSI Model

* What it is
	OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

	

	Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.

* How many layers it has
	The OSI model has 7 levels
	

* How it is organized
It is organized from the lowest level to the highest level:

	* The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
	* The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc

## Types of Network
LAN connect local devices together, WAN connects LANs together, and WANs are operating over the Internet.

## LAN
* What is a LAN
A local area network (LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratory, university campus or office building.

Ethernet and Wi-Fi are the two most common technologies in use for local area networks. Historical network technologies include ARCNET, Token Ring, and AppleTalk.
* Typical usage
* Typical geographical size

## WAN

* What is a WAN
A wide area network (WAN) is a telecommunications network that extends over a large geographic area. Wide area networks are often established with leased telecommunication circuits.

* Typical usage
Businesses, as well as schools and government entities, use wide area networks to relay data to staff, students, clients, buyers and suppliers from various locations around the world. In essence, this mode of telecommunication allows a business to effectively carry out its daily function regardless of location. The Internet may be considered a WAN

* Typical geographical size
a large geographic area

## INTERNET

* What is the Internet
The Internet (or internet)[a] is the global system of interconnected computer networks that uses the Internet protocol suite (TCP/IP)[b] to communicate between networks and devices. It is a network of networks that consists of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies. The Internet carries a vast range of information resources and services, such as the inter-linked hypertext documents and applications of the World Wide Web (WWW), electronic mail, telephony, and file sharing.

* What is an IP address
For locating individual computers on the network, the Internet provides IP addresses. IP addresses are used by the Internet infrastructure to direct internet packets to their destinations. They consist of fixed-length numbers, which are found within the packet. IP addresses are generally assigned to equipment either automatically via DHCP, or are configured.
However, the network also supports other addressing systems. Users generally enter domain names (e.g. "en.wikipedia.org") instead of IP addresses because they are easier to remember, they are converted by the Domain Name System (DNS) into IP addresses which are more efficient for routing purposes.


* What are the 2 types of IP address
	* IP4
	Internet Protocol version 4 (IPv4) defines an IP address as a 32-bit number.IPv4 is the initial version used on the first generation of the Internet and is still in dominant use. It was designed to address up to ≈4.3 billion (109) hosts. However, the explosive growth of the Internet has led to IPv4 address exhaustion, which entered its final stage in 2011,when the global IPv4 address allocation pool was exhausted.
	* IP6
	Because of the growth of the Internet and the depletion of available IPv4 addresses, a new version of IP IPv6, was developed in the mid-1990s, which provides vastly larger addressing capabilities and more efficient routing of Internet traffic. IPv6 uses 128 bits for the IP address and was standardized in 1998. IPv6 deployment has been ongoing since the mid-2000s and is currently in growing deployment around the world, since Internet address registries (RIRs) began to urge all resource managers to plan rapid adoption and conversion

* What is localhost
localhost is a hostname that refers to the current device used to access it. It is used to access the network services that are running on the host via the loopback network interface. Using the loopback interface bypasses any local network interface hardware.

* What is a subnet
A subnetwork or subnet is a logical subdivision of an IP network.The practice of dividing a network into two or more networks is called subnetting.
Computers that belong to a subnet are addressed with an identical most-significant bit-group in their IP addresses. This results in the logical division of an IP address into two fields, the network number or routing prefix and the rest field or host identifier. The rest field is an identifier for a specific host or network interface.

* Why IPv6 was created
Because of the growth of the Internet and the depletion of available IPv4 addresses,


## TCP/UDP
TCP/IP is a suite of protocols used by devices to communicate over the Internet and most local networks. It is named after two of it’s original protocols—the Transmission Control Protocol (TCP) and the Internet Protocol (IP). TCP provides apps a way to deliver (and receive) an ordered and error-checked stream of information packets over the network.

The User Datagram Protocol (UDP) is used by apps to deliver a faster stream of information by doing away with error-checking. 

Both TCP and UDP are protocols used for sending bits of data—known as packets—over the Internet. Both protocols build on top of the IP protocol. In other words, whether you’re sending a packet via TCP or UDP, that packet is sent to an IP address. These packets are treated similarly, as they’re forwarded from your computer to intermediary routers and on to the destination.


* What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
* What is the main difference between TCP and UDP
* What is a port

*  SSH, HTTP and HTTPS port numbers
	* 22 for SSH
	* 80 for HTTP
	* 443 for HTTPS
* What tool/protocol is often used to check if a device is connected to a network

## MAC Address
Is a hardware address
Along with an IP address (which is networks software), there’s also a hardware address
it is tied to a key connection device in your computer called the network interface card, or NIC. The NIC is essentially a computer circuit card that makes it possible for your computer to connect to a network.

A NIC turns data into an electrical signal that can be transmitted over the network.

 the MAC address is sometimes referred to as a networking hardware address, the burned-in address (BIA), or the physical address. Here’s an example of a MAC address for an Ethernet NIC: 00:0a:95:9d:68:16.