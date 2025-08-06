# Play It Safe: Manage Security Risks

## Description
**Play It Safe: Manage Security Risks**, the second course in the Google Cybersecurity Certificate.

By the end of this course, you will develop a greater understanding of the eight Certified Information Systems Security Professional (CISSP) security domains, as well as specific security frameworks and controls. You’ll also be introduced to how to use security tools and audits to help protect assets and data. These are key concepts in the cybersecurity field, and understanding them will help you keep organizations, and the people they serve, safe from threats, risks, and vulnerabilities.

---

## Module 1: Security domains
You will gain understanding of the CISSP’s eight security domains. Then, you'll learn about primary threats, risks, and vulnerabilities to business operations. In addition, you'll explore the National Institute of Standards and Technology’s (NIST) Risk Management Framework and the steps of risk management.

<img width="474" height="137" alt="image" src="https://github.com/user-attachments/assets/b90d045c-b02d-49e2-a462-8816491607e7" />

---

## Module 2: Security frameworks and controls 
You will focus on security frameworks and controls, along with the core components of the confidentiality, integrity, and availability (CIA) triad. You'll learn about Open Web Application Security Project (OWASP) security principles and security audits.

<img width="499" height="156" alt="image" src="https://github.com/user-attachments/assets/408a847f-e793-4c12-913e-34082714bc71" />

---

## Module 3: Introduction to cybersecurity tools
You will explore industry leading security information and event management (SIEM) tools that are used by security professionals to protect business operations. You'll learn how entry-level security analysts use SIEM dashboards as part of their every day work. 

<img width="502" height="143" alt="image" src="https://github.com/user-attachments/assets/31a00ae5-881e-414b-9035-c9e80789a487" />

---

## Module 4: Use playbooks to respond to incidents
You'll learn about the purposes and common uses of playbooks. You'll also explore how cybersecurity professionals use playbooks to respond to identified threats, risks, and vulnerabilities.

<img width="479" height="154" alt="image" src="https://github.com/user-attachments/assets/c535fa3a-6e29-494d-9ada-a5311302f6c1" />

---
---

## Module 1
### Security domains cybersecurity analysts need to know
As an analyst, you can explore various areas of cybersecurity that interest you. One way to explore those areas is by understanding different security domains and how they’re used to organize the work of security professionals. In this reading you will learn more about CISSP’s eight security domains and how they relate to the work you’ll do as a security analyst. 
<img width="542" height="483" alt="image" src="https://github.com/user-attachments/assets/0636b476-826a-4367-9764-a2428cd146fc" />

#### 1. Security & Risk Management
- **Security Posture**: Defend assets & adapt to change  
- **Key Elements**:  
  - Security goals, risk mitigation, compliance, business continuity  
  - Legal regulations, ethics  
- **InfoSec Processes**: Incident response, vulnerability management, cloud/application security  
- **Example**: GDPR compliance for PII handling  

#### 2. Asset Security
- **Focus**: Secure data lifecycle (storage, retention, destruction)  
- **Actions**: Backups, recovery plans, exposure management  

#### 3. Security Architecture & Engineering
- **Goal**: Secure systems via design principles  
- **Key Methods**:  
  - Least privilege, zero trust, defense in depth  
  - SIEM monitoring for threats  

#### 4. Communication & Network Security
- **Scope**: Physical/wireless networks (on-site/remote/cloud)  
- **Protections**: Access controls, secure remote connections  

#### 5. Identity & Access Management (IAM)
- **Core Principle**: Least privilege access  
- **Example**: Temporary data access for customer support  

#### 6. Security Assessment & Testing
- **Activities**: Penetration tests, vulnerability scans, audits  
- **Goal**: Identify risks before exploitation  

#### 7. Security Operations
- **Focus**: Incident response & prevention  
- **Tools**: SIEM, intrusion detection, forensics  
- **Process**: Playbooks, lessons learned  

#### 8. Software Development Security
- **Requirement**: Security at all SDLC stages  
- **Methods**: Secure coding, QA testing, encryption checks  

---

### Risk management  
The process of identifying, assessing, and controlling threats to an organization's assets  

A primary goal of organizations is to protect assets. An asset is an item perceived as having value to an organization. Assets can be digital or physical.  

#### Examples of digital assets include:  
Electronic data or systems that hold value:
- Social Security Numbers (SSNs)  
- Dates of birth  
- Bank account numbers  
- Mailing addresses  

#### Examples of physical assets include:  
Tangible items that require protection:
- Payment kiosks  
- Servers  
- Desktop computers  
- Office spaces  

#### Common risk management strategies:  
Approaches to handle potential threats:
- **Acceptance**: Acknowledging risk when mitigation costs outweigh impact  
- **Avoidance**: Eliminating activities that could trigger risk  
- **Transference**: Shifting risk to third parties (e.g., insurance)  
- **Mitigation**: Implementing controls to reduce risk impact  

#### Risk management frameworks:  
Standardized methodologies for risk assessment:
- **NIST RMF**: U.S. government standard for security controls  
- **HITRUST**: Healthcare-specific compliance framework  

---

### Today's most common threats, risks, and vulnerabilities  
Key categories of organizational exposures:

#### Threats  
Potential events/circumstances that can harm assets:
- **Insider threats**: Authorized users misusing access  
- **Advanced persistent threats (APTs)**: Long-term unauthorized access  

#### Risks  
Factors that could compromise CIA triad of assets:  
- **External risk**: Threats from outside the organization  
- **Internal risk**: Employees/vendors creating exposures  
- **Legacy systems**: Unsupported/outdated technology  
- **Multiparty risk**: Third-party vendor dependencies  
- **Software compliance**: Unpatched/license-violating systems  

#### Vulnerabilities  
Weaknesses that threats can exploit:
- **ProxyLogon**: Microsoft Exchange auth bypass  
- **ZeroLogon**: Windows Netlogon flaw  
- **Log4Shell**: Remote code execution in Java  
- **PetitPotam**: NTLM authentication hijacking  

### Key takeaways  
Core principles for security professionals:
- Continuous **monitoring** (SIEM, vulnerability scanners)  
- Timely **patching** of systems  
- Employee **training** against insider threats  
- Regular **audits** for risk assessment  

**Resources**:  
[NIST Database](https://nvd.nist.gov/) | [CISA Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)

---

### Terms and definitions from Module 1

**Assess**: The fifth step of the NIST RMF that means to determine if established controls are implemented correctly

**Authorize**: The sixth step of the NIST RMF that refers to being accountable for the security and privacy risks that may exist in an organization

**Business continuity**: An organization's ability to maintain their everyday productivity by establishing risk disaster recovery plans

**Categorize**: The second step of the NIST RMF that is used to develop risk management processes and tasks

**External threat**: Anything outside the organization that has the potential to harm organizational assets

**Implement**: The fourth step of the NIST RMF that means to implement security and privacy plans for an organization

**Internal threat**: A current or former employee, external vendor, or trusted partner who poses a security risk

**Monitor**: The seventh step of the NIST RMF that means be aware of how systems are operating

**Prepare**: The first step of the NIST RMF related to activities that are necessary to manage security and privacy risks before a breach occurs

**Ransomware**: A malicious attack where threat actors encrypt an organization's data and demand payment to restore access

**Risk**: Anything that can impact the confidentiality, integrity, or availability of an asset

**Risk mitigation**: The process of having the right procedures and rules in place to quickly reduce the impact of a risk like a breach

**Security posture**: An organization's ability to manage its defense of critical assets and data and react to change

**Select**: The third step of the NIST RMF that means to choose, customize, and capture documentation of the controls that protect an organization

**Shared responsibility**: The idea that all individuals within an organization take an active role in lowering risk and maintaining both physical and virtual security

**Social engineering**: A manipulation technique that exploits human error to gain private information, access, or valuables

**Vulnerability**: A weakness that can be exploited by a threat

---
---

## Module 2

### The relationship between frameworks and controls
Previously, you learned how organizations use security frameworks and controls to protect against threats, risks, and vulnerabilities. This included discussions about the National Institute of Standards and Technology’s (NIST’s) Risk Management Framework (RMF) and Cybersecurity Framework (CSF), as well as the confidentiality, integrity, and availability (CIA) triad. In this reading, you will further explore security frameworks and controls and how they are used together to help mitigate organizational risk.

#### Overview
Security frameworks and controls work together to mitigate organizational risks. Frameworks provide guidelines, while controls implement specific safeguards.

#### Security Frameworks
Guidelines for building risk mitigation plans that help organizations:
- Adhere to compliance laws (e.g., HIPAA for healthcare)
- Protect data and privacy
- Examples: NIST RMF, NIST CSF, CTF, ISO/IEC 27001

#### Security Controls
Safeguards that reduce specific security risks:
- Implemented alongside frameworks
- Three main types
  1. **Physical**: Gates, CCTV, access badges
  2. **Technical**: Firewalls, MFA, antivirus
  3. **Administrative**: Separation of duties, authorization policies
 
#### Key Takeaways
1. **Frameworks** = Strategic guidelines (e.g., NIST, ISO)
2. **Controls** = Tactical safeguards (physical/technical/admin)
3. Effective security requires both frameworks and controls

---

### OWASP Security Principles  
Open Worldwide Application Security Project is a non-profit foundation that works to improve software security.

#### Core Principles
- **Minimize attack surface**: Reduce exploitable vulnerabilities  
- **Least privilege**: Grant minimal necessary access  
- **Defense in depth**: Layer multiple security controls  
- **Separation of duties**: Split critical tasks across personnel  
- **Keep security simple**: Avoid complexity-induced risks  
- **Fix issues correctly**: Root cause analysis → remediation  

#### Additional Principles
1. **Secure defaults**
   - Default configurations = most secure state  
   - Example: Password complexity enabled by default  

2. **Fail securely**
   - Controls should default to "deny" on failure  
   - Example: Firewall blocks all traffic if crashes  

3. **Don’t trust services**
   - Verify third-party security (e.g., data validation)  
   - Example: Audit vendor APIs before integration  

4. **Avoid security by obscurity**
   - Never rely on secrecy (e.g., hidden code)  
   - Example: Open-source apps still need encryption/MFA  

#### Analyst Application
- Log analysis  
- SIEM monitoring  
- Vulnerability scanning  

**Reference**: [OWASP Top 10](https://owasp.org/www-project-top-ten/)

---

### Security Audits

A security audit is a review of an organization's security controls, policies, and procedures against a set of expectations. Audits are independent reviews that evaluate whether an organization is meeting internal and external criteria.

#### Key Aspects:
- **Internal criteria**: Outlined policies, procedures, and best practices
- **External criteria**: Regulatory compliance, laws, and federal regulations
- **Purpose**: Assess established security controls (safeguards designed to reduce specific security risks)

**Audits help ensure**:
- Daily monitoring of security information
- Identification of threats, risks, and vulnerabilities
- Maintenance of security posture
- Implementation of remediation processes for security issues

#### Primary Goal:
Ensure an organization's IT practices meet industry and organizational standards

#### Objectives:
- Identify and address areas of remediation and growth
- Provide direction by identifying current failures
- Develop correction plans
- Safeguard data
- Avoid governmental penalties and fines

*Note:* Audit frequency depends on local laws and federal compliance regulations.

#### Factors That Affect Audits
- Industry type
- Organization size
- Applicable government regulations
- Geographical location
- Business decisions on regulatory compliance

#### The Role of Frameworks and Controls in Audits

##### Frameworks:
- NIST CSF
- ISO 27000 series
- Help prepare for regulatory compliance audits
- Save time during internal/external audits

##### Controls:
Three main categories to review during audits:
1. Administrative/Managerial
2. Technical
3. Physical

*Resource:* [Control Categories](https://docs.google.com/document/d/1Ut_H5A9FHwuQEy6_qG6Lfy3zwF6GSJnj3DZTMaNRWEE/template/preview?resourcekey=0-i4dR5qZFqQyfzr8uk3OOmA)  

#### Audit Checklist

**Essential areas of focus**:

##### 1. Identify the Scope
- List assets to assess (firewall configurations, PII security, physical assets, etc.)
- Define audit's contribution to organizational goals
- Determine frequency
- Evaluate policy implementation effectiveness

##### 2. Complete a Risk Assessment
- Evaluate organizational risks regarding:
  - Budget
  - Controls
  - Internal processes
  - External standards/regulations

##### 3. Conduct the Audit
- Assess security of identified assets from scope

##### 4. Create a Mitigation Plan
- Strategy to:
  - Lower risk levels
  - Reduce potential costs/penalties
  - Improve security posture

##### 5. Communicate Results
- Provide detailed findings report
- Suggest improvements
- Highlight required compliance standards

#### Resources for More Information

- [Assessment and Auditing Resources](https://www.nist.gov/cyberframework/assessment-auditing-resources)
- [IT Disaster Recovery Plan](https://www.ready.gov/it-disaster-recovery-plan)

---

### Terms and definitions from Module 2

**Asset**: An item perceived as having value to an organization  

**Attack vectors**: The pathways attackers use to penetrate security defenses  

**Authentication**: The process of verifying who someone is  

**Authorization**: The concept of granting access to specific resources in a system  

**Availability**: The idea that data is accessible to those who are authorized to access it  

**Biometrics**: The unique physical characteristics that can be used to verify a person’s identity  

**Confidentiality**: The idea that only authorized users can access specific assets or data  

**Confidentiality, integrity, availability (CIA) triad**: A model that helps inform how organizations consider risk when setting up systems and security policies  

**Detect**: A NIST core function related to identifying potential security incidents and improving monitoring capabilities to increase the speed and efficiency of detections  

**Encryption**: The process of converting data from a readable format to an encoded format  

**Govern**: A NIST core function related to ensuring an organization establishes, oversees, and improves its cybersecurity strategy, policies, roles, and risk management processes to align with business goals and regulations  

**Identify**: A NIST core function related to management of cybersecurity risk and its effect on an organization’s people and assets  

**Integrity**: The idea that the data is correct, authentic, and reliable  

**National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF)**: A voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk  

**National Institute of Standards and Technology (NIST) Special Publication (S.P.) 800-53**: A unified framework for protecting the security of information systems within the U.S. federal government  

**Open Web Application Security Project/Open Worldwide Application Security Project (OWASP)**: A non-profit organization focused on improving software security  

**Protect**: A NIST core function used to protect an organization through the implementation of policies, procedures, training, and tools that help mitigate cybersecurity threats  

**Recover**: A NIST core function related to returning affected systems back to normal operation  

**Respond**: A NIST core function related to making sure that the proper procedures are used to contain, neutralize, and analyze security incidents, and implement improvements to the security process  

**Risk**: Anything that can impact the confidentiality, integrity, or availability of an asset  

**Security audit**: A review of an organization's security controls, policies, and procedures against a set of expectations  

**Security controls**: Safeguards designed to reduce specific security risks  

**Security frameworks**: Guidelines used for building plans to help mitigate risk and threats to data and privacy  

**Security posture**: An organization’s ability to manage its defense of critical assets and data and react to change  

**Threat**: Any circumstance or event that can negatively impact assets   

---
---

## Module 3

