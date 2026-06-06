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
You will explore common types of threats to digital asset security. You will also examine the tools and techniques used by cybercriminals to target assets. In addition, you will be introduced to the threat modeling process and examine the ways security professionals stay ahead of security breaches.

---
---

## Module 1

### Understand Risks, Threats, and Vulnerabilities
This module starts by defining what organizations are trying to protect and why. Asset security depends on understanding the relationship between assets, threats, vulnerabilities, and risk.

#### Core concepts
- **Asset**: Anything of value to an organization
- **Threat**: Any circumstance or event that can negatively impact assets
- **Vulnerability**: A weakness that can be exploited by a threat
- **Risk**: Anything that can impact the confidentiality, integrity, or availability of an asset

#### Security plan: three basic elements
##### 1. Assets
- Physical examples: buildings, devices, badges, people
- Digital examples: files, credentials, databases, software

##### 2. Threats
- Can be intentional or unintentional
- Can come from internal or external sources

##### 3. Vulnerabilities
- Technical weaknesses such as outdated software
- Human weaknesses such as poor security awareness

#### Key idea
Risk exists when a threat can exploit a vulnerability to affect an asset.

---

### Security Starts with Asset Classification
Organizations cannot protect everything in the same way. Asset classification helps determine which data and systems need stronger safeguards.

#### Asset management terms
- **Asset management**: The process of tracking assets and the risks that affect them
- **Asset inventory**: A catalog of assets that need protection
- **Asset classification**: Labeling assets based on sensitivity and business value

#### Common classification levels
| Classification | Description |
|----------------|-------------|
| **Public** | Intended for anyone |
| **Internal only** | Intended for people inside the organization |
| **Confidential** | Limited to specific authorized personnel |
| **Restricted** | Highly sensitive, with very limited access |

#### Why classification matters
- Helps apply the right controls
- Supports compliance and privacy requirements
- Reduces overexposure of sensitive data

---

### Assets in a Digital World
Modern organizations store and process large amounts of digital information. This increases the number of assets that require security controls.

#### States of data
| State | Meaning |
|-------|---------|
| **In use** | Data currently being accessed or processed |
| **In transit** | Data moving across a network |
| **At rest** | Data stored on a device or system |

#### Cloud security
The course also introduces the emergence of cloud security.

##### Important cloud ideas
- Cloud systems increase flexibility and scale
- They also increase the number of digital assets to track
- Misconfigurations can expose sensitive data
- Organizations still remain responsible for protecting their data

#### Key idea
The more digital systems an organization relies on, the more important visibility, classification, and access control become.

---

### Elements of a Security Plan
Security programs rely on documented guidance so people and systems handle assets consistently.

#### Key documentation types
- **Policy**: A set of rules that reduces risk and protects information
- **Standards**: References used to support and inform policies
- **Procedures**: Step-by-step instructions for completing security tasks

#### Related concepts
- **Compliance**: Following internal standards and external regulations
- **Regulations**: Rules created by governments or other authorities

#### Why this matters
- Security work needs consistency
- Policies and procedures support accountability
- Clear standards make audits and enforcement easier

---

### The NIST Cybersecurity Framework
This course continues building on the NIST CSF introduced earlier in the certificate.

#### NIST CSF
A voluntary framework of standards, guidelines, and best practices for managing cybersecurity risk.

#### Core functions
1. **Identify**
2. **Protect**
3. **Detect**
4. **Respond**
5. **Recover**

#### Additional framework concepts
##### Tiers
Used to describe how mature or effective an organization's cybersecurity practices are.

##### Profiles
Used to compare the current state of security with the desired target state.

#### Key idea
The framework helps organizations connect asset protection decisions to risk management and business needs.

---

### Terms and Definitions from Module 1

**asset**: An item perceived as having value to an organization.

**asset classification**: The practice of labeling assets based on sensitivity and importance to an organization.

**asset inventory**: A catalog of assets that need to be tracked and protected.

**asset management**: The process of tracking assets and the risks that affect them.

**compliance**: The process of adhering to internal standards and external regulations.

**policy**: A set of rules that reduces risk and protects information.

**procedure**: Step-by-step instructions used to complete a specific security task.

**risk**: Anything that can impact the confidentiality, integrity, or availability of an asset.

**standard**: A reference that informs how policies and procedures are applied.

**threat**: Any circumstance or event that can negatively impact assets.

**vulnerability**: A weakness that can be exploited by a threat.

---
---

## Module 2

### Security Controls
This module focuses on the safeguards organizations use to protect assets.

#### Security controls
Security controls are safeguards designed to reduce specific security risks.

#### Major control types covered in the course
- **Technical controls**: Technology used to protect assets, such as encryption
- **Operational controls**: Processes and human-centered practices, such as awareness training
- **Managerial controls**: Governance tools such as policies, standards, and procedures

#### Why controls matter
- They reduce risk to data and systems
- They support privacy and compliance
- They help enforce least privilege and accountability

---

### Principle of Least Privilege and Data Roles
Users and systems should receive only the access needed to perform their tasks.

#### Principle of least privilege
Give users only the minimum permissions necessary to do their work.

#### Common data-related roles
- **Data owner**: The person who decides how data can be accessed, edited, used, or destroyed
- **Data custodian**: The person or system responsible for safe handling, transport, and storage of data
- **Data steward**: The person or group that maintains data governance policies

#### Common account types
- **Guest account**: Very limited access for outside users
- **User account**: Standard employee access
- **Service account**: Used by applications and systems
- **Privileged account**: Elevated administrative access

#### Key idea
Access should be based on role and necessity, not convenience.

---

### The Data Lifecycle and Privacy
The course connects asset protection with privacy and proper data handling.

#### Data lifecycle
1. **Collect**
2. **Store**
3. **Use**
4. **Archive**
5. **Destroy**

#### Why privacy matters
- Sensitive data needs stronger protections
- Data should only be retained as long as necessary
- Mishandling personal data can create legal and reputational risk

#### Related topic
The module also introduces privacy regulations and compliance expectations that affect how organizations manage sensitive information.

---

### Fundamentals of Cryptography
Cryptography helps protect digital assets, especially private and sensitive information.

#### Symmetric encryption
- Uses the same secret key to encrypt and decrypt data
- Often used for speed and efficiency
- Examples mentioned in the course: `AES`, `3DES`

#### Asymmetric encryption
- Uses a public key and a private key
- Public key encrypts, private key decrypts
- Examples mentioned in the course: `RSA`, `DSA`

#### Public Key Infrastructure (PKI)
PKI is an encryption framework that:
- Secures the exchange of information online
- Uses digital certificates to establish trust between systems

#### Key idea
Encryption protects confidentiality, but trust and key handling are equally important.

---

### Non-Repudiation and Hashing
The course also introduces hashing and its relationship to integrity and trust.

#### Hashing
- Converts input data into a fixed-length value
- Used to verify integrity
- Not meant to be reversed like encryption

#### Non-repudiation
Non-repudiation helps prove the authenticity of information so that its origin or action cannot reasonably be denied.

#### Why hashing matters
- Detects changes to files or messages
- Supports password security and integrity checking
- Works with other mechanisms to build trust

---

### Access Controls and Authentication Systems
This module introduces AAA and common access control approaches.

#### AAA framework
##### Authentication
Answers: **Who are you?**

Common factors:
1. **Knowledge**: Something the user knows
2. **Ownership**: Something the user has
3. **Characteristic**: Something the user is

##### Authorization
Answers: **What can you do?**

##### Accounting
Answers: **What happened?**

#### Additional concepts
- **Separation of duties**: Users should not have enough permissions to improperly influence their own actions
- **Single sign-on (SSO)** and **multi-factor authentication (MFA)** strengthen access management
- **Identity and access management (IAM)** helps control identities and permissions at scale

#### Common access control models
| Model | Meaning |
|-------|---------|
| **MAC** | Mandatory access control |
| **DAC** | Discretionary access control |
| **RBAC** | Role-based access control |

#### Key idea
Authentication confirms identity, authorization limits access, and accounting records activity.

---

### Terms and Definitions from Module 2

**access control**: A security measure that manages access to systems, applications, or data.

**accounting**: The process of tracking what actions users performed in a system.

**asymmetric encryption**: Encryption that uses a public key and a private key.

**authentication**: The process of verifying who someone is.

**authorization**: The concept of granting access to specific resources in a system.

**data custodian**: A person or system responsible for the safe handling, transport, and storage of data.

**data lifecycle**: The sequence of stages data moves through from collection to destruction.

**data owner**: The person responsible for decisions about how data is accessed and used.

**data steward**: The person or group that maintains data governance policies.

**hashing**: The process of converting data into a fixed-length value for integrity verification.

**multi-factor authentication (MFA)**: An authentication method that uses two or more forms of verification.

**non-repudiation**: Assurance that the origin or action associated with information cannot be denied.

**principle of least privilege**: Granting only the minimum access necessary to complete a task.

**Public Key Infrastructure (PKI)**: A framework that uses encryption and digital certificates to establish trust online.

**role-based access control (RBAC)**: An access control model where permissions are assigned according to job role.

**single sign-on (SSO)**: An authentication method that allows a user to sign in once to access multiple systems.

**symmetric encryption**: Encryption that uses the same secret key to encrypt and decrypt data.

---
---

## Module 3

### Vulnerability Management
This module explains how organizations identify and address weaknesses before they are exploited.

#### Vulnerability management process
1. **Identify vulnerabilities**
2. **Consider potential exploits**
3. **Prepare defenses against threats**
4. **Evaluate defenses**

#### Important term
- **Zero-day**: A vulnerability that becomes known when there are zero days available to fix it before exploitation risk begins

#### Key idea
Vulnerability management is continuous because systems, software, and attack methods constantly change.

---

### Defense in Depth Strategy
The course presents defense in depth as a layered approach to security.

#### Defense in depth
Also described as a castle approach or Swiss cheese model, where multiple layers reduce the chance that one failure leads directly to compromise.

#### Common layers
1. **Perimeter layer**: credentials and user authentication
2. **Network layer**: firewalls and network controls
3. **Endpoint layer**: protection for user and server devices
4. **Application layer**: software-level protections
5. **Data layer**: asset classification and data protection

#### Key idea
No single control is enough on its own.

---

### Common Vulnerabilities and Exposures
This section covers how vulnerabilities are named and prioritized.

#### Exposure vs. vulnerability
- **Exposure**: A mistake or condition that can be exploited by a threat
- **Vulnerability**: A weakness in a system

#### CVE
**Common Vulnerabilities and Exposures (CVE)** is a standardized naming system for publicly known vulnerabilities.

#### CVE background
- Originally created by MITRE in 1999
- Reviewed by CVE Numbering Authorities (CNAs)

#### NIST NVD and CVSS
- The **National Vulnerability Database (NVD)** uses **CVSS**
- **Common Vulnerability Scoring System (CVSS)** scores severity on a `0.0` to `10.0` scale

##### General score interpretation
- Under `4.0`: lower urgency
- Over `9.0`: requires immediate attention

---

### Vulnerabilities of CI/CD and the OWASP Top 10
The module also introduces common weaknesses in software development and web applications.

#### CI/CD vulnerabilities
Weaknesses can appear anywhere in continuous integration and continuous delivery pipelines if:
- secrets are exposed
- dependencies are unverified
- access is too broad
- build and deployment systems are not hardened

#### OWASP Top 10
The course points to the OWASP Top 10 as a useful reference for the most significant web application security risks.

#### Why this matters
- Application weaknesses often become entry points
- Secure development practices help reduce avoidable exposure

---

### Open Source Intelligence and Vulnerability Scanning
Security professionals use publicly available information and automated tools to identify risk.

#### OSINT
**Open source intelligence (OSINT)** is intelligence gathered from publicly available information.

#### Information vs. intelligence
- **Information**: raw facts or data
- **Intelligence**: information that has been analyzed and interpreted to produce useful insight

#### Vulnerability scanning approaches
The course covers different approaches to vulnerability scanning and emphasizes that discovery alone is not enough. Findings still need analysis and prioritization.

---

### Vulnerability Assessments and Penetration Testing
The course distinguishes between identifying weaknesses and actively testing exploitability.

#### Vulnerability assessment process
1. **Identification**: Discover the current state
2. **Vulnerability analysis**: Examine each weakness
3. **Risk assessment**: Score the vulnerability
4. **Remediation**: Fix or reduce the issue

#### Penetration testing teams
- **Red team**: Simulates attacks
- **Blue team**: Defends and responds
- **Purple team**: Combines offense and defense collaboration

#### Types of penetration testing
| Type | Meaning |
|------|---------|
| **Open-box** | Tester has extensive internal knowledge |
| **Closed-box / Black-box** | Tester has outsider-level knowledge |
| **Partial-knowledge / Grey-box** | Tester has limited internal knowledge |

#### Related topic
The module also emphasizes the importance of software and system updates as part of reducing vulnerabilities.

---

### Adopt an Attacker Mindset
Security analysts are encouraged to think like attackers in order to identify likely paths into a system.

#### Types of threat actors
- Competitor
- State actor
- Criminal syndicate
- Insider threat
- Shadow IT user

#### Important term
- **Advanced persistent threat (APT)**: A threat actor or campaign that maintains access over a long period of time

#### Types of hackers
- Unauthorized hacker
- Authorized or ethical hacker
- Semi-authorized actor such as a hacktivist

#### Common attack vectors
- Direct physical access
- Removable media
- Social media platforms
- Email
- Wireless networks
- Cloud services
- Supply chains

#### Defending against attack vectors
- Educate users
- Apply least privilege
- Use appropriate controls and tools
- Harden all entry points

---

### Terms and Definitions from Module 3

**advanced persistent threat (APT)**: A threat that maintains unauthorized access to a system for an extended period of time.

**attack vector**: The path or method used to gain access to a target.

**Common Vulnerabilities and Exposures (CVE)**: A standardized system for identifying publicly known vulnerabilities.

**Common Vulnerability Scoring System (CVSS)**: A scoring framework used to measure vulnerability severity.

**defense in depth**: A layered security strategy that uses multiple safeguards to protect assets.

**exposure**: A mistake or condition that can be exploited by a threat.

**National Vulnerability Database (NVD)**: A U.S. government repository of standards-based vulnerability information.

**open source intelligence (OSINT)**: Intelligence produced from publicly available information.

**penetration testing**: Simulated attack activity used to evaluate security defenses.

**red team**: A team that simulates attacker behavior.

**remediation**: The process of fixing or reducing a vulnerability.

**shadow IT**: Technology used without formal organizational approval or oversight.

**vulnerability assessment**: The process of identifying, analyzing, and prioritizing weaknesses.

**vulnerability management**: The ongoing process of discovering, evaluating, and addressing vulnerabilities.

**zero-day**: A vulnerability with no available time or patch buffer before exploitation becomes a risk.

---
---

## Module 4

### Social Engineering Tactics
This module begins with threats that target people instead of systems directly.

#### Social engineering
A manipulation technique that exploits human behavior to gain information, access, or valuables.

#### Typical stages
1. **Prepare**
2. **Establish trust**
3. **Use persuasion tactics**
4. **Disconnect from the target**

#### Common social engineering techniques
- **Pretexting**
- **Baiting**
- **Quid pro quo**
- **Tailgating**
- **Watering hole attack**

#### Prevention ideas emphasized in the course
- Use managerial controls
- Stay informed about threat trends
- Share security knowledge with others
- Be cautious with unexpected communication and requests

---

### Types of Phishing
The course treats phishing as one of the most common social engineering threats.

#### Phishing
A deceptive attempt to obtain information or deliver malicious content through messages, sites, or attachments.

#### Common phishing kit components
- Malicious attachments
- Fake data collection forms
- Fraudulent web links

#### Why phishing works
- Creates urgency
- Exploits trust
- Imitates familiar brands or people

#### Key idea
Phishing is both a user problem and a system problem, so defenses need training plus technical controls.

---

### An Introduction to Malware
The course introduces several common malware families and signs of infection.

#### Five common malware types
1. **Virus**: Requires user action to activate
2. **Worm**: Self-replicates and spreads on its own
3. **Trojan**: Disguises itself as something legitimate
4. **Ransomware**: Encrypts data and demands payment
5. **Spyware**: Collects data without consent

#### Cryptojacking
Cryptojacking malware uses a victim's system resources to mine cryptocurrency.

##### Common signs of cryptojacking
- System slowdown
- Increased CPU usage
- Sudden crashes
- Fast battery drain
- Higher electricity costs

---

### Web-Based Exploits
This module also covers attacks against web applications and databases.

#### Cross-site scripting (XSS)
An injection attack that inserts malicious code into a vulnerable website.

#### Common XSS types
- **Reflected**
- **Stored**
- **DOM-based**

#### SQL injection
An attack that manipulates database queries through untrusted input.

#### SQL injection types
- **In-band**
- **Out-of-band**
- **Inferential**

#### SQL injection prevention
- Prepared statements
- Input sanitization
- Input validation

#### Key idea
Applications that accept user input without strong validation create exploitable gaps.

---

### A Proactive Approach to Security
After reviewing common threats, the course shifts to proactive security thinking through threat modeling.

#### Threat modeling
The process of identifying assets, vulnerabilities, and the ways threats could affect them.

#### Typical threat modeling steps
1. Define the scope
2. Identify threats
3. Characterize the environment
4. Analyze threats
5. Mitigate risks
6. Evaluate findings

#### Risk response options
- Avoid
- Transfer
- Reduce
- Accept

#### Related concept
Attack trees help map how threats might reach an asset through different attack paths.

---

### PASTA: Process for Attack Simulation and Threat Analysis
The course introduces PASTA as a structured threat modeling framework.

#### PASTA stages
1. **Define business and security objectives**
2. **Define technical scope**
3. **Decompose the application**
4. **Perform threat analysis**
5. **Perform vulnerability analysis**
6. **Conduct attack modeling**
7. **Analyze risk and impact**

#### Other frameworks briefly referenced
- **STRIDE**
- **Trike**
- **VAST**

#### Key idea
Threat modeling helps security teams stay ahead of breaches by identifying risk before exploitation happens.

---

### Terms and Definitions from Module 4

**baiting**: A social engineering attack that lures a target with something enticing, such as a free file or device.

**cryptojacking**: The unauthorized use of a system's computing resources to mine cryptocurrency.

**cross-site scripting (XSS)**: An injection attack that inserts malicious code into a web application.

**malware**: Software designed to harm, exploit, or gain unauthorized access to systems.

**phishing**: A social engineering attack that uses deceptive communication to steal information or deliver malware.

**pretexting**: A social engineering technique in which an attacker invents a false scenario to gain trust or access.

**quid pro quo**: A social engineering attack that offers something in exchange for information or access.

**ransomware**: Malware that encrypts data and demands payment to restore access.

**social engineering**: A manipulation technique that exploits human behavior to gain access, information, or valuables.

**SQL injection**: A web attack that manipulates database queries through malicious input.

**tailgating**: Gaining unauthorized physical access by following an authorized person into a restricted area.

**threat modeling**: The process of identifying threats, vulnerabilities, and likely attack paths affecting an asset or system.

**trojan**: Malware that appears legitimate but performs malicious actions.

**watering hole attack**: An attack in which a site frequently visited by a target group is compromised to infect visitors.

**worm**: Malware that can self-replicate and spread without attaching to another file.

---

## Final Takeaways

- Asset security begins with understanding assets, threats, vulnerabilities, and risk
- Classification, security planning, and the NIST CSF help organizations decide what to protect and how
- Controls such as encryption, hashing, IAM, MFA, and least privilege help protect organizational assets
- Vulnerability management, defense in depth, and attacker mindset help identify weak points before they are exploited
- Social engineering, phishing, malware, and web exploits are common threats to digital assets
- Threat modeling frameworks such as PASTA help security professionals take a proactive approach to risk
