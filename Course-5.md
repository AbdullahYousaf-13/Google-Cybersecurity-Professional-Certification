# Assets, Threats, and Vulnerabilities

## Description
**Assets, Threats, and Vulnerabilities**, the fifth course in the Google Cybersecurity Certificate.

By the end of this course, you will further explore the importance of protecting organizational assets from threats, risks, and vulnerabilities. You will continue developing your understanding of asset classification and how to use the National Institute of Standards and Technology's (NIST) Cybersecurity Framework (CSF), as well as security controls, to protect assets and mitigate risk. In addition, you will develop a threat actor mindset to better understand how attackers target assets and how security professionals stay ahead of evolving tactics and techniques.

---

## Module 1: Introduction to asset security
You will be introduced to how organizations determine what assets to protect. You will learn about the connection between managing risk and classifying assets by exploring the unique challenge of securing physical and digital assets. You will also continue to explore the NIST CSF, as well as other guidelines and best practices used to manage cybersecurity risk.

---

## Module 2: Protect organizational assets
You will focus on security controls that protect organizational assets. You will explore how privacy impacts asset security and understand the role that encryption plays in maintaining the privacy of digital assets. You will also explore how authentication and authorization systems help verify a user's identity.

---

## Module 3: Vulnerabilities in systems
You will build an understanding of the vulnerability management process. You will also learn about common vulnerabilities and develop an attacker mindset by examining the ways vulnerabilities can become threats to asset security if they are exploited.

---

## Module 4: Threats to asset security
You will explore common types of threats to digital asset security. You will also examine the tools and techniques used by cybercriminals to target assets. In addition, you will be introduced to the threat modeling process and examine the ways that security professionals stay ahead of security breaches.

---
---

## Module 1

### Asset Security Fundamentals
Asset security is the practice of protecting an organization's valuable resources from unauthorized access, damage, loss, or theft. In cybersecurity, assets include both physical objects and digital information.

#### What is an asset?
An **asset** is anything of value to an organization.

##### Common asset types
- **Physical assets**: laptops, servers, security badges, office spaces, mobile devices
- **Digital assets**: customer records, credentials, source code, financial data, intellectual property
- **Cloud assets**: virtual machines, storage buckets, databases, SaaS data

#### Why asset security matters
- Supports confidentiality, integrity, and availability
- Reduces operational and financial risk
- Protects sensitive information and business processes
- Helps organizations meet legal and regulatory requirements

#### Key takeaways
- Assets can be physical, digital, or cloud-based
- Not all assets have the same value or sensitivity
- Security efforts should prioritize the most critical assets first

---

### Asset Classification
Organizations classify assets so they can apply the right level of protection. Classification helps security teams prioritize controls, access restrictions, and monitoring.

#### Common classification levels
| Classification | Meaning | Example |
|----------------|---------|---------|
| **Public** | Safe to share widely | Marketing content |
| **Internal** | Intended for employees only | Internal procedures |
| **Confidential** | Sensitive business information | Employee records |
| **Restricted** | Highest sensitivity | Encryption keys, customer PII |

#### Classification factors
- Business value
- Sensitivity of the data
- Legal or compliance requirements
- Operational impact if compromised

#### Data handling examples
- Restrict access to confidential files
- Encrypt sensitive data at rest and in transit
- Apply retention and disposal rules
- Log access to critical information

#### Key takeaways
- Asset classification helps determine appropriate security controls
- Sensitive assets require stronger access restrictions and monitoring
- Classification should be documented and consistently enforced

---

### Digital Assets and the Expanding Attack Surface
Digital transformation has increased the number of assets organizations must secure. Every connected system, cloud workload, account, and application can expand the attack surface.

#### Common digital assets
- User accounts
- Databases
- Web applications
- Endpoints
- APIs
- Cloud services

#### Attack surface
The **attack surface** is the total number of possible entry points an attacker can use to access or damage assets.

##### Examples of attack surface expansion
- Unused open ports
- Unpatched software
- Misconfigured cloud storage
- Shared credentials
- Shadow IT tools

#### Cloud security considerations
- Shared responsibility between customer and provider
- Configuration errors can expose data publicly
- Identity and access management is critical
- Continuous monitoring is required

#### Key takeaways
- More digital assets usually mean more possible vulnerabilities
- Attack surface reduction is a core security goal
- Cloud systems require strong configuration and access management

---

### Security Plans and Risk-Based Protection
A security plan outlines how an organization will protect assets, reduce risk, and respond to security events.

#### Common elements of a security plan
- Asset inventory
- Risk assessment
- Security controls
- Access management procedures
- Monitoring and logging
- Incident response steps
- Recovery and continuity planning

#### Risk scoring basics
Risk is often evaluated based on:
- **Likelihood**: how probable a threat is
- **Impact**: how serious the damage would be

Simple model:
`Risk = Likelihood x Impact`

#### Why risk-based security matters
- Resources are limited
- Not every system needs the same level of protection
- High-value assets should receive stronger controls

---

### NIST Cybersecurity Framework (CSF)
The NIST CSF helps organizations manage and reduce cybersecurity risk using a set of core functions.

#### NIST CSF core functions
| Function | Purpose |
|----------|---------|
| **Identify** | Understand assets, risks, and business context |
| **Protect** | Apply safeguards to reduce risk |
| **Detect** | Discover security events quickly |
| **Respond** | Take action during incidents |
| **Recover** | Restore normal operations |
| **Govern** | Align cybersecurity strategy, policy, and oversight |

#### Applying the framework to asset security
- Identify critical systems and data
- Protect them with controls
- Detect suspicious activity
- Respond to threats
- Recover from disruption

#### Key takeaways
- NIST CSF provides a practical structure for cybersecurity planning
- Asset identification is the foundation of asset security
- The framework supports risk-based decision making

---

### Terms and Definitions from Module 1

**asset**: An item perceived as having value to an organization.

**asset classification**: The process of labeling assets based on sensitivity and business value.

**attack surface**: The total number of possible entry points through which an attacker can access a system or data.

**cloud security**: The practices and technologies used to protect cloud-based systems, applications, and data.

**confidential data**: Sensitive information that should only be accessible to authorized users.

**data owner**: The person or group responsible for deciding how specific data is protected and used.

**digital asset**: An electronic resource of value, such as data, credentials, applications, or systems.

**govern**: A NIST CSF core function focused on cybersecurity strategy, oversight, and accountability.

**inventory**: A documented list of assets that an organization owns or manages.

**NIST Cybersecurity Framework (CSF)**: A framework of standards, guidelines, and best practices used to manage cybersecurity risk.

**restricted data**: Highly sensitive information that requires the strongest security protections.

**risk assessment**: The process of identifying and evaluating threats, vulnerabilities, likelihood, and impact.

---
---

## Module 2

### Security Controls That Protect Assets
Security controls are safeguards that help reduce risk to assets. They are used to prevent, detect, or correct security issues.

#### Main control categories
| Control Type | Purpose | Example |
|--------------|---------|---------|
| **Administrative** | Policies and procedures | Security awareness training |
| **Technical** | Technology-based safeguards | Firewalls, MFA, encryption |
| **Physical** | Protection of facilities and devices | Locks, badges, cameras |

#### Control functions
- **Preventive**: stop incidents before they happen
- **Detective**: identify incidents in progress or after they occur
- **Corrective**: restore systems and reduce damage
- **Deterrent**: discourage malicious activity

#### Key takeaways
- Controls are selected based on the value of the asset and the risk involved
- Strong asset protection usually requires layered controls
- Security controls support privacy and access management goals

---

### Privacy and Data Protection
Privacy focuses on the proper handling of personal and sensitive information. Asset security and privacy overlap because many assets contain data about people.

#### Sensitive data examples
- Personally identifiable information (PII)
- Protected health information (PHI)
- Financial account data
- Authentication credentials

#### Privacy principles
- Collect only necessary data
- Limit access to authorized users
- Retain data only as long as needed
- Dispose of data securely
- Be transparent about data use

#### Why privacy matters in cybersecurity
- Data misuse can harm individuals and organizations
- Legal penalties may result from poor data handling
- Trust is damaged when personal information is exposed

---

### Encryption Basics
Encryption protects data by converting readable information into an unreadable format that can only be reversed with the proper key.

#### Encryption states
| State | Meaning |
|-------|---------|
| **Data at rest** | Stored data, such as files or database records |
| **Data in transit** | Data moving across a network |
| **Data in use** | Data currently being processed by a system |

#### Symmetric vs. asymmetric encryption
| Type | Description | Example Use |
|------|-------------|-------------|
| **Symmetric** | Same key encrypts and decrypts data | Disk encryption |
| **Asymmetric** | Public key encrypts, private key decrypts | TLS, secure email |

#### Common uses of encryption
- Protecting laptops and mobile devices
- Securing web traffic with HTTPS
- Encrypting backups
- Protecting cloud storage

#### Key takeaways
- Encryption helps preserve confidentiality
- Key management is just as important as encryption itself
- Sensitive assets should be encrypted whenever practical

---

### Hashing and Integrity
Hashing transforms data into a fixed-length value. Unlike encryption, hashing is not meant to be reversed.

#### Why hashing is useful
- Verifies file integrity
- Protects stored passwords when implemented properly
- Detects unauthorized changes to data

#### Password storage best practices
- Use strong hashing algorithms
- Add a **salt** to make hashes harder to crack
- Avoid storing plaintext passwords

#### Encryption vs. hashing
| Method | Reversible? | Primary Purpose |
|--------|-------------|-----------------|
| **Encryption** | Yes, with a key | Confidentiality |
| **Hashing** | No | Integrity and verification |

#### Key takeaways
- Hashing is commonly used for integrity checks and password security
- Salting reduces the effectiveness of rainbow table attacks
- Encryption and hashing solve different security problems

---

### Authentication, Authorization, and Access Controls
Security teams protect assets by verifying user identity and limiting what verified users can do.

#### Authentication
Confirms who a user is.

Examples:
- Password
- Security token
- Fingerprint
- One-time passcode

#### Authorization
Determines what an authenticated user is allowed to access or do.

Examples:
- Read-only access to reports
- Admin rights for server maintenance
- Temporary access to a customer record

#### Common access control concepts
- **Least privilege**: give only the minimum access required
- **Separation of duties**: split high-risk tasks between multiple people
- **Need to know**: restrict sensitive information to those who require it
- **Multi-factor authentication (MFA)**: require two or more verification methods

#### Key takeaways
- Authentication verifies identity
- Authorization controls permissions
- Strong access controls reduce the chance of insider misuse and account compromise

---

### Terms and Definitions from Module 2

**access control**: A security measure that manages who can access a system, application, or data.

**administrative control**: A security safeguard based on policy, procedure, or process.

**asymmetric encryption**: A type of encryption that uses a public key and a private key.

**authentication**: The process of verifying who someone is.

**authorization**: The concept of granting access to specific resources in a system.

**ciphertext**: Data that has been encrypted into an unreadable format.

**encryption**: The process of converting data from a readable format to an encoded format.

**hash**: A fixed-length value created by a hashing algorithm from input data.

**hashing**: The transformation of data into a fixed-length value used for integrity and verification.

**least privilege**: The principle of granting only the minimum access necessary to perform a task.

**multi-factor authentication (MFA)**: An authentication method that requires two or more forms of verification.

**salt**: Random data added before hashing to make password attacks more difficult.

**symmetric encryption**: A type of encryption that uses the same key for encryption and decryption.

---
---

## Module 3

### Vulnerability Management
Vulnerability management is the ongoing process of identifying, evaluating, prioritizing, and reducing weaknesses in systems and applications.

#### Common vulnerability management steps
1. Identify assets
2. Scan for vulnerabilities
3. Analyze findings
4. Prioritize based on risk
5. Remediate or mitigate
6. Verify the fix
7. Continue monitoring

#### Why it matters
- Systems change constantly
- New flaws are discovered every day
- Unpatched vulnerabilities can become entry points for attackers

#### Key takeaways
- Vulnerability management is continuous, not one-time
- Prioritization is necessary because not all findings are equally urgent
- Asset context helps determine which vulnerabilities matter most

---

### Common Vulnerabilities and Exposures
Security teams often rely on industry standards to name and track known vulnerabilities.

#### CVE
**Common Vulnerabilities and Exposures (CVE)** provides a standard identifier for publicly known vulnerabilities.

Example:
`CVE-2021-44228` identifies Log4Shell.

#### CVSS
**Common Vulnerability Scoring System (CVSS)** helps measure the severity of a vulnerability.

#### Severity examples
| Score Range | Severity |
|-------------|----------|
| **0.0** | None |
| **0.1 - 3.9** | Low |
| **4.0 - 6.9** | Medium |
| **7.0 - 8.9** | High |
| **9.0 - 10.0** | Critical |

#### Why standards matter
- Improve communication between teams
- Help prioritize remediation
- Create consistency across tools and reports

---

### Attack Surfaces and Exposure
Attackers look for weaknesses in systems, applications, and processes. Security analysts need to think like attackers to understand where exposures exist.

#### Common exposure sources
- Default passwords
- Missing patches
- Misconfigured services
- Excessive permissions
- Unused accounts
- Insecure web applications

#### Attacker mindset
An attacker asks:
- What is exposed to the internet?
- Which systems are unpatched?
- Which users can be tricked?
- What paths lead to sensitive assets?

#### Defense in depth
Defense in depth means using multiple layers of protection so one failure does not immediately expose a critical asset.

Examples:
- Endpoint protection
- Network segmentation
- MFA
- Logging and alerting
- Backups

#### Key takeaways
- Exposure is often created by small configuration or process failures
- Defense in depth reduces the impact of a single weakness
- Thinking like an attacker improves risk identification

---

### Vulnerability Assessments and Penetration Testing
Both activities help identify weaknesses, but they are not the same.

#### Vulnerability assessment
- Finds and documents known weaknesses
- Often automated with scanners
- Focuses on breadth and prioritization

#### Penetration testing
- Simulates real attacker behavior
- Attempts to exploit weaknesses safely
- Focuses on proving impact

#### Comparison
| Activity | Main Goal | Typical Output |
|----------|-----------|----------------|
| **Vulnerability assessment** | Identify weaknesses | List of findings and severity |
| **Penetration test** | Validate exploitability | Demonstrated attack paths and impact |

#### Key takeaways
- Vulnerability assessments are broader and more routine
- Penetration tests are deeper and more adversarial
- Both contribute to stronger asset protection

---

### Remediation and Mitigation
Once a vulnerability is found, organizations choose how to address it based on risk, cost, and business needs.

#### Common response options
- **Remediation**: fully fix the issue
- **Mitigation**: reduce the likelihood or impact
- **Acceptance**: formally accept the risk
- **Compensating control**: add a different safeguard when a direct fix is not possible

#### Examples
- Apply a security patch
- Disable a vulnerable service
- Block exposure with a firewall rule
- Increase monitoring until a permanent fix is available

#### Key takeaways
- Fast remediation is best for critical vulnerabilities
- Mitigation is useful when immediate patching is not possible
- Business context influences response decisions

---

### Terms and Definitions from Module 3

**attack vector**: The path or method a threat actor uses to gain unauthorized access to a system or data.

**Common Vulnerabilities and Exposures (CVE)**: A standardized list of publicly known cybersecurity vulnerabilities.

**Common Vulnerability Scoring System (CVSS)**: A framework used to measure the severity of vulnerabilities.

**compensating control**: An alternative safeguard used when a primary control cannot be implemented.

**defense in depth**: A layered security approach that uses multiple controls to protect assets.

**exposure**: The condition of being accessible to threats because of a weakness or misconfiguration.

**mitigation**: The reduction of risk by applying safeguards or limiting impact.

**patch management**: The process of applying updates to fix vulnerabilities and improve security.

**penetration test (pen test)**: A simulated attack that helps identify and validate exploitable weaknesses.

**remediation**: The act of fully fixing a vulnerability or security issue.

**vulnerability assessment**: The process of identifying and evaluating weaknesses in systems or applications.

**vulnerability management**: The ongoing process of identifying, prioritizing, addressing, and monitoring vulnerabilities.

---
---

## Module 4

### Common Threats to Asset Security
Threats are events or circumstances that can negatively affect assets. Threat actors use many different tactics to steal data, disrupt services, or gain unauthorized access.

#### Common threat categories
- Social engineering
- Malware
- Web-based attacks
- Insider threats
- Credential attacks
- Supply chain threats

#### Threat vs. vulnerability
- A **threat** is a potential cause of harm
- A **vulnerability** is a weakness that a threat can exploit

---

### Social Engineering Attacks
Social engineering manipulates people into revealing information or performing unsafe actions.

#### Common types
| Attack Type | Description |
|-------------|-------------|
| **Phishing** | Fraudulent messages designed to steal information |
| **Spear phishing** | Targeted phishing aimed at a specific person or group |
| **Whaling** | Phishing aimed at executives or high-value targets |
| **Vishing** | Voice-based social engineering |
| **Smishing** | SMS or text-based social engineering |
| **Pretexting** | Creating a false scenario to gain trust or access |

#### Warning signs
- Urgent requests
- Suspicious links or attachments
- Unexpected login prompts
- Requests for sensitive data
- Impersonation of trusted contacts

#### Key takeaways
- People are often the easiest target
- Awareness training reduces social engineering risk
- Verification procedures are essential

---

### Malware and Malicious Code
Malware is software intentionally designed to harm systems, steal data, or enable unauthorized access.

#### Common malware types
- **Virus**: attaches to legitimate files and spreads when executed
- **Worm**: self-replicates across systems and networks
- **Trojan**: disguises itself as legitimate software
- **Ransomware**: encrypts data and demands payment
- **Spyware**: secretly collects information
- **Rootkit**: hides malicious activity and maintains privileged access

#### Malware goals
- Steal credentials
- Disrupt business operations
- Exfiltrate sensitive data
- Create persistence on a system

#### Key takeaways
- Malware can affect confidentiality, integrity, and availability
- Prevention depends on patching, user awareness, access controls, and monitoring
- Backups are critical for ransomware resilience

---

### Web-Based Exploits
Attackers often target web applications because they are exposed to users, customers, and the internet.

#### Common web threats
- **SQL injection**: malicious SQL input manipulates database queries
- **Cross-site scripting (XSS)**: malicious scripts run in a user's browser
- **Cross-site request forgery (CSRF)**: tricks a user into submitting unintended requests
- **Command injection**: attacker input causes system commands to run

#### Why web apps are attractive targets
- Public exposure
- Valuable customer data
- Direct connection to backend services
- Frequent changes and updates

#### Defensive practices
- Input validation
- Parameterized queries
- Output encoding
- Secure session management
- Regular application testing

---

### Threat Modeling
Threat modeling is the process of identifying potential threats, vulnerabilities, and mitigations before an attack occurs.

#### Goals of threat modeling
- Understand what needs protection
- Identify likely attackers and attack paths
- Anticipate abuse cases
- Improve security during design and operation

#### Basic threat modeling process
1. Identify assets
2. Diagram the system or workflow
3. Identify possible threats
4. Analyze vulnerabilities and attack paths
5. Prioritize risks
6. Recommend controls or design changes

#### Benefits
- Encourages proactive security thinking
- Helps teams focus on the highest-risk areas
- Supports secure system design

#### Key takeaways
- Threat modeling helps teams think like attackers without waiting for a real incident
- It is useful during design, deployment, and review phases
- The quality of threat modeling depends on clear understanding of assets and trust boundaries

---

### Staying Ahead of Threat Actors
Security professionals need continuous awareness of how attackers operate

#### Common ways teams stay prepared
- Monitor threat intelligence sources
- Review logs and alerts
- Patch high-risk systems quickly
- Run tabletop exercises
- Update playbooks and controls
- Perform regular assessments and testing

#### Threat actor mindset
Threat actors often look for:
- Easy targets
- Weak passwords
- Untrained users
- Poor visibility
- Delayed patching

#### Key takeaways
- Security is an ongoing process of adaptation
- Strong fundamentals reduce many common attack opportunities
- Threat intelligence and continuous improvement help organizations respond faster

---

### Terms and Definitions from Module 4

**command injection**: A web attack in which malicious input causes a system to execute unintended commands.

**cross-site request forgery (CSRF)**: An attack that tricks a user into making an unwanted request to a web application where they are already authenticated.

**cross-site scripting (XSS)**: A web attack in which malicious scripts are injected into trusted web content.

**malware**: Software designed to harm systems, steal data, or gain unauthorized access.

**phishing**: A social engineering attack that uses deceptive messages to steal information or deliver malware.

**pretexting**: A social engineering technique in which an attacker invents a false scenario to obtain information or access.

**ransomware**: Malware that encrypts data and demands payment to restore access.

**smishing**: A phishing attack delivered through text messages.

**social engineering**: A manipulation technique that exploits human behavior to gain information, access, or valuables.

**spear phishing**: A targeted phishing attack aimed at a specific individual or group.

**SQL injection**: A web attack that inserts malicious SQL statements into application inputs.

**threat modeling**: The process of identifying potential threats, vulnerabilities, and mitigations affecting a system or asset.

**trojan**: Malware that appears legitimate but performs malicious actions.

**vishing**: A voice-based phishing attack.

**worm**: Malware that self-replicates and spreads without needing a host file.

---

## Final Takeaways

- Asset security starts with knowing what assets exist and how important they are
- Classification, privacy, encryption, and access control are central to protecting organizational assets
- Vulnerability management helps teams identify and reduce weaknesses before attackers exploit them
- Threats such as phishing, malware, and web attacks target both people and systems
- Threat modeling and an attacker mindset help security teams stay proactive instead of reactive

---
---
---