[NL] | [Français](fr.html) | [English](en.html)

# Systeem- & Netwerkbeheerder in wording

Hallo! Ik ben **Thibaut Blondeel**, een gedreven IT-student die na de zomer start aan het tweede en laatste jaar van de graduaatsopleiding **Systeem- en Netwerkbeheer** aan HOGENT. 

Mijn IT-reis begon met een sterke basis in Boekhouden-Informatica (Sint-Catharinacollege Geraardsbergen). Hoewel ik aanvankelijk startte in de bacheloropleiding Toegepaste Informatica, merkte ik al snel dat mijn kracht ligt in een sterk praktijkgerichte aanpak. Omdat ik bovendien al wist dat mijn echte passie bij systeem- en netwerkbeheer ligt, heb ik heel bewust de overstap gemaakt naar deze tweejarige, hands-on graduaatsopleiding. Mijn eerste jaar heb ik inmiddels succesvol achter de rug.

Naast mijn studies ben ik een actieve *homelabber*. Ik beheer thuis mijn eigen Linux- en NAS-servers, experimenteer met containerisatie (Docker) en configureer netwerkoppervlakken en smart home-automatisering. 

Ik ben momenteel op zoek naar een uitdagende stageplaats voor mijn laatste jaar, waar ik mijn enterprise- en praktische vaardigheden verder kan inzetten en aanscherpen.

---

## 💻 Technisch Profiel & Vaardigheden

 recruiters zoeken vaak op specifieke rollen binnen een IT-team. Hieronder vind je mijn vaardigheden ingedeeld volgens de expertises die ik tijdens mijn opleiding en enterprise-projecten heb opgebouwd.

### 1. Systeem- & Cloudbeheer (Systems Engineer)
Ik ben inzetbaar voor het beheren, virtualiseren en inrichten van on-premises en cloud-infrastructuur.

| Domein | Technologieën & Concepten |
| :--- | :--- |
| **Windows Server** | Active Directory (AD DS), GPO, AGDLP-rechtenstructuur, WSUS, Windows Server 2022/2025 |
| **Linux Administration** | Ubuntu Server, CentOS (Volledig headless CLI), LVM schijfbeheer, Vim/Nano, grep, Apache |
| **Virtualisatie & Cloud** | Proxmox VE (Clusters & Live Migration), Nutanix Prism Central, Hyper-V HA Clustering, VirtualBox |
| **Microsoft Azure & M365** | Azure Architectuur & Governance, Entra ID, Microsoft Intune, Windows Autopilot, Conditional Access |
| **Automatisering / IaC** | Cloud-init, Docker-Compose (YAML), Terraform, Azure Bicep, Power Automate, PowerShell |

### 2. Netwerkinfrastructuur & Firewalls (Network Engineer)
Ik bezit de theoretische en praktische kennis om enterprise-netwerken te structureren, te routeren en te beveiligen.

| Domein | Technologieën & Concepten |
| :--- | :--- |
| **Cisco Networking** | Cisco IOS CLI, VLANs, Trunking (802.1Q), Router-on-a-Stick, EtherChannel (LACP/PAgP) |
| **Routing Protocollen** | Single-area OSPFv2, HSRP (Gateway Redundancy), Statische routing |
| **Netwerkbeveiliging** | Switchport Security, DHCP Snooping, Dynamic ARP Inspection, Access Control Lists (ACL) |
| **Next-Gen Firewalls** | Palo Alto Networks NGFW (PAN-OS), pfSense (DMZ & Perimeter routing), FortiGate, Tailscale |
| **Core Netwerk Services** | DHCP Failover (Load Balance / Hot Standby), BIND9 DNS, Enterprise DNS Zone Transfers |

### 3. Cybersecurity & Observability (Security & Operations)
Ik heb actieve ervaring met het monitoren van infrastructuur en het valideren van netwerkbeveiliging via audits.

| Domein | Technologieën & Concepten |
| :--- | :--- |
| **Monitoring / Observability**| **Zabbix** (Infrastructuur & Service monitoring), `/var/log` audits, Query Store performance tuning |
| **Business Continuity** | **Proxmox Backup Server (PBS)** (Deduplicatie & Full Restore), Database DR (Full/Diff/Log Backups) |
| **Security Auditing (Red)** | Kali Linux, **Nmap** scanning & enumeratie, kwetsbaarheidsanalyse op Metasploitable |
| **Threat Mitigation (Blue)** | Verkeersinspectie via **Wireshark**, SSL Decryption (Inbound/Outbound), Palo Alto Antivirus Profiles |
| **Mail Security** | SPF, DKIM, DMARC, ARC, Exchange Online Protection (EOP) transportregels |

### 4. Database Administration & Organisatie (DBA & ITIL)
Ik ben vertrouwd met het ontwerpen, beveiligen en onderhouden van relationele enterprise-databases en ITIL-werkstromen.

| Domein | Technologieën & Concepten |
| :--- | :--- |
| **Database Management** | MS SQL Server Enterprise (`db.local`), SQL Server Configuration Manager, SSMS |
| **Cloud Databases** | Azure SQL Database (Cloud-native & replicatie), Oracle Autonomous Database (OCI), Linked Servers |
| **Database Security / Code** | T-SQL (Stored Procedures, Triggers, Views, Functions), Schema-Based Access Control, RBAC |
| **ITIL v4 Framework** | Incident, Problem, Change & Release Management, SLA/OLA KPI-opvolging |
| **Asset Management** | Configuration Management Database (**CMDB**), Configuration Items (CI's) mapping, ITAM |

### 📱 Ecosystemen & Development (Aanvullend)
* **Ecosystemen:** Geavanceerde administrator-kennis van Apple (macOS, iOS, tvOS, AirPlay-netwerksegmentatie) en Android/Google-omgevingen.
* **Development (Basis):** Object-Oriented Software Development (OOSD) in Java en C#. Basis HTML5/CSS3.
* **Randapparatuur:** Configureren en troubleshooten van netwerkprinters (Canon, Epson, HP, Samsung).

---

## 🛠️ Enterprise & Hands-on Projecten
### 🏠 Project 1: Persoonlijk Homelab & IoT Integratie (Compute & Storage Decoupling)
Dit project heb ik opgezet om mijn kennis van Linux en Docker te verbeteren, en het heeft er bovendien voor gezorgd dat ik niet meer afhankelijk hoef te zijn van betaalde cloudopslagdiensten om mijn foto's te bewaren. Op de server heb ik via Docker Jellyfin geïnstalleerd als container om een open-source alternatief voor Plex te testen. Daarnaast heb ik Immich geïmplementeerd als alternatief voor Google Photos. Immich is in de praktijk een aanzienlijk betere tool dan de ingebouwde fotobackup-functie van mijn NAS, waarvan de app erg traag en omslachtig werkt in vergelijking met het database-systeem van Immich. 

De persistence, applicatie-configuratiebestanden en media worden live via het SMB/CIFS-protocol over het netwerk opgehaald en opgeslagen op een dedicated WD My Cloud EX2 Ultra NAS, ingericht met unieke service-credentials op file-storage niveau. Verder heb ik via Oracle VirtualBox Home Assistant OS (HAOS) geïnstalleerd, wat zorgt voor een efficiënter en gecentraliseerd beheer van alle IoT-devices in huis. Via HAOS kan ik uitgebreide automatiseringen realiseren en heb ik via een add-on de mogelijkheid gecreëerd om AirPlay-compatibiliteit te bieden op Google Cast-apparaten (zoals het delen van iPhone-audio via AirPlay naar een Google Cast-speaker). Tot slot heb ik Music Assistant geïnstalleerd, waarmee ik nu heel eenvoudig muziek kan streamen naar verschillende multiroom speakers die onderling gebruikmaken van diverse protocollen.

---

## 📬 Contact
* **GitHub:** [thibautbdl](https://github.com/thibautbdl)
* **E-mail:** blondeelthibaut@outlook.be
