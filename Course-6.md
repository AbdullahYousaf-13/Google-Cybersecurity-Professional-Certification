# Sound the Alarm: Detection and Response

## Description
**Sound the Alarm: Detection and Response**, the sixth course in the Google Cybersecurity Certificate.

By the end of this course, you will focus on incident detection and response. You will learn what defines a security incident and explain the incident response lifecycle, including the roles and responsibilities of incident response teams. You will also analyze and interpret network communications to detect security incidents using packet sniffing tools to capture network traffic. In addition, you will explore how logs, intrusion detection systems, and SIEM tools help security professionals investigate and respond to threats.

---

## Module 1: Introduction to detection and incident response
You will be introduced to incident detection and response. You will learn how security teams identify and manage incidents, explore the incident response lifecycle, and examine the roles and responsibilities of people who respond to security events.

---

## Module 2: Network monitoring and analysis
You will focus on network communications and how analysts monitor traffic to identify suspicious activity. You will learn about packet captures, indicators of compromise, and the role of packet sniffing tools in security analysis.

---

## Module 3: Incident investigation and response
You will continue building an incident responder mindset by learning how analysts investigate alerts, document findings, and prioritize incidents. You will examine indicators of attack, triage, and the value of clear incident documentation.

---

## Module 4: Network traffic and logs using IDS and SIEM tools
You will explore how logs, intrusion detection systems, and SIEM tools help security teams monitor and investigate security events. You will also be introduced to Suricata and detection methods used to identify suspicious network activity.

---
---

## Module 1

### Incident Response Lifecycles
This module begins by defining how organizations prepare for, identify, contain, and recover from security incidents.

#### NIST CSF recap
The course connects incident response to the NIST Cybersecurity Framework:
1. **Identify**
2. **Protect**
3. **Detect**
4. **Respond**
5. **Recover**

#### Incident response lifecycle
1. **Preparation**
2. **Detection and analysis**
3. **Containment, eradication, and recovery**
4. **Post-incident activity**

#### Why the lifecycle matters
- Helps teams respond consistently
- Reduces confusion during active incidents
- Supports recovery and long-term improvement

---

### The 5 W's of an Incident
Security analysts need to collect core facts quickly when an event occurs.

#### The 5 W's
1. **Who** triggered the incident
2. **What** happened
3. **When** the incident took place
4. **Where** the incident took place
5. **Why** the incident took place

#### Why they matter
- Help determine whether an event is truly an incident
- Support documentation and escalation
- Provide structure for investigation and communication

---

### Incident Response Teams
Organizations often rely on dedicated teams to manage security incidents.

#### CSIRT
**Computer Security Incident Response Team (CSIRT)** members may include:
- Security analysts
- Technical lead
- Incident coordinator
- Legal or communications support when needed

#### Common CSIRT goals
- **Command**
- **Control**
- **Communication**

#### Key idea
Incident response is collaborative. Technical investigation, communication, and coordination all matter during an incident.

---

### Security Operations Center (SOC)
The course introduces the SOC structure and how alerts move through it.

#### Common SOC tiers
| Tier | Typical Role |
|------|--------------|
| **Tier 1** | Monitors alerts and performs initial review |
| **Tier 2** | Investigates escalated cases |
| **Tier 3** | Handles advanced detection and deep analysis |
| **Manager** | Oversees people, workflow, and escalation |

#### Why SOC structure matters
- Supports specialization
- Improves escalation paths
- Helps teams respond faster to alerts

---

### Incident Response Plans
Incident response depends on documentation prepared before an incident occurs.

#### Common plan contents
- Incident response procedures
- Contact information
- System information
- Reporting templates
- Escalation guidance

#### Why plans matter
- Reduce delays during response
- Standardize actions across teams
- Improve legal, technical, and operational coordination

---

### Detection and Response Tools
This module introduces the categories of tools analysts use to detect and respond to suspicious activity.

#### Intrusion detection systems
Examples mentioned in the course notes:
- **Zeek**
- **Suricata**
- **Snort**
- **Sagan**

#### Intrusion prevention systems
Some tools can also prevent malicious traffic, including:
- **Suricata**
- **Snort**
- **Sagan**

#### Endpoint detection and response (EDR)
Examples:
- **Open EDR**
- **Bitdefender EDR**
- **FortiEDR**

#### SIEM process
1. **Collect and aggregate data**
2. **Normalize data**
3. **Analyze data**

#### SOAR
**Security orchestration, automation, and response (SOAR)** helps automate analysis and response workflows.

#### Key idea
SIEM helps collect and analyze data, while SOAR helps automate response actions and case management.

---

### Terms and Definitions from Module 1

**Computer Security Incident Response Team (CSIRT)**: A group of professionals responsible for responding to and managing security incidents.

**endpoint detection and response (EDR)**: A set of tools used to detect, investigate, and respond to threats on endpoint devices.

**incident**: An observable occurrence in a network or system that may indicate a security event or policy violation.

**incident response lifecycle**: The structured process used to prepare for, detect, contain, eradicate, recover from, and review security incidents.

**incident response plan**: A documented set of procedures and information used to respond to incidents consistently.

**intrusion detection system (IDS)**: A tool or system that monitors activity to identify suspicious events or known threats.

**intrusion prevention system (IPS)**: A security system that can detect and actively block malicious activity.

**security operations center (SOC)**: A centralized function or team that monitors and responds to security events.

**Security Information and Event Management (SIEM)**: A platform that collects, normalizes, and analyzes security-related data from multiple sources.

**Security Orchestration, Automation, and Response (SOAR)**: A collection of tools and workflows that automate and coordinate security response tasks.

---
---

## Module 2

### Network Monitoring Basics
This module focuses on how analysts monitor network communications to identify suspicious behavior.

#### Key network monitoring terms
- **Indicator of compromise (IoC)**: Observable evidence that a security incident may have happened
- **Data exfiltration**: Unauthorized transmission of data from a system
- **Network traffic**: The amount of data moving across a network
- **Network data**: The actual data being transmitted

#### Why network monitoring matters
- Helps identify malicious communication
- Detects unusual patterns early
- Supports investigation and containment

---

### Common Monitoring Methods
Security teams analyze traffic in several ways to find anomalies.

#### Monitoring approaches
- **Flow analysis**: Looks for unusual ports, packets, or protocols
- **Packet payload inspection**: Examines the contents of packets
- **Temporal pattern analysis**: Checks whether communication occurs at unusual times

#### Defensive goals
- Prevent attacker access
- Monitor network activity
- Protect assets
- Detect and stop exfiltration

---

### Packet Captures
Packet captures are a major source of evidence during network analysis.

#### Packet capture
A **packet capture** records network traffic so analysts can review communications after the fact.

#### Common packet capture formats
| Format | Description |
|--------|-------------|
| **Libpcap** | Common Unix-like packet capture format |
| **WinPcap** | Older Windows packet capture library |
| **Npcap** | Windows packet capture library often associated with Nmap |
| **PCAPng** | Next-generation capture format that stores packets and metadata |

#### Why packet captures matter
- Preserve evidence for analysis
- Support troubleshooting
- Help confirm suspicious traffic patterns

---

### IP Packet Details
Understanding packet structure helps analysts interpret captured traffic.

#### IPv4 header fields discussed in the course
- Version
- Internet Header Length
- Type of Service
- Total Length
- Identification, Flags, Fragment Offset
- Time To Live (TTL)
- Protocol
- Header checksum
- Source address
- Destination address
- Options

#### IPv6 header fields discussed in the course
- Version
- Traffic class
- Flow label
- Payload length
- Next header
- Hop limit
- Source address
- Destination address

#### Key idea
Packet headers contain the metadata analysts use to understand where traffic came from, where it is going, and how it should be interpreted.

---

### Packet Sniffing with tcpdump
The course introduces `tcpdump` as a command-line tool for capturing and analyzing network traffic.

#### Example command
```bash
sudo tcpdump -i any -v -c 1
```

#### Command parts
- `sudo`: run with elevated privileges
- `tcpdump`: start the tool
- `-i any`: capture on any interface
- `-v`: verbose output
- `-c 1`: capture one packet

#### Why tcpdump matters
- Useful for quick packet inspection
- Common on Linux and Unix-like systems
- Lightweight for command-line investigations

---

### Terms and Definitions from Module 2

**data exfiltration**: The unauthorized transfer of data from a system or network.

**flow analysis**: The examination of communication patterns such as ports, protocols, and packet flow to identify suspicious activity.

**indicator of compromise (IoC)**: Observable evidence that suggests a security incident may have occurred.

**network data**: The actual content transmitted across a network.

**network traffic**: The amount and movement of data across a network.

**packet capture (PCAP)**: A recorded set of network packets used for later analysis.

**packet payload**: The part of a packet that contains the actual transmitted data.

**packet sniffing**: The process of capturing and inspecting packets traveling across a network.

**tcpdump**: A command-line packet analyzer used to capture and inspect network traffic.

**Time To Live (TTL)**: A packet header field that limits how long a packet can travel before being discarded.

---
---

## Module 3

### Indicators of Compromise and Indicators of Attack
This module distinguishes between evidence of a completed incident and signs of an active or developing attack.

#### Indicator of compromise (IoC)
Observable evidence that suggests a potential security incident occurred.

Examples:
- A suspicious IP address
- A malicious filename
- A known bad hash

#### Indicator of attack (IoA)
A pattern of behavior or a series of events that suggests an attack is happening in real time.

Examples:
- A process unexpectedly making outbound network connections
- Repeated unauthorized attempts to perform actions

#### Key difference
- **IoCs** often help explain the **who** and **what** after an event
- **IoAs** help identify the **why** and **how** of ongoing activity

---

### The Pyramid of Pain
The course introduces the Pyramid of Pain to show how different indicators affect attackers differently.

#### Core idea
The higher an indicator sits on the pyramid, the harder it is for an attacker to change or work around.

#### TTP
**Tactics, techniques, and procedures (TTPs)** describe how threat actors behave and operate.

#### Why the pyramid matters
- Blocking a single IP address is relatively easy for attackers to bypass
- Detecting behavior and TTPs is more disruptive to attackers
- Better detection focuses on higher-value indicators when possible

---

### Documentation in Incident Response
Clear documentation is a core part of investigation and response.

#### Benefits of documentation
1. **Transparency**
2. **Standardization**
3. **Clarity**

#### Why it matters
- Preserves chain of custody
- Supports consistent response
- Makes escalation and communication easier

---

### Triage
Analysts use triage to quickly assess and prioritize incoming alerts and incidents.

#### Common triage steps
1. **Receive and assess**
2. **Assign priority**
3. **Collect and analyze**

#### Why triage matters
- Analysts cannot treat every alert the same way
- Prioritization helps focus on the highest-risk incidents first
- Good triage reduces time spent on low-value noise

---

### Incident Investigation Mindset
This module emphasizes practical thinking during investigations.

#### Investigation priorities
- Verify whether the alert is legitimate
- Gather evidence without damaging it
- Document what was observed
- Escalate when the incident exceeds current authority or skill level

#### Key idea
Strong investigation work depends on evidence handling, prioritization, and communication as much as technical skill.

---

### Terms and Definitions from Module 3

**chain of custody**: A documented record showing how evidence was collected, handled, and transferred.

**indicator of attack (IoA)**: A pattern of behavior that suggests an attack may be in progress.

**indicator of compromise (IoC)**: Observable evidence that suggests a security incident may have taken place.

**investigation**: The process of examining alerts, evidence, and system activity to understand a possible incident.

**Pyramid of Pain**: A model showing how difficult different indicators are for attackers to change.

**tactics, techniques, and procedures (TTPs)**: The behaviors and methods threat actors use to carry out attacks.

**triage**: The process of assessing and prioritizing incidents or alerts based on urgency and impact.

---
---

## Module 4

### Logs
This module focuses on logs as a major source of evidence during monitoring and investigations.

#### Common log types
- **Network logs**: Firewalls, proxies, and related network devices
- **System logs**: Operating system activity
- **Application logs**: Specific program activity
- **Security logs**: Security tools such as IDS and IPS
- **Authentication logs**: Login attempts and identity-related events

#### Why logs matter
- Help reconstruct events
- Reveal patterns over time
- Provide evidence for detection and response

---

### Host-Based and Network-Based Detection
The course introduces two major intrusion detection perspectives.

#### HIDS
**Host-based intrusion detection system (HIDS)**:
- Installed on a host or endpoint
- Monitors activity on that specific system

#### NIDS
**Network-based intrusion detection system (NIDS)**:
- Positioned to monitor network traffic
- Observes communications moving across the network

#### Key difference
- HIDS focuses on one host
- NIDS focuses on traffic across network paths

---

### Detection Techniques
Detection systems use different analysis methods to identify suspicious activity.

#### Signature-based analysis
- Compares activity against known malicious patterns
- Usually has lower false positives
- Easier for attackers to evade if they change behavior

#### Anomaly-based analysis
- Looks for behavior outside a normal baseline
- Can detect unknown threats
- Often produces more false positives

#### Key idea
Both methods are useful, and many systems combine them.

---

### Detection Signatures
Signatures are rules that tell an IDS or IPS what to look for.

#### Common signature elements
- **Action**: What to do, such as alert, pass, or reject
- **Header**: Source and destination IP addresses, ports, and protocols
- **Rule options**: Extra filtering or detection logic

#### Why signatures matter
- Translate threat knowledge into detection logic
- Help automate alerting
- Need tuning to reduce noise

---

### Suricata
The course introduces Suricata as a practical tool for network monitoring and detection.

#### What Suricata is
Suricata can function as:
- **IDS**
- **IPS**
- **NSM** (network security monitoring) tool

#### Common Suricata log files
| File | Purpose |
|------|---------|
| `eve.json` | Standard JSON log output |
| `fast.log` | Basic simplified logging |

#### Why Suricata matters
- Widely used in blue-team workflows
- Supports rule-based monitoring
- Produces logs that can feed into SIEM workflows

---

### IDS, SIEM, and Security Analysis
This module brings together traffic analysis, detection systems, and log review.

#### How the pieces connect
- **IDS/NIDS/HIDS** generate alerts from observed behavior
- **Logs** provide detailed event records
- **SIEM** centralizes and correlates those events
- Analysts investigate, tune rules, and escalate when needed

#### Key idea
Detection is not just about seeing alerts. It also requires context, log analysis, and judgment.

---

### Terms and Definitions from Module 4

**anomaly-based analysis**: A detection method that identifies behavior outside normal patterns.

**authentication log**: A log that records sign-in attempts and related identity events.

**Host-based Intrusion Detection System (HIDS)**: An intrusion detection system installed on a specific host or endpoint.

**log**: A record of events that occur within systems, applications, or security tools.

**Network-based Intrusion Detection System (NIDS)**: An intrusion detection system that monitors traffic across a network.

**network security monitoring (NSM)**: The practice of collecting and analyzing network data to detect and respond to threats.

**signature**: A defined rule or pattern used by a detection system to identify suspicious or malicious activity.

**signature-based analysis**: A detection method that compares observed activity to known malicious patterns.

**Suricata**: An open-source IDS, IPS, and network security monitoring tool.

---

## Final Takeaways

- Incident response relies on preparation, structured investigation, and documented recovery steps
- The 5 W's, CSIRTs, and SOC tiers help organizations manage incidents clearly and consistently
- Packet captures, IP headers, and tools like `tcpdump` help analysts inspect suspicious network activity
- IoCs, IoAs, the Pyramid of Pain, and triage help analysts investigate and prioritize threats
- Logs, IDS tools, Suricata, and SIEM platforms work together to support detection and response
