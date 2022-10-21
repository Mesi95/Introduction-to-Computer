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

# What is Register?

A processor register (CPU register) is one of a small set of data holding places that are part of the computer processor.

A register may hold an instruction, a storage address, or any kind of data (such as a bit sequence or individual characters). Some instructions specify registers as part of the instruction.

## Types of Register

In Computer Organisation, the register is utilized to acknowledge, store, move information and directions that are being utilized quickly by the CPU. There are different kinds of registers utilized for different reasons. Some of the commonly used registers are:

* AC ( accumulator )
* DR ( Data registers )
* AR ( Address registers )
* PC ( Program counter )
* MDR ( Memory data registers )
* IR ( index registers )
* MBR ( Memory buffer registers )

These registers are utilized for playing out the different operations. When we perform some operations, the CPU utilizes these registers to perform the operations. When we provide input to the system for a certain operation, the provided information or the input gets stored in the registers. Once the ALU arithmetic and logical unit process the output, the processed data is again provided to us by the registers.

The sole reason for having a register is the quick recovery of information that the CPU will later process. The CPU can use RAM over the hard disk to retrieve the memory, which is comparatively a much faster option, but the speed retrieved from RAM is still not enough. Therefore, we have catch memory, which is faster than registers. These registers work with CPU memory like catch and RAM to complete the task quickly.

# What is Virtualization?

Virtualization is the process of running a virtual instance of a computer system in a layer abstracted from the actual hardware. Most commonly, it refers to running multiple operating systems on a computer system simultaneously. To the applications running on top of the virtualized machine, it can appear as if they are on their own dedicated machine, where the operating system, libraries, and other programs are unique to the guest virtualized system and unconnected to the host operating system which sits below it.

There are many reasons why people utilize virtualization in computing. To desktop users, the most common use is to be able to run applications meant for a different operating system without having to switch computers or reboot into a different system. For administrators of servers, virtualization also offers the ability to run different operating systems, but perhaps, more importantly, it offers a way to segment a large system into many smaller parts, allowing the server to be used more efficiently by a number of different users or applications with different needs. It also allows for isolation, keeping programs running inside of a virtual machine safe from the processes taking place in another virtual machine on the same host.

# What is a Virtual Machine?

A virtual machine is the emulated equivalent of a computer system that runs on top of another system. Virtual machines may have access to any number of resources: computing power, through hardware-assisted but limited access to the host machine's CPU and memory; one or more physical or virtual disk devices for storage; a virtual or real network inferface; as well as any devices such as video cards, USB devices, or other hardware that are shared with the virtual machine. If the virtual machine is stored on a virtual disk, this is often referred to as a disk image. A disk image may contain the files for a virtual machine to boot, or, it can contain any other specific storage needs.

# What is an Operating System?
An operating system is the most important software that runs on a computer. It manages the computer's memory and processes, as well as all of its software and hardware. It also allows you to communicate with the computer without knowing how to speak the computer's language. Without an operating system, a computer is useless.

## The operating system's job
Your computer's operating system (OS) manages all of the software and hardware on the computer. Most of the time, there are several different computer programs running at the same time, and they all need to access your computer's central processing unit (CPU), memory, and storage. The operating system coordinates all of this to make sure each program gets what it needs.

## Types of operating systems
Operating systems usually come pre-loaded on any computer you buy. Most people use the operating system that comes with their computer, but it's possible to upgrade or even change operating systems. The three most common operating systems for personal computers are Microsoft Windows, macOS, and Linux.

Modern operating systems use a graphical user interface, or GUI (pronounced gooey). A GUI lets you use your mouse to click icons, buttons, and menus, and everything is clearly displayed on the screen using a combination of graphics and text.

Each operating system's GUI has a different look and feel, so if you switch to a different operating system it may seem unfamiliar at first. However, modern operating systems are designed to be easy to use, and most of the basic principles are the same.

# Native Apps, Web Apps, and Hybrid Apps

Native and hybrid apps are installed in an app store, whereas web apps are mobile-optimized webpages that look like an app. Both hybrid and web apps render HTML web pages, but hybrid apps use app-embedded browsers to do that.

## Native Apps
Native apps live on the device and are accessed through icons on the device home screen. Native apps are installed through an application store (such as Google Play or Apple’s App Store). They are developed specifically for one platform, and can take full advantage of all the device features — they can use the camera, the GPS, the accelerometer, the compass, the list of contacts, and so on. They can also incorporate gestures (either standard operating-system gestures or new, app-defined gestures). And native apps can use the device’s notification system and can work offline.

## Mobile Web Apps
Web apps are not real applications; they are really websites that, in many ways, look and feel like native applications, but are not implemented as such. They are run by a browser and typically written in HTML5. Users first access them as they would access any web page: they navigate to a special URL and then have the option of “installing” them on their home screen by creating a bookmark to that page.

## Hybrid apps
Hybrid apps are part native apps, part web apps. (Because of that, many people incorrectly call them “web apps”). Like native apps, they live in an app store and can take advantage of the many device features available. Like web apps, they rely on HTML being rendered in a browser, with the caveat that the browser is embedded within the app.

# What is Java?
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let programmers write once, run anywhere ,meaning that compiled Java code can run on all platforms that support Java without the need to recompile. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages.
