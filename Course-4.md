# Tools of the Trade: Linux and SQL

## Description
**Tools of the Trade: Linux and SQL**, the fourth course in the Google Cybersecurity Certificate.

By the end of this course, you will develop a greater understanding of the basics of computing that will support your work as a security analyst. You will learn foundational concepts related to understanding operating systems, communicating with the Linux operating system through commands, and querying databases with Structured Query Language (SQL). These are key concepts in the cybersecurity field and understanding them will help you keep organizations secure.

---

## Module 1: Introduction to operating systems
You will learn about the relationship between operating systems, hardware, and software, and become familiar with the primary functions of an operating system. You'll recognize common operating systems in use today and understand how the graphical user interface (GUI) and command-line interface (CLI) both allow users to interact with the operating system.

<img width="509" height="133" alt="image" src="https://github.com/user-attachments/assets/24a149b5-f4a0-4905-814b-5291e06244d2" />

---

## Module 2:  The Linux operating system
You will be introduced to the Linux operating system and learn how it is commonly used in cybersecurity. You’ll also learn about Linux architecture and common Linux distributions. In addition, you'll be introduced to the Linux shell and learn how it allows you to communicate with the operating system.

<img width="506" height="136" alt="image" src="https://github.com/user-attachments/assets/239f2870-3f98-4186-b094-2418b8f8cd5d" />

---

## Module 3: Linux commands in the Bash shell
You will be introduced to Linux commands as entered through the Bash shell. You'll use the Bash shell to navigate and manage the file system and to authorize and authenticate users. You'll also learn where to go for help when working with new Linux commands.

<img width="511" height="148" alt="image" src="https://github.com/user-attachments/assets/51479d77-771d-4ad3-a42d-049b12bdcc17" />

---

Module 4: Databases and SQL 
You will practice using SQL to communicate with databases. You'll learn how to query a database and filter the results. You’ll also learn how SQL can join multiple tables together in a query.

<img width="507" height="140" alt="image" src="https://github.com/user-attachments/assets/7a981f86-e24d-40ac-9c24-aac5d31e8095" />

---
---

## Module 1
### Operating Systems
It's the interface between the computer hardware and the user. The operating system, or the OS as it's commonly called, is responsible for making the computer run as efficiently as possible while also making it easy to use. 

#### Major OS Categories
##### 1. Desktop OS
   - Windows (closed-source)  
   - macOS (partially open-source)  
   - Linux distributions (open-source)  

##### 2. Mobile OS
   - Android (open-source)  
   - iOS (partially open-source)  

##### 3. Cloud/Web-based OS
   - ChromeOS (partially open-source) 

#### Security Risks by Type
##### Desktop Systems
- Frequent target for malware
- Requires regular patching
- Enterprise deployments need centralized management

##### Mobile Systems
- App store vulnerabilities
- Device fragmentation issues
- Physical security concerns

##### Legacy Systems
- No security updates available
- Vulnerable to modern exploits
- Often found in industrial/medical equipment

#### Requests to the Operating System  
Operating systems bridge applications and hardware, enabling users to perform tasks efficiently. This process involves booting the computer and managing task execution through a structured workflow.  

##### Booting the Computer  
When a computer powers on, either a **BIOS** (Basic Input/Output System) or **UEFI** (Unified Extensible Firmware Interface) microchip initializes. These chips contain loading instructions, such as hardware health checks.  

###### BIOS vs. UEFI  
- **BIOS**: Found in older systems, it handles basic boot instructions.  
- **UEFI**: Modern replacement for BIOS with enhanced security features.  

###### Bootloader Activation  
The final instruction from BIOS/UEFI activates the **bootloader**, a program that loads the operating system. Once booted, the computer is ready for use.  

#### Completing a Task  
Tasks follow a four-step process:  

##### 1. User  
Initiates the task (e.g., downloading a file or opening an application).  

##### 2. Application  
Software (e.g., browser, calculator) interprets the user’s request and relays it to the OS.  

##### 3. Operating System  
Receives the request, directs it to the appropriate hardware components, and manages execution.  

##### 4. Hardware  
Processes the task (e.g., CPU calculates, hard drive saves files) and returns output through the OS to the application.  

<img width="716" height="132" alt="image" src="https://github.com/user-attachments/assets/93fe08ea-8656-41f7-b3c7-33b52bb42a0d" />

#### Vulnerability Resources
Even when operating systems are kept up to date, they can still become vulnerable to attack. Below are several resources that include information on operating systems and their vulnerabilities.
- [Microsoft Security Response Center](https://msrc.microsoft.com)
- [Apple Security Updates](https://support.apple.com/en-us/HT201222)
- [CVE Report for Ubuntu](https://ubuntu.com/security/cve)
- [Google Cloud Security Bulletin](https://cloud.google.com/support/bulletins)

#### Key Takeaways
- Windows/macOS dominate enterprise environments  
- Linux critical for security tools  
- Mobile OS require special security considerations  
- Legacy systems create significant risk  
- Regular updates are essential for security
- The OS seamlessly connects applications and hardware.  
- Boot processes (BIOS/UEFI → bootloader) prepare the system.  
- Task execution flows through user → application → OS → hardware.

---  

### Virtualization Technology  
Virtualization enables operating systems to run on virtual machines (VMs), enhancing security and efficiency. This section explores VMs, their benefits, and management tools.  

#### What is a Virtual Machine?  
A **virtual machine (VM)** is a software-emulated computer with virtualized CPU, storage, and hardware. It operates on a physical host machine while sharing its resources (e.g., RAM, CPU).  

<img width="685" height="381" alt="image" src="https://github.com/user-attachments/assets/b136b1b8-19ca-4193-99a1-c0f958b490cd" />

##### Key Features:  
- **Shared Resources**: A single host can run multiple VMs (e.g., 16GB RAM split across 3 VMs).  
- **Isolated OS**: Each VM runs its own operating system independently.  
- **Software-Defined**: VMs exist as code, not physical hardware.  

#### Benefits of Virtual Machines  

##### 1. Security  
- **Sandboxing**: VMs provide isolated environments ("guests") to contain threats like malware.  
- **Risk Note**: Malware may escape virtualization (never fully trust VMs).  

##### 2. Efficiency  
- **Resource Optimization**: Like a city bus carrying multiple passengers, one host machine runs multiple VMs, reducing hardware needs.  
- **Task Streamlining**: Switch between VMs for testing or running diverse applications.  

#### Managing Virtual Machines  
VMs are managed via **hypervisors**, software that allocates host resources to VMs.  

##### Kernel-based Virtual Machine (KVM)  
- **Open-source hypervisor** integrated into Linux kernels.  
- No additional software needed for Linux-based VM creation.  

#### Other Forms of Virtualization  
Beyond VMs, virtualization extends to:  
- **Virtual servers**: Multiple servers on one physical machine.  
- **Virtual networks**: Optimized use of physical network hardware.  

### Key Takeaways  
- VMs are software-based, isolated computers sharing host resources.  
- Benefits include **security** (sandboxing) and **efficiency** (resource sharing).  
- **Hypervisors** (e.g., KVM) manage VM-physical hardware interactions.  
- Risks exist (e.g., malware escape), so VMs require cautious use.  

---

### The Command Line in Use  
Security analysts work with both graphical (GUI) and command-line interfaces (CLI). This section compares their features and highlights CLI advantages in cybersecurity.

#### CLI vs. GUI  

<img width="747" height="249" alt="image" src="https://github.com/user-attachments/assets/b088bae4-a4f5-4148-a90c-4e14c8685f8e" />

##### Display  
- **GUI**: Visual interface with icons, windows, and menus (e.g., desktop shortcuts).  
- **CLI**: Text-only interface resembling code lines.  

##### Function  
- **GUI**: Single-request operations (one action at a time).  
- **CLI**: Supports multiple simultaneous commands.  

#### Advantages of CLI in Cybersecurity  

##### 1. Efficiency  
- **Speed**: Faster task execution for experienced users (e.g., creating multiple files).  
- **Multi-tasking**: Run batch commands vs. repetitive GUI steps.  

##### 2. History File  
- **Audit Trail**: Linux CLI logs all commands, enabling:  
  - Playbook verification during incident response.  
  - Attacker action tracing in compromised systems.  
- **GUI Limitation**: Actions aren’t systematically recorded.  

#### Use Case Example  
- **Scenario**: Following an incident response playbook.  
- **CLI Benefit**: Review `history` to confirm correct command execution.  

### Key Takeaways  
- **GUI**: Beginner-friendly for single tasks.  
- **CLI**: Preferred for cybersecurity due to:  
  - Batch processing capabilities.  
  - Built-in command history for auditing.
 
---

### Terms and Definitions

**Application**: A program that performs a specific task.

**Basic Input/Output System (BIOS)**: A microchip that contains loading instructions for the computer and is prevalent in older systems.

**Bootloader**: A software program that boots the operating system.

**Command-line interface (CLI)**: A text-based user interface that uses commands to interact with the computer.

**Graphical user interface (GUI)**: A user interface that uses icons on the screen to manage different tasks on the computer.

**Hardware**: The physical components of a computer.

**Legacy operating system**: An operating system that is outdated but still being used.

**Operating system (OS)**: The interface between computer hardware and the user.

**Random Access Memory (RAM)**: A hardware component used for short-term memory.

**Unified Extensible Firmware Interface (UEFI)**: A microchip that contains loading instructions for the computer and replaces BIOS on more modern systems.

**User interface**: A program that allows the user to control the functions of the operating system.

**Virtual machine (VM)**: A virtual version of a physical computer.
