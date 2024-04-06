# Author: Rebecca Childs
## Reading Notes:
### Lab 01

### What does “OSI” stand for?
OSI stands for Open Systems Interconnection.

### List the 7 layers of the OSI model and what each one is responsible for.
Physical Layer - The lowest layer of the OSI reference model. Responsible for the actual physical connection between the devices.
Data Link Layer - Responsible for the node-to-node delivery of the message. The main function of this layer is to make sure data transfer is error-free from one node to another, over the physical layer.
Network Layer - The network layer works for the transmission of data from one host to the other located in different networks.
Transport Layer - The transport layer provides services to the application layer and takes services from the network layer. Responsible for the end-to-end delivery of the complete message.
Session Layer - This layer is responsible for the establishment of connection, maintenance of sessions, and authentication, and also ensures security.
Presentation Layer - The presentation layer is also called the Translation layer. The data from the application layer is extracted here and manipulated as per the required format to transmit over the network. 
Application Layer - Network Virtual Terminal: It allows a user to log on to a remote host.
FTAM- File transfer access and management: This application allows a user to
access files in a remote host, retrieve files in a remote host, and manage or
control files from a remote computer.
Mail Services: Provide email service.
Directory Services: This application provides distributed database sources
and access for global information about various objects and services.


### Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?
Lower Layers (Hardware-Centric):
Physical Layer (Layer 1): This layer deals with the physical transmission of data, like cables, connectors, and network cards. It's primarily hardware-based.
Data Link Layer (Layer 2): This layer manages data transmission on a physical link, using hardware like network adapters for error detection and addressing. However, it also relies on software protocols for data framing.

Upper Layers (Software-Centric):
Network Layer (Layer 3): This layer handles routing data packets across networks. While routers are hardware, routing protocols are software.
Transport Layer (Layer 4): This layer ensures reliable data delivery between applications. It uses software protocols like TCP and UDP.
Session Layer (Layer 5): This layer establishes, manages, and terminates sessions between applications, primarily handled by software protocols.
Presentation Layer (Layer 6): This layer deals with data format presentation and encryption/decryption, involving both software protocols and some hardware acceleration features.
Application Layer (Layer 7): This layer provides network services to applications. It's purely software-based, with protocols like HTTP, FTP, and SMTP.

### How can the OSI model be used in troubleshooting?
Even though some layers lean more towards hardware or software, they work together. Hardware components like network cards and routers rely on software protocols to function effectively within the OSI framework. This layered approach ensures clear communication between devices and software applications regardless of the underlying hardware specifics.


### What is Wireshark?
Wireshark is a free and open-source network protocol analyzer. It's essentially a tool that captures and analyzes the data flowing across a network connection. Think of it like a microscope for your network traffic.

### What is a packet?
A packet refers to a single, self-contained unit of data that travels across a network. You can think of it as an envelope carrying information between devices on a network.

### What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?
Network Traffic Capture: Wireshark can capture all the data flowing across a specific network connection. Imagine it as eavesdropping on a conversation, but instead of voices, it's capturing digital information packets.

Packet Decoding and Analysis:  Once captured, Wireshark can break down these data packets and analyze their content. It reveals details like sender, receiver, protocols used (like TCP/IP), and potentially the data itself (though often encrypted).

Network Troubleshooting and Visibility: By combining capture and analysis, Wireshark provides a deep view of network activity. This helps diagnose issues like slowdowns, identify bottlenecks, and pinpoint where data might be getting lost.

Nefarious Uses:
Spying and Data Theft: Malicious actors can use Wireshark to capture sensitive information like usernames, passwords, or credit card details flowing unencrypted across a network. This can be a stepping stone for identity theft or financial fraud.
Network Intrusion Analysis: Hackers can leverage Wireshark to analyze network traffic patterns and identify vulnerabilities in network security protocols. This knowledge can be used to exploit those weaknesses and gain unauthorized access to systems.
Denial-of-Service (DoS) Attacks: By analyzing network traffic, attackers can identify critical points in a network and launch targeted DoS attacks to overwhelm those points and disrupt network functionality.

Benevolent Uses:
Network Troubleshooting: Network administrators use Wireshark to diagnose network problems. By analyzing captured packets, they can pinpoint where data is getting stuck, identify bottlenecks, and troubleshoot issues like slowdowns or connectivity problems.
Security Analysis: Security professionals use Wireshark to monitor network traffic for suspicious activity. They can identify potential malware infections, analyze intrusion attempts, and improve overall network security posture.
Software Development and Debugging: Developers can leverage Wireshark to understand how network protocols work and debug communication issues in their software. By analyzing captured packets, they can see how data is being exchanged between their application and other systems.

## Things I want to learn more about:
N/A
