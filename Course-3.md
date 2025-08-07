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

