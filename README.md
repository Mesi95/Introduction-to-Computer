# Introduction-to-Computer

# What are transistors?
A transistor is a semiconductor that regulates or controls current or voltage flow. It also used as an amplifier or switch for the electrical signals

# Moor’s law
Moore's law is the observation that the number of transistors in a dense integrated circuit (IC) doubles about every two years. Moore's law is to guide long-term planning and to set targets for research and development.

# Lambda calculus
Lambda calculus (λ-calculus) is a formal system in mathematical logic and computer science for expressing computation by way of variable binding and substitution. It captures the features of a wide variety of programming languages.

# How computers work
A computer regards any information as binary ones and zeros. This information are sent as electrical pulses in circuits. <br>Computer has input, processor and output. The processor has three parts the CPU, Memory and Motherboard.

# HTTP & HTTPS

## The Hypertext Transfer Protocol (HTTP) 
HTTP is the foundation of the World Wide Web, and is used to load web pages using hypertext links.

## Hypertext transfer protocol secure (HTTPS)
HTTPS is the secure version of HTTP, which is the primary protocol used to send data between a web browser and a website. HTTPS is encrypted in order to increase security of data transfer.

# DNS

The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like facebook.com or aau.edu.et. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

# What is SSL & TLS

## SSL stands for Secure Sockets Layer 
It's the standard technology for keeping an internet connection secure and safeguarding any sensitive data that is being sent between two systems, preventing criminals from reading and modifying any information transferred, including potential personal details. The two systems can be a server and a client (for example, a shopping website and browser) or server to server (for example, an application with personal identifiable information or with payroll information). It does this by making sure that any data transferred between users and sites, or between two systems remain impossible to read. It uses encryption algorithms to scramble data in transit, preventing hackers from reading it as it is sent over the connection. This information could be anything sensitive or personal which can include credit card numbers and other financial information, names and addresses.

## TLS (Transport Layer Security)
It is just an updated, more secure, version of SSL. We still refer to our security certificates as SSL because it is a more commonly used term, but when you are buying SSL from DigiCert you are actually buying the most up to date TLS certificates with the option of ECC, RSA or DSA encryption.

# What is the OSI Model?
The open systems interconnection (OSI) model is a conceptual model created by the International Organization for Standardization which enables diverse communication systems to communicate using standard protocols. In plain English, the OSI provides a standard for different computer systems to be able to communicate with each other.

![](https://github.com/Mesi95/Introduction-to-Computer/blob/main/OSI-7-layers.jpg)

# The 7 Layers of the OSI Model

## Physical Layer 
The lowest layer of the OSI Model is concerned with electrically or optically transmitting raw unstructured data bits across the network from the physical layer of the sending device to the physical layer of the receiving device. It can include specifications such as voltages, pin layout, cabling, and radio frequencies. At the physical layer, one might find “physical” resources such as network hubs, cabling, repeaters, network adapters or modems.

## Data Link Layer
At the data link layer, directly connected nodes are used to perform node-to-node data transfer where data is packaged into frames. The data link layer also corrects errors that may have occurred at the physical layer. The data link layer encompasses two sub-layers of its own. The first, media access control (MAC), provides flow control and multiplexing for device transmissions over a network. The second, the logical link control (LLC), provides flow and error control over the physical medium as well as identifies line protocols.

## Network Layer
The network layer is responsible for receiving frames from the data link layer, and delivering them to their intended destinations among based on the addresses contained inside the frame. The network layer finds the destination by using logical addresses, such as IP (internet protocol). At this layer, routers are a crucial component used to quite literally route information where it needs to go between networks.

## Transport Layer
The transport layer manages the delivery and error checking of data packets. It regulates the size, sequencing, and ultimately the transfer of data between systems and hosts. One of the most common examples of the transport layer is TCP or the Transmission Control Protocol.

## Session Layer
The session layer controls the conversations between different computers. A session or connection between machines is set up, managed, and termined at layer 5. Session layer services also include authentication and reconnections.

## Presentation Layer
The presentation layer formats or translates data for the application layer based on the syntax or semantics that the application accepts. Because of this, it at times also called the syntax layer. This layer can also handle the encryption and decryption required by the application layer.

## Application Layer
At this layer, both the end user and the application layer interact directly with the software application. This layer sees network services provided to end-user applications such as a web browser or Office 365. The application layer identifies communication partners, resource availability, and synchronizes communication.

# What is DHCP and how does it work?
A DHCP Server is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. It relies on the standard protocol known as Dynamic Host Configuration Protocol or DHCP to respond to broadcast queries by clients.

When a device wants access to a network that’s using DHCP, it sends a request for an IP address that is picked up by a DHCP server. The server responds be delivering an IP address to the device, then monitors the use of the address and takes it back after a specified time or when the device shuts down. The IP address is then returned to the pool of addresses managed by the DHCP server to be reassigned to another device as it seeks access to the network. While the delegation of IP addresses is the central function of the protocol, DHCP also assigns a variety of related networking parameters including subnet mask, default gateway address, and domain name server (DNS). DHCP is an IEEE standard built on top of the older BOOTP (bootstrap protocol), which has become obsolete because it only works on IPv4 networks.

# What Is a Firewall?
A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

## Software Firewall:
A software firewall is a special type of computer software that runs on a computer/server. Its main purpose is to protect your computer/server from outside attempts to control or gain access and depending on your choice of a software firewall. A software firewall can also be configured for checking any suspicious outgoing requests. 

## Hardware Firewall:
It is physical piece of equipment planned to perform firewall duties. A hardware firewall can be a computer or a dedicated piece of equipment which serve as a firewall. Hardware firewall are incorporated into the router that is situated between the computer and the internet gateway. 

### Difference between Hardware and Software firewall:

| Parameters  | Software Firewall  | Hardware Firewall |
| :------------ |:---------------:| :---------------:|
| Operates on    | A software Firewall operates on the system. | Hardware Firewall do not operate on the system. |
| Configuration      | Configuration of a software firewall is easy. |   Configuration of hardware firewall is not easy. |
| Working | It is required to install the device between the computer and the Internet so that it will not be easily accessible. The installation requires a connection of network cable with the firewall rather than directly connecting to the router. Hence, a barrier is formed for blocking the incoming and outgoing data packets between the network and the Internet. It protects against viruses, malware, spyware, email spam, and other similar attacks from outside.|  It is installed on individual devices like computes and phones which results in blocking users or devices from accessing the individual components of the network. It basically inspects the packets and then blocks the unauthorized access. |
| Cost |It is less expensive to install though the cost may increase in case of variation in computers.| It is more expensive than a software firewall as an initial investment is required based on the protection level.|
| Flexibility | It is flexible i.e., you can choose which application has to be installed.| It is not flexible like software firewall.|
| Installation | It is installed inside the individual system.  | It is installed outside the system.|
| Protects | It protects one system at a time and is not enabled for smart TVs, gaming consoles, and other devices.| It protects a whole network at a time.|
| Performance | It makes the performance of computers slows down.| It doesn’t affect the performance of the computer.|
| Requirement | It is needed to be installed on every individual system on a network.| It needs only one hardware to be installed for a whole network. |
| Blocking | In software firewall, content based on keywords can be blocked.| A domain or website can be blocked using hardware firewall. |
