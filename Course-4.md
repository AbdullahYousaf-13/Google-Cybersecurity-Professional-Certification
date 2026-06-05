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

### Terms and Definitions from Module 1

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
 
---
---

## Module 2

### Linux Architecture Explained
Understanding Linux architecture helps security analysts comprehend system organization and functionality. A task request flows through these components:

#### User
The person interacting with the computer. Linux supports multi-user environments where multiple users can share resources simultaneously.

#### Applications
**Programs performing specific tasks**:
- **Pre-installed**: Calculators, calendars
- **Installable**: Web browsers, email clients (via package managers)
- **Package Manager**: Tool for installing/managing software bundles (packages)

#### Shell
**The command-line interpreter that**:
- Translates user commands to machine-readable instructions
- Returns kernel responses in human-readable format
- Acts as a user-kernel interface

#### Filesystem Hierarchy Standard (FHS)
**Organizes data storage through**:
- **Directories** (folders): /bin (essential binaries), /etc (config files), /home (user files)
- Standardized locations for system files and user data

#### Kernel
**Core component that**:
- Manages processes and memory
- Routes commands between apps and hardware
- Controls all major hardware functions
- Allocates system resources efficiently

#### Hardware
**Physical computer components**:

##### Peripheral Devices
**Non-essential attached hardware**:
- Monitors, printers
- Keyboards, mice

##### Internal Hardware
**Core system components**:
- **Motherboard**: Main circuit board
- **CPU**: Executes program instructions
- **RAM**: Short-term memory (volatile)
- **Hard Drive**: Long-term storage (persistent)

#### Key Takeaways
1. Linux architecture components work sequentially:  
   User → Applications → Shell → FHS → Kernel → Hardware  
2. Each layer has distinct security implications  
3. Understanding this flow aids in troubleshooting and security analysis  
4. Kernel and FHS are unique to Linux's efficiency and organization

---

### Linux Distributions in Cybersecurity

Security analysts should be familiar with these key Linux distributions:

#### KALI LINUX
_(Trademark of OffSec)_  
**Type**: 
- Debian-based
- Open-source

**Primary Use**:  
- Penetration testing (simulated attacks to find vulnerabilities)  
- Digital forensics (post-attack data analysis)

**Features**:  
- Comes pre-installed with 600+ security tools  
- Standard distribution for security professionals  

#### Ubuntu  
**Type**:
- Debian-derived
- Open-source

**Primary Use**:  
- General security operations  
- Cloud computing environments

**Features**:  
- User-friendly with both CLI and GUI  
- Extensive package repository  
- Large community support  
- Common in enterprise cloud migrations  

#### Parrot  
**Type**: 
- Debian-based
- Open-source  

**Primary Use**:  
- Penetration testing  
- Digital forensics  
- Privacy-focused computing
  
**Features**:  
- Pre-loaded security tools (like KALI LINUX ™)  
- Lightweight OS options available  
- User-friendly GUI interface  

#### Red Hat® Enterprise Linux®  
**Type**:
- Enterprise
- Subscription-based  

**Primary Use**:  
- Large-scale enterprise systems  
- Mission-critical deployments
  
**Features**:  
- Commercial support available  
- Strong security certifications  
- Stable release cycles  

#### AlmaLinux  
**Type**: 
- Community-driven
- Open-source
 
**Primary Use**:  
- CentOS replacement  
- Enterprise environments

**Features**:  
- Binary-compatible with RHEL  
- Free alternative to Red Hat  
- Maintained by community  

#### Key Takeaways  
1. **Security Focus**: KALI LINUX ™ and Parrot specialize in penetration testing  
2. **Enterprise Use**: Red Hat and AlmaLinux target business environments  
3. **Versatility**: Ubuntu balances security with general computing needs  
4. **Cost Factors**: Most distributions are free except Red Hat  
5. **Transition**: AlmaLinux fills the gap left by CentOS discontinuation  

> **Note**: Trademarks belong to their respective owners (KALI LINUX ™ - OffSec, Red Hat® - IBM)

---

### Package Managers Overview

#### Core Concepts
- **Packages**: Software bundles (may include dependencies)
- **Package Managers**: Tools to install/update/remove software
- **Key Types**:
  - **Debian/Ubuntu**: `.deb` format (dpkg/APT)
  - **Red Hat/CentOS**: `.rpm` format (RPM/YUM)

#### Quick Commands
| Action          | Debian (APT)            | Red Hat (YUM)          |
|-----------------|-------------------------|------------------------|
| Install         | `sudo apt install pkg`  | `sudo yum install pkg` |
| Update          | `sudo apt update`       | `sudo yum update`      |
| Upgrade         | `sudo apt upgrade`      | `sudo yum upgrade`     |
| Remove          | `sudo apt remove pkg`   | `sudo yum remove pkg`  |

> **Security Tip**: Always update packages (`apt upgrade`/`yum update`) for latest security patches.

---

### Essential Linux Terminal Shortcuts

#### Command Control
| Shortcut       | Function                          |
|----------------|-----------------------------------|
| `CTRL + C`     | Stop current command              |
| `CTRL + V`     | Paste text                        |
| `CTRL + L`     | Clear screen (alternative to `clear`) |

#### Cursor Navigation
| Shortcut       | Function                          |
|----------------|-----------------------------------|
| `CTRL + A`     | Jump to line start                |
| `CTRL + E`     | Jump to line end                  |
| `← →`          | Move character by character       |

#### Command History
| Shortcut       | Function                          |
|----------------|-----------------------------------|
| `↑`            | Previous command                  |
| `↓`            | Next command (after using `↑`)    |

#### Auto-completion
| Shortcut       | Function                          |
|----------------|-----------------------------------|
| `TAB`          | Show completion suggestions       |

> **Note**: All shortcuts require cursor focus in terminal.

---

### Linux Shells Overview

#### Shell Basics
- **Function**: Acts as command-line interpreter (user-system translator)
- **Process**: 
  1. Interprets user commands
  2. Communicates with kernel
  3. Returns system responses

#### Common Shell Types
| Shell       | Indicator | Notable Features               |
|-------------|-----------|---------------------------------|
| **bash**    | `$`       | Default in most Linux distros   |
| **zsh**     | `%`       | Modern alternative to bash      |
| **ksh**     | `$`       | Combines features of bash/csh   |
| **csh**     | `%`       | C-like syntax                   |
| **tcsh**    | `%`       | Enhanced csh with completion    |

#### Why Bash Dominates Cybersecurity
- Pre-installed on nearly all Linux systems
- Consistent behavior across distributions
- Extensive scripting capabilities
- Default shell for most security tools

> **Course Note**: All exercises will use bash (indicated by `$` prompt)

#### Key Takeaways
1. Shells bridge user commands and system operations
2. Bash is industry standard for security work
3. Shell differences mainly affect advanced functionality
4. Prompt symbols vary (`$` for bash/ksh, `%` for zsh/csh)

---

### Terms and Definitions from Module 2

**Application**: A program that performs a specific task.

**Bash**: The default shell in most Linux distributions.

**CentOS**: An open-source distribution that is closely related to Red Hat.

**Central Processing Unit (CPU)**: A computer's main processor, which is used to perform general computing tasks on a computer.

**Command**: An instruction telling the computer to do something.

**Digital forensics**: The practice of collecting and analyzing data to determine what has happened after an attack.

**Directory**: A file that organizes where other files are stored.

**Distributions**: The different versions of Linux.

**File path**: The location of a file or directory.

**Filesystem Hierarchy Standard (FHS)**: The component of the Linux OS that organizes data.

**Graphical user interface (GUI)**: A user interface that uses icons on the screen to manage different tasks on the computer.

**Hard drive**: A hardware component used for long-term memory.

**Hardware**: The physical components of a computer.

**Internal hardware**: The components required to run the computer.

**Kali Linux ™**: An open-source distribution of Linux that is widely used in the security industry.

**Kernel**: The component of the Linux OS that manages processes and memory.

**Linux**: An open source operating system.

**Package**: A piece of software that can be combined with other packages to form an application.

**Package manager**: A tool that helps users install, manage, and remove packages or applications.

**Parrot**: An open-source distribution that is commonly used for security.

**Penetration test (pen test)**: A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes.

**Peripheral devices**: Hardware components that are attached and controlled by the computer system.

**Random Access Memory (RAM)**: A hardware component used for short-term memory.

**Red Hat® Enterprise Linux®**: A subscription-based distribution of Linux built for enterprise use.

**Shell**: The command-line interpreter.

**Standard error**: An error message returned by the OS through the shell.

**Standard input**: Information received by the OS via the command line.

**Standard output**: Information returned by the OS through the shell.

**String data**: Data consisting of an ordered sequence of characters.

**Ubuntu**: An open-source, user-friendly distribution that is widely used in security and other industries.

**User**: The person interacting with a computer.

---
---

## Module 3

### Linux Filesystem Navigation and File Reading

#### Filesystem Hierarchy Standard (FHS)
- **Root Directory**:
  - `/` (base of all directories)
- **Key Directories**:
  - `/home`: User directories
  - `/bin`: Essential binaries
  - `/etc`: Configuration files
  - `/tmp`: Temporary files (common attack target)
  - `/mnt`: Mounted devices

#### Navigation Commands
| Command  | Function                | Example              |
|----------|-------------------------|----------------------|
| `pwd`    | Show current directory  | `pwd` → `/home/user` |
| `ls`     | List directory contents | `ls /var/log`        |
| `cd`     | Change directory        | `cd ~/projects`      |
| `whoami` | Show current user       | `whoami` → `analyst` |

#### Path Notations
- `~` = Home directory
- `.` = Current directory
- `..` = Parent directory

#### File Reading Commands
| Command | Function            | Options              |
|---------|---------------------|----------------------|
| `cat`   | Display entire file | `cat log.txt`        |
| `head`  | Show first lines    | `head -n 5 file.txt` |
| `tail`  | Show last lines     | `tail -f live.log`   |
| `less`  | Page through file   | `less largefile.txt` |

#### Less Navigation
- `Space`: Next page
- `b`: Previous page
- `↑/↓`: Line navigation
- `q`: Quit

#### Pro Tips
1. Use `man hier` for FHS details
2. `tail -f` monitors growing log files
3. Absolute paths start with `/`, relative paths don't
4. `/tmp` is world-writable - handle with care

---

### Filtering Content in Linux

#### grep Commands
| Command | Function | Example |
|---------|----------|---------|
| `grep`  | Search text in file | `grep OS updates.txt` |
|         | Search error keyword | `grep error time_logs.txt` |

#### Piping (`|`)
| Symbol | Function                    | Example                                  |
|--------|-----------------------------|------------------------------------------|
| `\|`   | Send output to next command | `ls /home/analyst/reports \| grep users` |

> **Note**: Pipe (`|`) sends command output as input to another.

#### find Commands
| Command                 | Function               | Example                                     |
|-------------------------|------------------------|---------------------------------------------|
| `find [path] [options]` | Search files/dirs      | `find /home/analyst/projects -name "*log*"` |
| `-name`                 | Case-sensitive match   | `find /dir -name "*txt*"`                   |
| `-iname`                | Case-insensitive match | `find /dir -iname "*txt*"`                  |
| `-mtime`                | Modified by days       | `find /dir -mtime -3`                       |
| `-mmin`                 | Modified by minutes    | `find /dir -mmin -60`                       |

---

### Linux File & Directory Management

#### Directory Commands
| Command | Function               | Example                            |
|---------|------------------------|------------------------------------|
| `mkdir` | Create directory       | `mkdir /home/analyst/logs/network` |
| `rmdir` | Remove empty directory | `rmdir /home/analyst/logs/network` |

#### File Commands
| Command | Function                | Example                                 |
|---------|-------------------------|-----------------------------------------|
| `touch` | Create empty file       | `touch permissions.txt`                 |
| `rm`    | Delete file             | `rm permissions.txt`                    |
| `mv`    | Move/Rename file or dir | `mv permissions.txt /home/analyst/logs` |
| `cp`    | Copy file or dir        | `cp permissions.txt /home/analyst/logs` |

#### nano Text Editor
| Action    | Shortcut/Command    |
|-----------|---------------------|
| Open file | `nano filename.txt` |
| Save      | `Ctrl + O`          |
| Exit      | `Ctrl + X`          |

#### Output Redirection
| Symbol | Function       | Example                                       |
|--------|----------------|-----------------------------------------------|
| `>`    | Overwrite file | `echo "time" > permissions.txt`               |
| `>>`   | Append to file | `echo "last updated date" >> permissions.txt` |

---

### Permission commands
Previously explored file permissions and the commands used to display and change them, with a focus on applying the principle of least privilege.

#### Reading permissions
Permissions in Linux are represented with a **10-character string**.  
- **read (r)**: Files – read contents; Directories – list contents.  
- **write (w)**: Files – modify contents; Directories – create/delete files.  
- **execute (x)**: Files – run as program; Directories – enter and access files.  

**Owner types**:  
- **user (u)**: Owner of the file.  
- **group (g)**: Group the owner is part of.  
- **other (o)**: All other users.

##### 10-character string breakdown
| Position | Example    | Meaning                                        | 
|----------|------------|------------------------------------------------|
| 1st      | drwxrwxrwx | File type: `d` = directory, `-` = regular file |
| 2nd      | drwxrwxrwx | User read (`r` / `-`)                          |
| 3rd      | drwxrwxrwx | User write (`w` / `-`)                         |
| 4th      | drwxrwxrwx | User execute (`x` / `-`)                       |
| 5th      | drwxrwxrwx | Group read (`r` / `-`)                         |
| 6th      | drwxrwxrwx | Group write (`w` / `-`)                        |
| 7th      | drwxrwxrwx | Group execute (`x` / `-`)                      |
| 8th      | drwxrwxrwx | Other read (`r` / `-`)                         |
| 9th      | drwxrwxrwx | Other write (`w` / `-`)                        |
| 10th     | drwxrwxrwx | Other execute (`x` / `-`)                      |

#### Exploring existing permissions
The `ls` command can display permissions. Useful options:  
- **`ls -a`**: Show hidden files (start with `.`).  
- **`ls -l`**: Show permissions, owner, group, size, last modified time.  
- **`ls -la`**: Combine both – includes hidden files with details.

#### Changing permissions
The **principle of least privilege** ensures users only have necessary access.

The `chmod` command changes file/directory permissions.

##### Using chmod
Syntax: `chmod [who][operator][permissions] filename`  
| Component   | Options       | Meaning                     |
|-------------|---------------|-----------------------------|
| Who         | `u`, `g`, `o` | user, group, other          |
| Operator    | `+`, `-`, `=` | add, remove, assign exactly |
| Permissions | `r`, `w`, `x` | read, write, execute        |

##### Common chmod Examples
| Command                          | Meaning                                                         | 
|----------------------------------|-----------------------------------------------------------------|
| chmod u+rwx,g+rwx,o+rwx file.txt | Add all permissions for all                                     |
| chmod u-rwx,g-rwx,o-rwx file.txt | Remove all permissions from all                                 |
| chmod u=r,g=r,o=r file.txt       | Set read-only for all                                           |
| chmod u+r,g-w,o=r file.txt       | Add read for user, remove write from group, set read for others |

##### The principle of least privilege in action
Example scenario:  
- File: `bonuses.txt`, owned by `hrrep1` (Human Resources)  
- Initial permissions: `-rw-rw----` → user and group have read/write  
- Requirement: Only `hrrep1` should have access  
- Fix:  
`chmod g-rw bonuses.txt`  

> Now only the owner has required permissions.

##### Key takeaways
- Use `ls -l` or `ls -la` to check permissions  
- Use `chmod` to modify them according to the principle of least privilege  
- Understand permission strings to manage file security effectively

---

Add and delete users

Managing users is an important part of system administration and cybersecurity. Analysts need to understand how users are created, modified, and removed so they can help enforce access control.

#### Superuser privileges
Some user management tasks require elevated privileges.

- **root**: The superuser account with full system access
- **sudo**: Temporarily grants elevated privileges to approved users

> **Security Note**: Use `sudo` only when necessary and follow the principle of least privilege.

#### User management commands
| Command | Function | Example |
|---------|----------|---------|
| `useradd` | Add a new user | `sudo useradd analyst1` |
| `userdel` | Delete a user | `sudo userdel analyst1` |
| `usermod` | Modify a user | `sudo usermod -g security analyst1` |
| `passwd` | Set or change password | `sudo passwd analyst1` |
| `id` | Display user and group IDs | `id analyst1` |

#### Common options
| Option | Used With | Function |
|--------|-----------|----------|
| `-m` | `useradd` | Create a home directory |
| `-d` | `useradd` | Specify home directory |
| `-g` | `usermod` | Change primary group |
| `-G` | `usermod` | Assign supplementary groups |
| `-r` | `userdel` | Remove home directory with user |

#### Example workflow
##### Add a new user
`sudo useradd -m analyst1`

##### Set the user's password
`sudo passwd analyst1`

##### Add the user to a group
`sudo usermod -G security analyst1`

##### Delete the user later
`sudo userdel -r analyst1`

#### Why this matters in cybersecurity
- Limits unnecessary access
- Helps track accountability by user account
- Reduces risk from shared or excessive privileges

#### Key takeaways
- Use `useradd`, `usermod`, and `userdel` for account management
- Elevated privileges are usually required for these tasks
- Proper account management supports secure authentication and authorization

---

### Ownership and Authentication in Linux

In Linux, files and directories are associated with owners and groups. Security analysts need to understand ownership because it directly affects access control.

#### File and directory ownership
Every file has:
- A **user owner**
- A **group owner**

The `ls -l` command displays both.

Example:
`-rw-r----- 1 analyst1 security 120 report.txt`

In this example:
- `analyst1` is the user owner
- `security` is the group owner

#### Ownership commands
| Command | Function | Example |
|---------|----------|---------|
| `chown` | Change file owner | `sudo chown analyst1 report.txt` |
| `chgrp` | Change group owner | `sudo chgrp security report.txt` |

#### Changing owner and group together
`sudo chown analyst1:security report.txt`

#### Authentication vs. Authorization
These two terms are closely related but different:

##### Authentication
Verifies identity.
- Example: Logging in with a username and password

##### Authorization
Determines what a user is allowed to do.
- Example: Whether a user can read or modify a file

#### Why ownership matters
- Controls who can access sensitive files
- Supports separation of duties
- Helps enforce the principle of least privilege

#### Key takeaways
- `chown` changes the owner of a file or directory
- `chgrp` changes the group ownership
- Authentication confirms identity, while authorization controls access

---

### Getting Help in Linux

Security analysts frequently work with unfamiliar commands. Linux provides built-in tools to learn command usage directly from the terminal.

#### Help resources
| Command | Function | Example |
|---------|----------|---------|
| `man` | Open manual page | `man chmod` |
| `whatis` | Short command description | `whatis grep` |
| `apropos` | Search manual page descriptions | `apropos password` |
| `help` | Help for shell built-ins | `help cd` |

#### Manual pages
The `man` command opens a manual page for a command.

Example:
`man grep`

Useful navigation inside `man`:
- `Space`: Next page
- `b`: Previous page
- `/word`: Search for text
- `q`: Quit

#### Why help commands matter
- Reduce mistakes when using powerful commands
- Improve efficiency during investigations
- Provide fast access to syntax and options

#### Key takeaways
- `man` is the primary command reference in Linux
- `help` is useful for shell built-ins like `cd`
- `whatis` and `apropos` help when you know little or only part of a command's purpose

---

### Terms and Definitions from Module 3

**Absolute file path**: The full path to a file or directory starting from the root directory.

**Authentication**: The process of verifying who someone is.

**Authorization**: The concept of granting access to specific resources in a system.

**chmod**: A Linux command used to change permissions on files and directories.

**chown**: A Linux command used to change the owner of a file or directory.

**current working directory**: The directory that a user is currently in.

**grep**: A Linux command used to search for specific text in a file.

**hidden file**: A file in Linux that begins with a period (`.`).

**id**: A Linux command that displays user and group identification information.

**least privilege**: The concept of granting only the minimum access and authorization required to complete a task or function.

**man**: A Linux command that displays the manual page for another command.

**relative file path**: A path to a file or directory that starts from the user's current working directory.

**root directory**: The highest-level directory in the Linux filesystem, represented by `/`.

**sudo**: A command that temporarily grants elevated permissions.

**useradd**: A Linux command used to create a new user account.

**userdel**: A Linux command used to remove a user account.

**usermod**: A Linux command used to modify an existing user account.

---
---

## Module 4

### Introduction to Databases

Databases help store, organize, and retrieve information efficiently. In cybersecurity, analysts often use databases to review logs, investigate events, and monitor assets.

#### What is a database?
A **database** is an organized collection of information or data.

Examples of data stored in databases:
- Employee records
- Login events
- Device inventories
- Security alerts

#### Why databases matter in cybersecurity
- Store large amounts of structured information
- Make searching and reporting faster
- Support investigation and monitoring workflows

#### Relational databases
A **relational database** organizes data into tables.

Each table contains:
- **Rows**: Individual records
- **Columns**: Specific attributes of those records

Example:

| employee_id | name   | department |
|-------------|--------|------------|
| 101         | Aisha  | Security   |
| 102         | Hamza  | IT         |

#### Database management systems
A **database management system (DBMS)** is software used to create, manage, and interact with databases.

Common examples:
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server
- SQLite

#### Key takeaways
- Databases store and organize data for efficient access
- Relational databases use tables, rows, and columns
- DBMS tools make it possible to manage and query stored data

---

### SQL Basics

**Structured Query Language (SQL)** is used to communicate with relational databases. Security analysts use SQL to retrieve, filter, and analyze data.

#### Common SQL statements
| Statement | Function |
|-----------|----------|
| `SELECT`  | Retrieve data from a table |
| `FROM`    | Specify the table to query |
| `ORDER BY`| Sort query results |

#### Basic query structure
```sql
SELECT column1, column2
FROM table_name;
```

#### Example queries
##### Select all columns
```sql
SELECT *
FROM employees;
```

##### Select specific columns
```sql
SELECT name, department
FROM employees;
```

##### Sort results
```sql
SELECT name, department
FROM employees
ORDER BY name;
```

#### `ORDER BY` options
| Keyword | Function |
|---------|----------|
| `ASC`   | Sort in ascending order |
| `DESC`  | Sort in descending order |

Example:
```sql
SELECT username, login_time
FROM logins
ORDER BY login_time DESC;
```

#### Key takeaways
- SQL is used to interact with relational databases
- `SELECT` retrieves data
- `FROM` identifies the table
- `ORDER BY` sorts the output

---

### Filter a SQL Query

Filtering helps analysts focus only on the records they need. This is especially useful when reviewing large datasets.

#### The `WHERE` clause
The `WHERE` clause filters records based on specified conditions.

```sql
SELECT *
FROM employees
WHERE department = 'Security';
```

#### Comparison operators
| Operator | Meaning |
|----------|---------|
| `=`      | Equal to |
| `!=`     | Not equal to |
| `>`      | Greater than |
| `<`      | Less than |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to |

#### Filter by numeric value
```sql
SELECT *
FROM employees
WHERE employee_id > 200;
```

#### Filter by date
```sql
SELECT *
FROM logins
WHERE login_date = '2025-10-19';
```

#### Combining conditions
| Operator | Function |
|----------|----------|
| `AND`    | Both conditions must be true |
| `OR`     | At least one condition must be true |
| `NOT`    | Excludes a condition |

Example with `AND`:
```sql
SELECT *
FROM logins
WHERE department = 'Security'
AND login_status = 'Failed';
```

Example with `OR`:
```sql
SELECT *
FROM employees
WHERE department = 'Security'
OR department = 'IT';
```

#### Pattern matching with `LIKE`
| Wildcard | Function |
|----------|----------|
| `%`      | Matches zero or more characters |
| `_`      | Matches exactly one character |

Example:
```sql
SELECT *
FROM employees
WHERE name LIKE 'A%';
```

#### Range and list filtering
##### `BETWEEN`
```sql
SELECT *
FROM logins
WHERE login_hour BETWEEN 8 AND 17;
```

##### `IN`
```sql
SELECT *
FROM employees
WHERE department IN ('Security', 'IT', 'HR');
```

#### Key takeaways
- `WHERE` filters rows based on conditions
- `AND`, `OR`, and `NOT` combine or exclude conditions
- `LIKE`, `BETWEEN`, and `IN` make filtering more flexible

---

### More SQL Filters

Additional SQL filters help analysts work with missing values, sort through event data, and narrow investigations efficiently.

#### `IS NULL` and `IS NOT NULL`
Used to find missing or available values.

```sql
SELECT *
FROM employees
WHERE phone_number IS NULL;
```

```sql
SELECT *
FROM assets
WHERE assigned_user IS NOT NULL;
```

#### Filtering with multiple conditions
Parentheses help control logic in more complex queries.

```sql
SELECT *
FROM logins
WHERE (department = 'Security' OR department = 'IT')
AND login_status = 'Failed';
```

#### Why this matters in cybersecurity
- Identify failed logins
- Detect incomplete asset records
- Narrow incident data quickly

#### Key takeaways
- Use `IS NULL` to locate missing values
- Use parentheses to clarify logic in combined conditions
- Careful filtering improves investigation accuracy

---

### Join Tables with SQL

Data is often stored across multiple related tables. SQL joins allow analysts to combine that data in a single query.

#### Why joins are useful
One table may store employee information, while another stores login activity. A join connects related records using a shared column.

#### Common join concept
- **Primary key**: A column that uniquely identifies each record in a table
- **Foreign key**: A column in one table that references a primary key in another table

#### `INNER JOIN`
Returns only rows with matching values in both tables.

```sql
SELECT employees.name, logins.login_time
FROM employees
INNER JOIN logins
ON employees.employee_id = logins.employee_id;
```

#### `LEFT JOIN`
Returns all rows from the left table and matching rows from the right table.

```sql
SELECT employees.name, devices.device_name
FROM employees
LEFT JOIN devices
ON employees.employee_id = devices.employee_id;
```

#### Join use cases in cybersecurity
- Match users with login records
- Associate devices with owners
- Connect alerts to affected systems

#### Key takeaways
- Joins combine data from multiple tables
- `INNER JOIN` returns matching records only
- `LEFT JOIN` keeps all records from the left table
- Shared key fields connect related data

---

### Terms and Definitions from Module 4

**AND**: An operator that specifies that both conditions in a filter must be true.

**column**: A vertical set of values in a table that represents one attribute of the stored data.

**database**: An organized collection of information or data.

**DBMS (database management system)**: Software used to create, manage, and interact with databases.

**filter**: A condition used to limit the rows returned by a query.

**foreign key**: A column in one table that refers to the primary key in another table.

**INNER JOIN**: A join that returns only rows with matching values in both tables.

**LIKE**: An operator used to search for a pattern in a value.

**OR**: An operator that specifies that at least one condition in a filter must be true.

**primary key**: A column that uniquely identifies each row in a table.

**query**: A request for data from a database.

**relational database**: A database that stores data in tables.

**row**: A single record in a table.

**SQL (Structured Query Language)**: A language used to communicate with relational databases.

**table**: A collection of related data organized into rows and columns.

**WHERE**: A SQL clause used to filter records.

---

## Final Takeaways

- Linux and SQL are foundational tools for security analysts
- Linux supports system navigation, permissions management, and user administration
- The command line provides speed, flexibility, and auditability
- SQL helps analysts retrieve, filter, and join large amounts of structured data
- Together, Linux and SQL improve investigation, monitoring, and incident response capabilities

---
---
---