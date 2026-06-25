[NL](nl.html) | [Français](fr.html) | English

# Future Systems & Network Administrator

Hello! My name is **Thibaut Blondeel**, a passionate IT student who, after the summer, will begin his second and final year of a graduate degree in **Systems and Network Administration** at HOGENT. 

My journey in IT began with a solid foundation in Accounting-IT (Sint-Catharinacollege Geraardsbergen). Although I initially started a Bachelor's degree in Applied Computer Science, I quickly realized that my strength lay in a highly practical approach. Knowing, moreover, that my true passion was in systems and network administration, I deliberately chose to pivot to this two-year graduate program, which is very concrete and hands-on. I have now successfully completed my first year.

Outside of my studies, I am an active *homelabber*. I manage my own Linux servers and NAS at home, experiment with containerization (Docker), and configure network environments as well as smart home automation. 

I am currently looking for a challenging internship for my final year, where I can deploy and perfect my practical and corporate skills.

---

## 💻 Technical Profile & Skills

Recruiters often look for specific roles within an IT team. Below you will find my skills classified according to the areas of expertise I developed during my training and enterprise projects.

### 1. Systems Management & Cloud (Systems Engineer)
I am operational in management, virtualization, and setting up on-premises and cloud infrastructures.

| Domain | Technologies & Concepts |
| :--- | :--- |
| **Windows Server** | Active Directory (AD DS), GPO, AGDLP permission structure, WSUS, Windows Server 2022/2025 |
| **Linux Administration** | Ubuntu Server, CentOS (fully headless CLI), LVM disk management, Vim/Nano, grep, Apache |
| **Virtualization & Cloud** | Proxmox VE (Clusters & Live Migration), Nutanix Prism Central, Hyper-V HA Clustering, VirtualBox |
| **Microsoft Azure & M365** | Azure Architecture & Governance, Entra ID, Microsoft Intune, Windows Autopilot, Conditional Access |
| **Automation / IaC** | Cloud-init, Docker-Compose (YAML), Terraform, Azure Bicep, Power Automate, PowerShell |

### 2. Network Infrastructure & Firewalls (Network Engineer)
I possess the theoretical and practical knowledge to structure, route, and secure enterprise networks.

| Domain | Technologies & Concepts |
| :--- | :--- |
| **Cisco Networking** | Cisco IOS CLI, VLANs, Trunking (802.1Q), Router-on-a-Stick, EtherChannel (LACP/PAgP) |
| **Routing Protocols** | Single-area OSPFv2, HSRP (Gateway Redundancy), Static Routing |
| **Network Security** | Switchport Security, DHCP Snooping, Dynamic ARP Inspection, Access Control Lists (ACL) |
| **Next-Gen Firewalls** | Palo Alto Networks NGFW (PAN-OS), pfSense (DMZ & Perimeter Routing), FortiGate, Tailscale |
| **Core Network Services** | DHCP Failover (Load Balance / Hot Standby), BIND9 DNS, Enterprise DNS Zone Transfers |

### 3. Cybersecurity & Observability (Security & Operations)
I have active experience in infrastructure and service monitoring, as well as network security validation through auditing.

| Domain | Technologies & Concepts |
| :--- | :--- |
| **Monitoring / Observability**| **Zabbix** (Infrastructure & service monitoring), `/var/log` audits, Query Store performance tuning |
| **Business Continuity** | **Proxmox Backup Server (PBS)** (Deduplication & Full Restore), Database DR (Full/Diff/Log Backups) |
| **Security Auditing (Red)** | Kali Linux, **Nmap** scanning & enumeration, vulnerability analysis on Metasploitable |
| **Threat Mitigation (Blue)** | Traffic inspection via **Wireshark**, SSL Decryption (Inbound/Outbound), Palo Alto Antivirus Profiles |
| **Email Security** | SPF, DKIM, DMARC, ARC, Exchange Online Protection (EOP) transport rules |

### 4. Database Administration & Governance (DBA & ITIL)
I am familiar with designing, securing, and maintaining enterprise relational databases as well as ITIL workflows.

| Domain | Technologies & Concepts |
| :--- | :--- |
| **Database Management** | MS SQL Server Enterprise (`db.local`), SQL Server Configuration Manager, SSMS |
| **Cloud Databases** | Azure SQL Database (Cloud-native & replication), Oracle Autonomous Database (OCI), Linked Servers |
| **Security / DB Coding** | T-SQL (Stored Procedures, Triggers, Views, Functions), Schema-Based Access Control, RBAC |
| **ITIL v4 Framework** | Incident, Problem, Change & Release Management, SLA/OLA KPI tracking |
| **Asset Management** | Configuration Management Database (**CMDB**), Configuration Item (CI) mapping, ITAM |

### 📱 Ecosystems & Development (Complementary)
* **Ecosystems:** Advanced administration knowledge of Apple environments (macOS, iOS, tvOS, AirPlay, AirPrint) and Android/Google environments.
* **Development (Basics):** Object-Oriented Software Development (OOSD) in Java and C#. Basics of HTML5/CSS3.
* **Peripherals:** Configuration and troubleshooting of network printers (Canon, Epson, HP, Samsung).

---

## 🛠️ Corporate & Practical Projects
### 🏠 Project 1: Personal Homelab & IoT Integration (Compute & Storage Decoupling)
I set up this project to improve my knowledge of Linux and Docker, which also allowed me to stop relying on paid cloud storage services to back up my photos. On the server, I deployed Jellyfin via Docker as a container to test an open-source alternative to Plex. Additionally, I implemented Immich as an alternative to Google Photos. In practice, Immich is a significantly higher-performing tool compared to the built-in photo backup feature of my NAS, whose application is very slow and tedious compared to Immich's database system. 

Persistence, application configuration files, and media are fetched and stored directly over the network via the SMB/CIFS protocol on a dedicated WD My Cloud EX2 Ultra NAS, configured with unique service credentials at the file storage level. Furthermore, I installed Home Assistant OS (HAOS) via Oracle VirtualBox, allowing for a more efficient and centralized management of all IoT devices in the house. Thanks to HAOS, I can create advanced automations and, via an add-on, I enabled AirPlay compatibility on Google Cast devices (such as sharing audio from an iPhone via AirPlay to a Google Cast speaker). Finally, I installed Music Assistant, which now allows me to easily stream music to multiple multiroom speakers that use different communication protocols.

---

## 📬 Contact
* **GitHub:** [thibautbdl](https://github.com/thibautbdl)
* **E-mail:** blondeelthibaut@outlook.be
