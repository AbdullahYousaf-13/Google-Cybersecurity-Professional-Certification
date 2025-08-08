# Connect and Protect: Networks and Network Security

## Description
**Connect and Protect: Networks and Network Security**, the third course in the Google Cybersecurity Certificate. You’re on an exciting journey!

By the end of this course, you will develop a greater understanding of network architecture, operations, intrusion tactics, common types of network vulnerabilities and attacks, and how to secure networks. You’ll also be introduced to common network protocols, firewalls, virtual private networks (VPNs), and system hardening practices. 

---

## Module 1: Network architecture
Five icons show the course followed by the four modules sequentially from left to right with module 1 highlighted.
You'll be introduced to network security and explain how it relates to ongoing security threats and vulnerabilities. You will learn about network architecture and mechanisms to secure a network.

<img width="538" height="160" alt="image" src="https://github.com/user-attachments/assets/353fb005-3632-4173-aec8-55499be7783d" />

---

## Module 2: Network operations 
Five icons show the course followed by the four modules sequentially from left to right with module 2 highlighted.
You will explore network protocols and how network communication can introduce vulnerabilities. In addition, you'll learn about common security measures, like firewalls, that help network operations remain safe and reliable.

<img width="539" height="156" alt="image" src="https://github.com/user-attachments/assets/aa42f110-9734-4e16-9d32-12ff764aeb5b" />

---

## Module 3: Secure against network intrusions
Five icons show the course followed by the four modules sequentially from left to right with module 3 highlighted.
You will understand types of network attacks and techniques used to secure compromised network systems and devices. You'll explore the many ways that malicious actors exploit vulnerabilities in network infrastructure and how cybersecurity professionals identify and close potential loopholes.

<img width="543" height="149" alt="image" src="https://github.com/user-attachments/assets/cd1c027a-22b7-4b98-8131-5c32bc129e06" />

---

## Module 4: Security hardening
Five icons show the course followed by the four modules sequentially from left to right with module 4 highlighted.
You will become familiar with network hardening practices that strengthen network systems. You'll learn how security hardening helps defend against malicious actors and intrusion methods. You'll also learn how to use security hardening to address the unique security challenges posed by cloud infrastructures.

<img width="539" height="157" alt="image" src="https://github.com/user-attachments/assets/373c7852-6105-4108-b807-3a3a7ec2b74e" />

---
---

## Module 1

### Network Devices
Network devices maintain information and services for users of a network. These devices connect over wired and wireless connections, sending data packets that contain information about the source and destination of the data.

<img width="783" height="360" alt="image" src="https://github.com/user-attachments/assets/a217c751-6aaf-4b2a-aa49-1ec74e3cd3a0" />

### Key Concepts
- **Network**: The overall infrastructure enabling device communication
- **Network Devices**: Specialized equipment (routers, switches) that manage network traffic
- **End-user Devices**: Computers, phones, etc. that connect via network devices

### Common Network Components

#### 1. End-user Devices
- Personal computers, laptops, mobile phones, tablets
- **Each has**:
  - Unique MAC address
  - IP address
  - Network interface for sending/receiving data
- **Connection methods**:
  - wired
  - wireless

<img width="611" height="363" alt="image" src="https://github.com/user-attachments/assets/30d34aa6-0eba-4bd0-9467-d16457fa83d5" />

#### 2. Firewalls
- Network security devices that monitor traffic
- First line of defense
- Can restrict specific incoming/outgoing traffic
- Typically positioned between internal networks and external/untrusted networks

<img width="757" height="221" alt="image" src="https://github.com/user-attachments/assets/69d0bdfd-7d53-420a-8e79-20b748c364a4" />

#### 3. Servers
- Provide information and services to client devices
- **Client-Server Model**:
  - Clients send requests
  - Servers perform requests
- **Examples**:
  - DNS servers
  - File servers
  - Mail servers

 <img width="336" height="232" alt="image" src="https://github.com/user-attachments/assets/b0f22c49-b23b-45e0-94c3-1757bcc9c90b" />

#### 4. Hubs and Switches
##### Hubs
- Basic connection points for network devices
- Broadcast data to all ports (security vulnerability)
- Primarily used in limited setups (e.g., home offices)

<img width="648" height="376" alt="image" src="https://github.com/user-attachments/assets/461c3a30-f068-4966-9ca0-1475810ab20b" />

##### Switches
- Intelligent traffic directors
- Forward packets only to intended devices
- Maintain MAC address tables
- **Benefits**:
  - Improved performance
  - Enhanced security
- Operate at Data Link Layer (TCP/IP model)

<img width="693" height="380" alt="image" src="https://github.com/user-attachments/assets/fbc77511-cd68-4b1f-81aa-e43821d4ff34" />

#### 5. Routers
- Connect different networks
- Direct traffic based on IP addresses
- **Features**:
  - Read IP headers
  - Forward packets toward destination
  - Often include firewall capabilities
- Operate at Network Layer (TCP/IP model)

<img width="732" height="176" alt="image" src="https://github.com/user-attachments/assets/88ddfc14-8dd7-4db3-af5f-48e5194262ef" />

#### 6. Modems and Wireless Access Points
##### Modems
- Connect to ISP
- Convert signals between ISP and local network
- Typically connect to routers

<img width="719" height="199" alt="image" src="https://github.com/user-attachments/assets/ec70ee49-0573-4e16-9727-8c5b56bd66fd" />

##### Wireless Access Points
- Create wireless networks via radio waves
- Use Wi-Fi standards for communication
- Enable wireless device connectivity

<img width="740" height="342" alt="image" src="https://github.com/user-attachments/assets/0eeea773-d704-4d77-b3d2-93912adc1022" />

### Network Diagrams
Visual representations of network architecture used by security professionals.

**Example Home Network Diagram**:

<img width="713" height="435" alt="image" src="https://github.com/user-attachments/assets/43897777-00e1-49ef-9ef6-bea9049693a8" />

---

### Cloud Computing and Software-Defined Networks

#### Introduction to Cloud Networks
- Extends traditional network concepts (LAN/WAN) to cloud environments
- Removes geographical limitations through virtualized infrastructure
- Rapid growth due to digital transformation

#### Cloud Computing Models

##### IaaS vs PaaS vs SaaS

| Service Model | Description                                              | Example Use               |
|---------------|----------------------------------------------------------|---------------------------|
| **IaaS**      | Virtual machines, storage, and networking managed by CSP | Hosting existing apps     |
| **PaaS**      | Platform for developers to build and deploy custom apps  | Web app development       |
| **SaaS**      | Software accessed via the internet                       | Google Workspace, Dropbox |

#### On-Premise vs. Cloud

| Characteristic     | On-Premise                  | Cloud                          |
|--------------------|-----------------------------|--------------------------------|
| **Location**       | Company-owned facilities    | Provider data centers          |
| **Maintenance**    | In-house IT team            | Managed by CSP                 |
| **Cost Model**     | Capital expenditure (CapEx) | Operational expenditure (OpEx) |
| **Scalability**    | Physical hardware limits    | Elastic resources              |

#### Hybrid & Multi-Cloud Environments
- **Hybrid Cloud**: Mix of on-premise + cloud infrastructure
- **Multi-Cloud**: Use of services from more than one CSP

#### Software-Defined Networking (SDN)
- Virtual equivalents of routers, switches, firewalls
- Controlled via software, APIs, and dashboards
- Improves agility, monitoring, and performance

#### Benefits of Cloud Computing & SDN
- **Reliability**: High availability, secure access
- **Cost**: No large upfront hardware investments
- **Scalability**: Elastic resource usage, pay-as-you-go model
- **Security**: Easily deploy firewalls, IDS/IPS, and WAFs

#### Key Takeaways
- CSPs offer scalable, reliable, and cost-effective compute, storage, and network services.
- SDNs enable dynamic and programmable networking like cloud systems.
- Organizations benefit from reduced complexity and faster provisioning.

#### More Info
- [Google Cloud](https://cloud.google.com)

---

### TCP/IP Model

#### What is the TCP/IP Model?
- Conceptual framework for data communication across networks.
- Helps visualize how data is transmitted and where issues may occur.
- Comprises 4 layers: **Application**, **Transport**, **Internet**, and **Network Access**.

<img width="536" height="373" alt="image" src="https://github.com/user-attachments/assets/75612767-07c1-4436-89fe-be74e6f3999e" />

#### TCP/IP Model Layers & Key Protocols

##### Application Layer
- Combines OSI’s application, presentation, and session layers.
- **Purpose**: Handles high-level protocols and user interaction.
- **Common Protocols**:
  - HTTP – Web browsing
  - FTP – File transfers
  - SMTP – Email sending
  - SSH – Secure remote access
  - DNS – Domain resolution

##### Transport Layer
- **Purpose**: Provides end-to-end communication and data transfer.
- **Key Protocols**:
  - **TCP (Transmission Control Protocol)**: Reliable, connection-based
  - **UDP (User Datagram Protocol)**: Faster, connectionless, used in streaming

##### Internet Layer
- **Purpose**: Determines routing and delivery of data across networks.
- **Key Protocols**:
  - **IP (Internet Protocol)** – Sends packets to correct destination
  - **ICMP (Internet Control Message Protocol)** – Error reporting, diagnostics (e.g., `ping`)

##### Network Access Layer (a.k.a. Data Link Layer)
- **Purpose**: Handles physical transmission of data and MAC addressing.
- **Key Protocols/Tools**:
  - **ARP** – Resolves IP to MAC addresses
  - Involves hardware like switches, cables, NICs

#### TCP/IP vs. OSI Model

| **OSI Model Layer**                    | **TCP/IP Equivalent Layer**  |
|----------------------------------------|------------------------------|
| Application, Presentation, Session     | Application                  |
| Transport                              | Transport                    |
| Network                                | Internet                     |
| Data Link, Physical                    | Network Access               |

- **OSI Model**: 7 layers, more detailed
- **TCP/IP Model**: 4 layers, widely used in real-world networking
- **TCP/IP is based on real protocols**, OSI is mostly theoretical

<img width="725" height="323" alt="image" src="https://github.com/user-attachments/assets/5385fde5-9e12-4b55-80a8-4038f8493f89" />

#### Key Takeaways
- TCP/IP is a practical model used in real-world networking.
- Each layer is responsible for specific parts of data communication.
- Understanding the model helps in troubleshooting and securing networks.
- OSI provides more granularity but TCP/IP is the dominant implementation standard.

---

### OSI Model

#### What is the OSI Model?
- OSI (Open Systems Interconnection) is a **7-layer model** for understanding network communication.
- Each layer represents a step in the process of moving data between networked systems.
- It complements the TCP/IP model but provides **more granularity**.

#### OSI Layers Explained (Layer 7 → Layer 1)

##### Layer 7: Application Layer
- **Purpose**: Directly interacts with end-user applications.
- **Protocols/Examples**:
  - HTTP/HTTPS – Web browsing
  - SMTP – Email
  - DNS – Domain name to IP resolution
- Handles user-generated data and requests.

##### Layer 6: Presentation Layer
- **Purpose**: Translates, encrypts, and compresses data for the application layer.
- **Examples**:
  - SSL/TLS – Encryption
  - Converts data formats for compatibility between systems

##### Layer 5: Session Layer
- **Purpose**: Manages sessions (open, maintain, close connections).
- **Functions**:
  - Authentication
  - Checkpointing
  - Session recovery after interruptions

##### Layer 4: Transport Layer
- **Purpose**: Provides reliable or unreliable delivery of data.
- **Key Protocols**:
  - **TCP** – Reliable, ordered, connection-oriented
  - **UDP** – Fast, connectionless, unordered
- **Functions**:
  - Segmentation and reassembly
  - Flow and error control

##### Layer 3: Network Layer
- **Purpose**: Determines how data is sent to the receiving device across multiple networks.
- **Key Protocols**:
  - **IP (Internet Protocol)** – Routing
- Data units at this layer are called **packets**.

##### Layer 2: Data Link Layer
- **Purpose**: Handles node-to-node delivery within the same network.
- **Components**:
  - Switches
  - Network Interface Cards (NICs)
- **Protocols**:
  - HDLC, NCP, SDLC

##### Layer 1: Physical Layer
- **Purpose**: Transfers raw bits (0s and 1s) over physical media.
- **Components**:
  - Cables, hubs, modems
  - Electrical signals or light pulses for transmission

#### Key Takeaways
- **OSI** is a detailed, layered framework for understanding how systems communicate over a network.
- **Each layer serves a distinct role** in ensuring reliable data transmission.
- **OSI and TCP/IP** are both useful depending on context:
  - **OSI** is better for teaching, troubleshooting
  - **TCP/IP** is used in real-world networking systems

---

### Components of Network Layer Communication

#### Operations at the Network Layer (Layer 3)
- The **Network Layer** is responsible for **addressing** and **delivering data packets** from the source host to the destination host across networks.
- Uses **IP addresses** for routing packets through multiple routers until they reach the final destination.
- IP addresses are stored in **routing tables** and found in the **IP header** of each packet.

#### What is an IP Packet?
- A **data packet** = unit of communication over a network.
- IP packets:
  - For **TCP**: often called **IP packets**
  - For **UDP**: often called **datagrams**
- All IP packets contain a **header** (with metadata) and **data** (the actual message).

#### IPv4 Packet Structure
An IPv4 packet consists of:
- **Header** (20–60 bytes): Contains control information.
- **Data**: Variable size, max total packet size = **65,535 bytes**

#### IPv4 Header Fields (13 total):

| **Field**                  | **Description**                                               |
|----------------------------|---------------------------------------------------------------|
| **Version (VER)**          | 4 bits – Indicates IPv4 protocol                              |
| **Header Length (IHL)**    | Defines where header ends and data begins                     |
| **Type of Service (ToS)**  | Prioritization info for routers                               |
| **Total Length**           | Size of entire packet (header + data)                         |
| **Identification**         | Uniquely identifies fragments of the same packet              |
| **Flags**                  | Indicates if the packet is fragmented                         |
| **Fragment Offset**        | Location of the fragment in original packet                   |
| **Time to Live (TTL)**     | Limits lifespan of a packet in network (prevents loops)       |
| **Protocol**               | Indicates which protocol (TCP, UDP, etc.) is used in the data |
| **Header Checksum**        | Used to detect corruption in the header                       |
| **Source IP Address**      | IP address of the sender                                      |
| **Destination IP Address** | IP address of the recipient                                   |
| **Options**                | Optional settings (used if IHL > 5)                           |

#### Packet Routing and TTL
- **Routers** use **IP headers** to determine where to forward packets.
- Each time a packet passes through a router, its **TTL is decreased by 1**.
- When TTL = 0, the packet is **discarded** to avoid infinite loops.

#### IPv4 vs IPv6

| **Feature**               | **IPv4**                               | **IPv6**                                        |
|---------------------------|----------------------------------------|-------------------------------------------------|
| **Address Format**        | Decimal, e.g., `192.168.0.1`           | Hexadecimal, e.g., `2001:0db8::ff21:0023:1234`  |
| **Address Length**        | 32 bits (4 bytes)                      | 128 bits (16 bytes)                             |
| **Total Addresses**       | ~4.3 billion                           | ~340 undecillion                                |
| **Header Complexity**     | More complex                           | Simplified                                      |
| **Security & Efficiency** | NAT required, potential collisions     | Built-in support for better routing & security  |

<img width="683" height="389" alt="image" src="https://github.com/user-attachments/assets/2fab50e1-4569-44ed-9a2d-c9f708672d62" />

**IPv6 Improvements:**
- Solves **IPv4 address exhaustion**
- Eliminates private address conflicts
- Introduces **Flow Label** for special handling
- Simpler header (removes fields like Identification, Flags, IHL)

## Key Takeaways
- The **network layer (Layer 3)** is critical for routing and addressing packets across networks.
- **IP headers** carry vital metadata like source/destination addresses and protocol info.
- Security professionals can analyze header data to:
  - Identify suspicious traffic origins
  - Understand protocol usage
  - Detect corrupted or malformed packets
- Understanding **IPv4 vs. IPv6** is essential for adapting to modern network architectures.

---

###Terms and Definitions – Course 3, Module 1

**Bandwidth**: The maximum data transmission capacity over a network, measured by bits per second

**Cloud computing**: The practice of using remote servers, application, and network services that are hosted on the internet instead of on local physical devices

**Cloud network**: A collection of servers or computers that stores resources and data in remote data centers that can be accessed via the internet

**Data packet**: A basic unit of information that travels from one device to another within a network

**Hub**: A network device that broadcasts information to every device on the network

**Internet Protocol (IP)**: A set of standards used for routing and addressing data packets as they travel between devices on a network

**Internet Protocol (IP) address**: A unique string of characters that identifies the location of a device on the internet

**Local Area Network (LAN)**: A network that spans small areas like an office building, a school, or a home

**Media Access Control (MAC) address**: A unique alphanumeric identifier that is assigned to each physical device on a network

**Modem**: A device that connects your router to the internet and brings internet access to the LAN

**Network**: A group of connected devices

**Open systems interconnection (OSI) model**: A standardized concept that describes the seven layers computers use to communicate and send data over the network

**Packet sniffing**: The practice of capturing and inspecting data packets across a network

**Port**: A software-based location that organizes the sending and receiving of data between devices on a network

**Router**: A network device that connects multiple networks together

**Speed**: The rate at which a device sends and receives data, measured by bits per second

**Switch**: A device that makes connections between specific devices on a network by sending and receiving data between them

**TCP/IP model**: A framework used to visualize how data is organized and transmitted across a network

**Transmission Control Protocol (TCP)**: An internet communication protocol that allows two devices to form a connection and stream data

**User Datagram Protocol (UDP)**: A connectionless protocol that does not establish a connection between devices before transmissions
**Wide Area Network (WAN)**: A network that spans a large geographic area like a city, state, or country

---
---

## Module 2

### Common Network Protocols  
Network protocols are sets of rules that govern communication between devices on a network. They define data structure, transmission order, and handling instructions.  

#### Categories of Network Protocols  
##### 1. Communication Protocols  
   - **TCP (Transmission Control Protocol)**: Ensures reliable, connection-based data transmission using a three-way handshake (SYN, SYN/ACK, ACK). Operates at the transport layer.  
   - **UDP (User Datagram Protocol)**: Connectionless protocol for fast transmissions (e.g., DNS queries). Less reliable than TCP. Transport layer.  
   - **HTTP (Hypertext Transfer Protocol)**: Application layer protocol for client-server communication (port 80). Insecure; often replaced by HTTPS.  
   - **DNS (Domain Name System)**: Translates domain names to IP addresses. Uses UDP (port 53) by default, switches to TCP for large replies. Application layer.  

##### 2. Management Protocols  
   - **SNMP (Simple Network Management Protocol)**: Monitors/manages network devices (e.g., bandwidth usage, configurations). Application layer.  
   - **ICMP (Internet Control Message Protocol)**: Reports transmission errors (e.g., `ping` command). Internet layer.  

##### 3. Security Protocols  
   - **HTTPS (HTTP Secure)**: Encrypts HTTP traffic using SSL/TLS (port 443). Application layer.  
   - **SFTP (Secure File Transfer Protocol)**: Encrypts file transfers via SSH (port 22). Uses AES encryption. Application layer.  

#### Key Takeaways  
- Protocols ensure standardized communication but may have vulnerabilities (e.g., DNS spoofing).  
- Security analysts must understand protocols to mitigate risks (e.g., enforcing HTTPS over HTTP).

---

### Additional Network Protocols  
This section covers essential protocols beyond basic communication, management, and security categories, including their port numbers and roles in network operations.  

#### Network Address Translation (NAT)  
- **Function**: Translates private IP addresses (LAN) to a public IP (WAN) for internet access.  
- **Layers**: Operates at TCP/IP layers 2 (Internet) and 3 (Transport).  
- **Private vs. Public IPs**:  
  - **Private**: Non-routable, free (e.g., `192.168.x.x`).  
  - **Public**: Routable, leased from ISPs (e.g., `8.8.8.8`).  

#### Dynamic Host Configuration Protocol (DHCP)  
- **Role**: Automatically assigns IPs, DNS, and gateway addresses to devices.  
- **Ports**:  
  - **Servers**: UDP 67  
  - **Clients**: UDP 68  
- **Layer**: Application (TCP/IP).  

#### Address Resolution Protocol (ARP)  
- **Purpose**: Maps IP addresses to MAC addresses for local network communication.  
- **Layer**: Network Access (Layer 2). No port number.  
- **Cache**: Devices store IP-MAC pairs in an ARP cache.  

#### Remote Access Protocols  
##### 1. **Telnet**  
   - **Use**: Remote CLI access (insecure, plaintext).  
   - **Port**: TCP 23.  
   - **Layer**: Application.  

##### 2. **Secure Shell (SSH)**  
   - **Use**: Encrypted remote access (replaces Telnet).  
   - **Port**: TCP 22.  
   - **Layer**: Application.  

#### Email Protocols  
##### 1. **Post Office Protocol (POP3)**  
   - **Function**: Downloads emails to a local device (deletes from server by default).  
   - **Ports**:  
     - Unencrypted: TCP/UDP 110  
     - Encrypted (SSL/TLS): TCP/UDP 995  

##### 2. **Internet Message Access Protocol (IMAP)**  
   - **Function**: Syncs emails across devices (stores on server).  
   - **Ports**:  
     - Unencrypted: TCP 143  
     - Encrypted (SSL/TLS): TCP 993  

##### 3. **Simple Mail Transfer Protocol (SMTP)**  
   - **Function**: Sends/relays emails between servers.  
   - **Ports**:  
     - Unencrypted: TCP/UDP 25  
     - Encrypted (TLS): TCP/UDP 587  

#### Key Port Numbers Summary  

| Protocol | Port(s)                     | Encryption          |  
|----------|-----------------------------|---------------------|  
| DHCP     | UDP 67 (server), 68 (client)| -                   |  
| ARP      | None                        | -                   |  
| Telnet   | TCP 23                      | ❌ (Plaintext)      |  
| SSH      | TCP 22                      | ✅ (AES)            |  
| POP3     | 110 (unencrypted), 995 (TLS)| ✅ (995 only)       |  
| IMAP     | 143 (unencrypted), 993 (TLS)| ✅ (993 only)       |  
| SMTP     | 25 (unencrypted), 587 (TLS) | ✅ (587 only)       |  

#### Key Takeaways  
- **NAT** enables private networks to access the internet via a public IP.  
- **DHCP** simplifies IP management; **ARP** resolves IP-MAC mappings.  
- **SSH** (secure) replaces **Telnet** (insecure) for remote access.  
- Email protocols: **POP3** (local storage) vs. **IMAP** (server sync); **SMTP** for sending.  
- Memorize port numbers for firewall configurations and troubleshooting.

---

### Wireless Security Protocols
Many people today refer to wireless internet as Wi-Fi. Wi-Fi refers to a set of standards that define communication for wireless LANs.

#### 1. WEP (Wired Equivalent Privacy)
- First wireless security protocol (1999)
- Major security vulnerabilities

#### 2. WPA (Wi-Fi Protected Access) 
- Temporary replacement for WEP (2003)
- Introduced TKIP encryption

#### 3. WPA2
- Current standard (2004)
- Uses AES encryption
- Personal and Enterprise modes

#### 4. WPA3
- Latest protocol (2018)
- 128/192-bit encryption
- KRACK attack resistant

#### Key Takeaways
- WEP and WPA are insecure
- Always use WPA3 (or WPA2 as fallback)

---

### Subnetting and CIDR

#### What is Subnetting?
- Division of a network into smaller logical subnets
- Improves efficiency and enables security zoning
- Devices on same subnet communicate faster

#### CIDR (Classless Inter-Domain Routing) Notation
- Replaced classful addressing (Class A-E)
- Format: IP/prefix (e.g., 192.168.1.0/24)
- /24 represents subnet mask (255.255.255.0)
- Allows more efficient IP allocation

#### Security Benefits of subnetting
- Creates isolated network segments
- Enables security zones (DMZ, restricted zones, etc.)
- Reduces attack surface through segmentation
- No need for additional public IPs

#### Key Takeaways
- Subnetting improves performance and security
- CIDR provides flexible IP allocation
- Essential for network segmentation strategies

---

### Virtual Networks and Privacy

#### Network Protocols
- **Communication**: TCP, UDP, SMTP
- **Management**: ICMP
- **Security**: IPSec, SSL/TLS
- **Common Protocols**:
  - HTTP (web communication)
  - DNS (hostname to IP)
  - ARP (IP to MAC mapping)

#### Wireless Security
- **Protocols**: WEP → WPA → WPA2 → WPA3
- **Encryption**: AES (WPA2/WPA3)
- **Modes**:
  - Personal (home networks)
  - Enterprise (business networks)

#### Network Security Tools
##### Firewalls
- **Stateless**: Rule-based, no connection tracking
- **Stateful**: Tracks connections via state table
- **Next-Gen (NGFW)**:
  - Deep packet inspection
  - Application-aware filtering
  - Advanced threat prevention

##### Proxy Servers
- **Forward**: Internal → External
- **Reverse**: External → Internal
- **Features**: NAT, content filtering

##### VPNs
- Encrypts data in transit
- Masks IP addresses
- Uses encapsulation

#### Key Takeaways
1. Protocols enable secure communication
2. WPA3 is current wireless standard
3. Firewalls/proxies/VPNs provide layered security
4. Modern networks combine VPN + SD-WAN

---

### VPN Protocols: WireGuard vs IPSec

#### VPN Overview
- Encrypts data and hides IP addresses
- Creates secure tunnels over public networks
- Protocols define connection rules between endpoints

#### VPN Types
1. **Remote Access VPN**
   - Connects personal devices to VPN servers
   - Used by individual users
   - Easier to configure

2. **Site-to-Site VPN**
   - Connects entire networks
   - Used by enterprises with multiple locations
   - More complex configuration

#### Protocol Comparison

| Feature          | WireGuard              | IPSec                  |
|------------------|------------------------|------------------------|
| Speed            | Faster                 | Slower                 |
| Code Complexity  | Simple (fewer lines)   | Complex                |
| Deployment       | Easier (open source)   | More difficult         |
| Use Cases        | Streaming, large files | Legacy systems         |
| Connection Types | Site-to-site & remote  | Primarily site-to-site |

#### Key Takeaways
- WireGuard offers better performance and simpler setup
- IPSec has wider compatibility (older protocol)
- Choice depends on speed needs vs compatibility

---

### Terms and Definitions

**Address Resolution Protocol (ARP)**: A network protocol used to determine the MAC address of the next router or device on the path

**Cloud-based firewalls**: Software firewalls that are hosted by the cloud service provider

**Controlled zone**: A subnet that protects the internal network from the uncontrolled zone

**Domain Name System (DNS)**: A networking protocol that translates internet domain names into IP addresses

**Encapsulation**: A process performed by a VPN service that protects your data by wrapping sensitive data in other data packets

**Firewall**: A network security device that monitors traffic to or from your network

**Forward proxy server**: A server that regulates and restricts a person's access to the internet

**Hypertext Transfer Protocol (HTTP)**: An application layer protocol that provides a method of communication between clients and website servers

**Hypertext Transfer Protocol Secure (HTTPS)**: A network protocol that provides a secure method of communication between clients and servers

**IEEE 802.11 (Wi-Fi)**: A set of standards that define communication for wireless LANs

**Network protocols**: A set of rules used by two or more devices on a network to describe the order of delivery of data and the structure of data

**Network segmentation**: A security technique that divides the network into segments

**Port filtering**: A firewall function that blocks or allows certain port numbers to limit unwanted communication

**Proxy server**: A server that fulfills the requests of its clients by forwarding them to other servers

**Reverse proxy server**: A server that regulates and restricts the internet's access to an internal server

**Secure File Transfer Protocol (SFTP)**: A secure protocol used to transfer files from one device to another over a network

**Secure shell (SSH)**: A security protocol used to create a shell with a remote system

**Security zone**: A segment of a company's network that protects the internal network from the internet

**Simple Network Management Protocol (SNMP)**: A network protocol used for monitoring and managing devices on a network

**Stateful**: A class of firewall that keeps track of information passing through it and proactively filters out threats

**Stateless**: A class of firewall that operates based on predefined rules and does not keep track of information from data packets

**Subnetting**: The subdivision of a network into logical groups called subnets

**Transmission Control Protocol (TCP)**: An internet communication protocol that allows two devices to form a connection and stream data

**Uncontrolled zone**: The portion of the network outside the organization

**Virtual private network (VPN)**: A network security service that changes your public IP address and masks your virtual location so that you can keep your data private when you are using a public network like the internet

**Wi-Fi Protected Access (WPA)**: A wireless security protocol for devices to connect to the internet

---
---

## Module 3

### How Intrusions Compromise Systems

#### Network Interception Attacks
Intercepting network traffic to steal data or disrupt transmissions
- **Methods**:
  - Packet sniffing (capturing/inspecting data)
  - Altering transmissions (e.g., modifying bank transfers)
- **Types**:
  - On-path attacks
  - Replay attacks

#### Backdoor Attacks
Exploiting hidden access points in systems
- **Sources**:
  - Intentionally left by developers for troubleshooting
  - Installed by attackers after initial breach
- **Impacts**:
  - Malware installation
  - DoS attacks
  - Data theft
  - Security setting changes

#### Potential Organizational Impacts
| Impact Area   | Consequences                                                       |
|---------------|--------------------------------------------------------------------|
| Financial     | Lost revenue, repair costs, ransomware payments, legal settlements |
| Reputation    | Loss of customer trust, competitive disadvantage                   |
| Public Safety | Critical infrastructure compromise (power grids, water systems)    |

#### Key Takeaways
- Attackers exploit vulnerabilities via interception/backdoor methods
- Consequences span financial, reputational, and safety domains
- Continuous security monitoring is critical for prevention

---

### Denial of Service (DoS) Attacks

#### Overview
- **Objective**: Overwhelm network/server to disrupt operations
- **Impact**: Business downtime, financial loss, security vulnerabilities
- **DDoS**: Distributed version using multiple attack sources

#### Common Network-Level DoS Attacks

1. **SYN Flood Attack**
   - Exploits TCP 3-way handshake:
     1. Floods server with SYN requests
     2. Exhausts available ports
     3. Prevents legitimate connections

2. **ICMP Flood Attack**
   - Bombards server with ICMP echo requests
   - Consumes all bandwidth
   - Crashes server from traffic overload

3. **Ping of Death**
   - Sends oversized ICMP packets (>64KB)
   - Causes system crashes
   - Analogous to crushing infrastructure

#### Key Characteristics
| Attack Type   | Protocol Used | Method                | Result                |
|---------------|---------------|-----------------------|----------------------|
| SYN Flood     | TCP           | Half-open connections | Port exhaustion      |
| ICMP Flood    | ICMP          | Echo request spam     | Bandwidth saturation |
| Ping of Death | ICMP          | Oversized packets     | System crash         |

#### Mitigation Strategies
- Rate limiting
- Traffic filtering
- Cloud-based DDoS protection
- Network monitoring systems

---

### tcpdump Network Protocol Analyzer

#### Overview
- Command-line packet sniffer
- Lightweight (low CPU/memory usage)
- Uses libpcap library
- Preinstalled on most Linux/Unix systems

#### Key Output Fields
| **Field**       | **Timestamp**       | **Source IP**     | **Source Port**    | **Dest IP**       | **Dest Port**      |
|-----------------|---------------------|-------------------|--------------------|-------------------|--------------------|
| **Description** | Packet capture time | Origin IP address | Origin port number | Target IP address | Target port number |
| **Example**     | `12:34:56.789`      | `192.168.1.1`     | `54321`            | `10.0.0.1`        | `80`               |

<img width="731" height="131" alt="image" src="https://github.com/user-attachments/assets/07cd7929-c8ec-4879-9282-a1c922475217" />

#### Common Uses
- Network troubleshooting
- Traffic pattern analysis
- Security monitoring
- Detecting malicious activity
- Identifying unauthorized services

#### Security Considerations
**Legitimate Uses:**
- Baseline network traffic
- Troubleshoot performance
- Detect intrusions

**Malicious Uses:**
- Capturing credentials
- Reconnaissance
- Eavesdropping

---

### IP Spoofing Attacks

#### What is IP Spoofing?
- Modifying source IP in packets to impersonate authorized systems
- Bypasses firewall rules by appearing as internal traffic

#### Common Spoofing Attacks

##### 1. On-Path Attack
   - Attacker intercepts communication between two devices
   - Becomes "man-in-the-middle"
   - Can alter data in transit

##### 2. Replay Attack
   - Intercepts and delays/retransmits packets
   - **Used to**:
     - Disrupt connections
     - Impersonate authorized users

##### 3. Smurf Attack
   - Combines DDoS + IP spoofing
   - Floods spoofed IP with packets
   - Overwhelms target system

#### Prevention Methods
| **Defense**        | **Implementation**                       |
|--------------------|------------------------------------------|
| Encryption         | Prevents packet interpretation           |
| Firewall Rules     | Block external traffic with internal IPs |
| Network Monitoring | Detect abnormal traffic patterns         |

#### Key Takeaways
- Spoofing enables more complex attacks
- Firewalls should reject internal IPs from external sources
- Encryption is critical for protection
- Combination of defenses works best

---

### Terms and Definitions

**Active packet sniffing**: A type of attack where data packets are manipulated in transit

**Botnet**: A collection of computers infected by malware that are under the control of a single threat actor, known as the "bot-herder"

**Denial of service (DoS) attack**: An attack that targets a network or server and floods it with network traffic

**Distributed denial of service (DDoS) attack**: A type of denial of service attack that uses multiple devices or servers located in different locations to flood the target network with unwanted traffic

**Internet Control Message Protocol (ICMP)**: An internet protocol used by devices to tell each other about data transmission errors across the network

**Internet Control Message Protocol (ICMP) flood**: A type of DoS attack performed by an attacker repeatedly sending ICMP request packets to a network server

**IP spoofing**: A network attack performed when an attacker changes the source IP of a data packet to impersonate an authorized system and gain access to a network

**On-path attack**: An attack where a malicious actor places themselves in the middle of an authorized connection and intercepts or alters the data in transit

**Packet sniffing**: The practice of capturing and inspecting data packets across a network

**Passive packet sniffing**: A type of attack where a malicious actor connects to a network hub and looks at all traffic on the network

**Ping of death**: A type of DoS attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB

**Replay attack**: A network attack performed when a malicious actor intercepts a data packet in transit and delays it or repeats it at another time

**Smurf attack**: A network attack performed when an attacker sniffs an authorized user's IP address and floods it with ICMP packets

**Synchronize (SYN) flood attack**: A type of DoS attack that simulates a TCP/IP connection and floods a server with SYN packets

---
---

## Module 4

### Security Hardening Fundamentals

#### What is Security Hardening?
- Process of reducing system vulnerabilities
- Minimizes attack surface (potential entry points)
- Applies to: hardware, OS, apps, networks, databases

#### Common Hardening Techniques

##### 1. System Maintenance
- Regular software updates/patches
- Disable unused applications/services
- Close unused network ports
- Reduce excessive access permissions

##### 2. OS Hardening Practices
- Scheduled patch management
- Baseline configuration maintenance
- Secure hardware/software disposal
- Strong password policies + MFA

##### 3. Network Protection
- Regular penetration testing
- Encryption standard updates
- Device/access monitoring
- Physical security measures

#### Key Benefits
- Prevents exploitation of known vulnerabilities
- Limits damage from potential breaches
- Maintains system integrity
- Improves monitoring efficiency

> **Pro Tip**: Treat hardening as an ongoing process, not a one-time task. Regular reviews and updates are essential for maintaining security.

---

### Brute Force Attacks & OS Hardening

#### Brute Force Attack & its Types
Trial-and-error method to guess credentials
- **Simple Brute Force**: Manual credential guessing
- **Dictionary Attacks**: Uses common passwords/breached credentials

#### Vulnerability Assessment Tools
| **Tool**             | **Purpose**              | **Considerations**             |
|----------------------|--------------------------|--------------------------------|
| **Virtual Machines** | Isolated malware testing | Risk of VM escape              |
| **Sandboxes**        | Safe environment testing | Some malware detects sandboxes |

#### Prevention Measures
##### 1. Password Security
   - Hashing (one-way encryption)
   - Salting (adds random characters)

##### 2. Authentication
   - MFA/2FA (multiple verification steps)
   - CAPTCHA/reCAPTCHA (bot prevention)

##### 3. Password Policies
   - Complexity requirements
   - Rotation schedules
   - Attempt limits
   - Reuse restrictions

#### OS Hardening and its Benefits
The process of securing an operating system by reducing vulnerabilities through configuration changes, updates, and access controls
- Reduces attack surface
- Limits damage from breaches
- Complements brute force protections

> **Best Practice**: Combine technical controls (MFA) with policy controls (password rules) for defense-in-depth.

---

### Network Security Applications

#### Core Security Tools
##### 1. Firewall
   - *Function*: Filters traffic based on rules (ports/IPs)  
   - *Types*: Stateless, Stateful, Next-Gen (NGFW)  
   - *Placement*: Network perimeter  

##### 2. Intrusion Detection System (IDS)  
   - *Function*: Monitors traffic and alerts on threats  
   - *Limitation*: Detection-only (no blocking)  
   - *Placement*: Behind firewall  

##### 3. Intrusion Prevention System (IPS)  
   - *Function*: Actively blocks detected threats  
   - *Risk*: Inline failure breaks connectivity  
   - *Placement*: Behind firewall  

##### 4. SIEM Tools  
   - *Function*: Centralized log analysis & alerting  
   - *Examples*: Splunk, Chronicle  
   - *Value*: "Single pane of glass" monitoring  

#### Key Comparisons
| **Tool**	   | **Pros**	                | **Cons**                     |
|--------------|--------------------------|------------------------------|
| **Firewall** | Basic traffic filtering	| Limited to header inspection |
| **IDS**	     | Threat detection         |	No active prevention         |
| **IPS**	     | Active threat blocking	  | False positives risk         |
| **SIEM**	   | Centralized visibility	  | Requires manual analysis     |

---

### Cloud Security Essentials

#### Key Considerations
##### 1. IAM (Identity Access Management)
   - Manages user roles/permissions
   - Critical to prevent overprivileged accounts

##### 2. Configuration Management
   - Each service requires precise security settings
   - Misconfigurations = leading cause of cloud breaches

##### 3. Attack Surface Expansion
   - Every new service adds potential vulnerabilities
   - Requires compensating security controls

##### 4. Zero-Day Threats
   - CSPs often detect/patch faster than on-prem
   - Hypervisor-level protections available

##### 5. Visibility Challenges
   - Limited packet-level inspection
   - Reliance on flow logs and mirroring tools
   - Third-party audits verify CSP security

---

### Cloud Cryptography & Security Hardening

#### Core Hardening Techniques
##### 1. IAM (Identity Access Management)
   - Manages digital identities and resource access
   - Critical for least-privilege enforcement

##### 2. Hypervisor Security
   - **Type 1 (Bare-metal)**: ESXi, Hyper-V (CSP-managed)
   - **Type 2 (Hosted)**: VirtualBox, VMware Workstation
   - Mitigate VM escape risks via CSP patches

##### 3. Baselining
   - Establish secure reference configurations:
     - Admin portal restrictions
     - Mandatory encryption
     - Threat detection enablement

#### Cryptographic Protections
| **Technique**        | **Purpose**             | **Implementation**       |
|----------------------|-------------------------|--------------------------|
| **Encryption**       | Data confidentiality    | AES-256 for data at rest |
| **Key Management**   | Secure key storage      | TPM, CloudHSM            |
| **Crypto-Shredding** | Secure data destruction | Key deletion             |

---

### Terms and Definitions from Module 4

**Baseline configuration (baseline image)**: A documented set of specifications within a system that is used as a basis for future builds, releases, and updates

**Hardware**: The physical components of a computer

**Multi-factor authentication (MFA)**: A security measure which requires a user to verify their identity in two or more ways to access a system or network

**Network log analysis**: The process of examining network logs to identify events of interest 

**Operating system (OS)**: The interface between computer hardware and the user

**Patch update**: A software and operating system update that addresses security vulnerabilities within a program or product

**Penetration testing (pen test)**: A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes 

**Security hardening**: The process of strengthening a system to reduce its vulnerabilities and attack surface

**Security information and event management (SIEM)**: An application that collects and analyzes log data to monitor critical activities for an organization

**World-writable file**: A file that can be altered by anyone in the world

---
---
---
