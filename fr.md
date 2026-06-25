[NL](index.html) | [Français] | [English](en.html)

# Étudiant Administrateur Systèmes & Réseaux

Bonjour ! Je m'appelle **Thibaut Blondeel**, un étudiant en informatique passionné qui débutera, après l'été, sa deuxième et dernière année de formation graduée en **Administration Systèmes et Réseaux** à la HOGENT. 

Mon parcours en informatique a commencé par une base solide en Comptabilité-Informatique (Sint-Catharinacollege Geraardsbergen). Bien que j'aie initialement commencé par un bachelier en Informatique Appliquée, j'ai rapidement réalisé que ma force résidait dans une approche fortement axée sur la pratique. Sachant de surcroît que ma véritable passion se trouvait dans l'administration systèmes et réseaux, j'ai délibérément choisi de me réorienter vers ce cursus gradué de deux ans, très concret et pratique. J'ai désormais validé ma première année avec succès.

En dehors de mes études, je suis un *homelabber* actif. Je gère mes propres serveurs Linux et NAS à la maison, j'expérimente la conteneurisation (Docker) et je configure des environnements réseau ainsi que l'automatisation de la maison connectée (smart home). 

Je suis actuellement à la recherche d'un stage stimulant pour ma dernière année, où je pourrai déployer et perfectionner mes compétences pratiques et d'entreprise.

---

## 💻 Profil Technique & Compétences

Les recruteurs recherchent souvent des rôles spécifiques au sein d'une équipe informatique. Vous trouverez ci-dessous mes compétences classées selon les domaines d'expertise que j'ai développés au cours de ma formation et de mes projets d'entreprise.

### 1. Gestion Systèmes & Cloud (Systems Engineer)
Je suis opérationnel pour la gestion, la virtualisation et la mise en place d'infrastructures sur site (on-premises) et cloud.

| Domaine | Technologies & Concepts |
| :--- | :--- |
| **Windows Server** | Active Directory (AD DS), GPO, structure de permissions AGDLP, WSUS, Windows Server 2022/2025 |
| **Linux Administration** | Ubuntu Server, CentOS (CLI entièrement headless), gestion de disques LVM, Vim/Nano, grep, Apache |
| **Virtualisation & Cloud** | Proxmox VE (Clusters & Live Migration), Nutanix Prism Central, Hyper-V HA Clustering, VirtualBox |
| **Microsoft Azure & M365** | Architecture & Gouvernance Azure, Entra ID, Microsoft Intune, Windows Autopilot, Conditional Access |
| **Automatisation / IaC** | Cloud-init, Docker-Compose (YAML), Terraform, Azure Bicep, Power Automate, PowerShell |

### 2. Infrastructure Réseau & Firewalls (Network Engineer)
Je possède les connaissances théoriques et pratiques pour structurer, router et sécuriser les réseaux d'entreprise.

| Domaine | Technologies & Concepts |
| :--- | :--- |
| **Cisco Networking** | Cisco IOS CLI, VLANs, Trunking (802.1Q), Router-on-a-Stick, EtherChannel (LACP/PAgP) |
| **Protocoles de Routage** | Single-area OSPFv2, HSRP (Gateway Redundancy), Routage statique |
| **Sécurité Réseau** | Switchport Security, DHCP Snooping, Dynamic ARP Inspection, Access Control Lists (ACL) |
| **Next-Gen Firewalls** | Palo Alto Networks NGFW (PAN-OS), pfSense (DMZ & Routage de périmètre), FortiGate, Tailscale |
| **Services Réseau Core** | DHCP Failover (Load Balance / Hot Standby), BIND9 DNS, Enterprise DNS Zone Transfers |

### 3. Cybersécurité & Observabilité (Security & Operations)
J'ai une expérience active dans la surveillance des infrastructures et la validation de la sécurité réseau par le biais d'audits.

| Domaine | Technologies & Concepts |
| :--- | :--- |
| **Monitoring / Observability**| **Zabbix** (Surveillance d'infrastructure & de services), audits `/var/log`, Query Store performance tuning |
| **Continuité d'Activité** | **Proxmox Backup Server (PBS)** (Déduplication & Full Restore), Database DR (Full/Diff/Log Backups) |
| **Audit de Sécurité (Red)** | Kali Linux, **Nmap** scanning & énumération, analyse de vulnérabilités sur Metasploitable |
| **Atténuation des Menaces (Blue)** | Inspection du trafic via **Wireshark**, SSL Decryption (Inbound/Outbound), Palo Alto Antivirus Profiles |
| **Sécurité Messagerie** | SPF, DKIM, DMARC, ARC, règles de transport Exchange Online Protection (EOP) |

### 4. Administration de Bases de Données & Organisation (DBA & ITIL)
Je suis familier avec la conception, la sécurisation et la maintenance des bases de données relationnelles d'entreprise ainsi qu'avec les flux de travail ITIL.

| Domaine | Technologies & Concepts |
| :--- | :--- |
| **Gestion de Bases de Données** | MS SQL Server Enterprise (`db.local`), SQL Server Configuration Manager, SSMS |
| **Bases de Données Cloud** | Azure SQL Database (Cloud-native & réplication), Oracle Autonomous Database (OCI), Linked Servers |
| **Sécurité / Code de BD** | T-SQL (Stored Procedures, Triggers, Views, Functions), Schema-Based Access Control, RBAC |
| **Framework ITIL v4** | Gestion des Incidents, Problèmes, Changements & Releases, suivi des KPI SLA/OLA |
| **Gestion des Actifs** | Configuration Management Database (**CMDB**), cartographie des éléments de configuration (CI), ITAM |

### 📱 Écosystèmes & Développement (Complémentaire)
* **Écosystèmes :** Connaissances d'administration avancées des environnements Apple (macOS, iOS, tvOS, segmentation réseau AirPlay) et Android/Google.
* **Développement (Bases) :** Développement Logiciel Orienté Objet (OOSD) en Java et C#. Bases en HTML5/CSS3.
* **Périphériques :** Configuration et dépannage d'imprimantes réseau (Canon, Epson, HP, Samsung).

---

## 🛠️ Projets d'Entreprise & Pratiques
### 🏠 Projet 1 : Homelab Personnel & Intégration IoT (Découplage Compute & Storage)
J'ai mis en place ce projet pour améliorer mes connaissances de Linux et Docker, et cela m'a également permis de ne plus dépendre de services de stockage cloud payants pour sauvegarder mes photos. Sur le serveur, j'ai installé Jellyfin via Docker en tant que conteneur afin de tester une alternative open source à Plex. De plus, j'ai implémenté Immich comme alternative à Google Photos. En pratique, Immich est un outil nettement plus performant que la fonction de sauvegarde de photos intégrée à my NAS, dont l'application est très lente et fastidieuse par rapport au système de base de données d'Immich. 

La persistance, les fichiers de configuration de l'application et les médias sont récupérés et stockés en direct sur le réseau via le protocole SMB/CIFS sur un NAS dédié WD My Cloud EX2 Ultra, configuré avec des identifiants de service uniques au niveau du stockage de fichiers. De plus, j'ai installé Home Assistant OS (HAOS) via Oracle VirtualBox, ce qui permet une gestion plus efficace et centralisée de tous les appareils IoT de la maison. Grâce à HAOS, je peux réaliser des automatisations poussées et j'ai créé, via un add-on, la possibilité d'offrir une compatibilité AirPlay sur les appareils Google Cast (comme le partage de l'audio d'un iPhone via AirPlay vers une enceinte Google Cast). Enfin, j'ai installé Music Assistant, ce qui me permet désormais de diffuser très facilement de la musique sur plusieurs enceintes multiroom qui utilisent pourtant des protocoles différents.

---

## 📬 Contact
* **GitHub :** [thibautbdl](https://github.com/thibautbdl)
* **E-mail :** blondeelthibaut@outlook.be
