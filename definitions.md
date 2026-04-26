# CompTIA Network+ (N10-009) Acronyms Organized by OSI Layer

> 📋 **Aligned with official V9 exam objectives** | Definitions optimized for exam recall

---

## 🔹 Layer 1: Physical
*Transmission media, connectors, signaling, power*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **BNC** | Bayonet Neill-Concelman | Twist-lock coaxial connector used in legacy 10BASE2 Ethernet |
| **LC** | Local Connector | Small form-factor fiber connector with push-pull latch; common in SFP modules |
| **SC** | Subscriber Connector | Fiber connector with push-pull coupling; common in multimode installations |
| **ST** | Straight Tip | Fiber connector with bayonet-style coupling; used in campus backbones |
| **MPO** | Multifiber Push-On | High-density connector supporting 12-24 fibers; used in 40/100GbE |
| **RJ** | Registered Jack | Standardized telecommunication interface (RJ-45 for Ethernet, RJ-11 for phone) |
| **DAC** | Direct Attach Copper | Short-range copper cable with fixed SFP+ transceivers for high-speed links |
| **FC** | Fibre Channel | High-speed SAN protocol (8/16/32 Gbps) using optical fiber |
| **QSFP** | Quad Small Form-factor Pluggable | Hot-pluggable transceiver aggregating 4 channels for 40/100GbE |
| **SFP** | Small Form-factor Pluggable | Hot-pluggable transceiver for Gigabit Ethernet/fiber connections |
| **TX** | Transmitter | Component sending optical/electrical signals on a network interface |
| **RX** | Receiver | Component receiving optical/electrical signals on a network interface |
| **CRC** | Cyclic Redundancy Check | Error-detecting code appended to frames; verified at Physical/Data Link boundary |
| **MTU** | Maximum Transmission Unit | Largest Layer 3 packet size an interface can transmit without fragmentation |
| **PoE** | Power over Ethernet | IEEE 802.3af/at/bt standard delivering DC power over Ethernet cables |
| **UPS** | Uninterruptible Power Supply | Battery-backed device providing temporary power during outages |
| **PDU** | Power Distribution Unit | Rack-mounted device distributing electrical power to network equipment |
| **STP** | Shielded Twisted Pair | Copper cabling with foil/braid shielding to reduce EMI/RFI interference |
| **UTP** | Unshielded Twisted Pair | Most common Ethernet cabling; twisted pairs reduce crosstalk (Cat5e/6/6a) |
| **CPU** | Central Processing Unit | Hardware executing instructions; network devices use CPUs for control-plane tasks |

---

## 🔹 Layer 2: Data Link
*MAC addressing, switching, VLANs, wireless framing*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **MAC** | Media Access Control | Unique 48-bit hardware address burned into NICs for Layer 2 frame delivery |
| **ARP** | Address Resolution Protocol | Resolves IPv4 addresses to MAC addresses on local networks (Layer 2.5) |
| **CAM** | Content-Addressable Memory | High-speed switch memory storing MAC address tables for forwarding decisions |
| **VLAN** | Virtual Local Area Network | Logical segmentation of a physical switch into multiple broadcast domains |
| **SVI** | Switch Virtual Interface | Virtual Layer 3 interface on a multilayer switch representing a VLAN |
| **STP** | Spanning Tree Protocol | Prevents Layer 2 loops by blocking redundant paths; IEEE 802.1D |
| **RSTP** | Rapid Spanning Tree Protocol | Enhanced STP (802.1w) providing sub-50-second convergence |
| **LACP** | Link Aggregation Control Protocol | IEEE 802.3ad standard for dynamically bundling physical links into one logical channel |
| **LLDP** | Link Layer Discovery Protocol | Vendor-neutral Layer 2 protocol advertising device identity to neighbors |
| **CDP** | Cisco Discovery Protocol | Cisco-proprietary Layer 2 protocol advertising device info to directly connected neighbors |
| **EAPoL** | Extensible Authentication Protocol over LAN | Carries EAP frames between clients and switches for 802.1X port-based access |
| **BSSID** | Basic Service Set Identifier | MAC address of a wireless AP's radio; uniquely identifies a single AP |
| **SSID** | Service Set Identifier | Human-readable name identifying a wireless network; broadcast in beacon frames |
| **ESSID** | Extended Service Set Identifier | Logical SSID name shared across multiple APs to enable seamless roaming |
| **NIC** | Network Interface Card | Hardware component enabling a device to connect to a network medium |
| **MDIX** | Medium Dependent Interface Crossover | Auto-MDIX allows Ethernet ports to auto-detect straight-through/crossover cables |
| **WPA** | Wi-Fi Protected Access | Security protocol for wireless; WPA2 (AES-CCMP) and WPA3 provide stronger encryption |
| **WPS** | Wi-Fi Protected Setup | Simplified Wi-Fi connection method (PIN/push-button); known security vulnerabilities |
| **PSK** | Pre-shared Key | Symmetric password used for authentication in WPA/WPA2-Personal networks |

---

## 🔹 Layer 3: Network
*Logical addressing, routing, path selection*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **IP** | Internet Protocol | Connectionless Layer 3 protocol for logical addressing and routing packets |
| **ICMP** | Internet Control Message Protocol | Network-layer protocol for error reporting and diagnostics (ping, traceroute) |
| **CIDR** | Classless Inter-Domain Routing | IP addressing using variable-length subnet masks (e.g., 192.168.1.0/24) |
| **APIPA** | Automatic Private IP Addressing | Windows feature auto-assigning 169.254.0.0/16 when DHCP fails |
| **NAT** | Network Address Translation | Translates private IP addresses to public IPs at network boundaries |
| **PAT** | Port Address Translation | NAT variant mapping multiple private IPs to one public IP using unique ports |
| **BGP** | Border Gateway Protocol | Path-vector routing protocol between autonomous systems; uses AS_PATH for loop prevention |
| **OSPF** | Open Shortest Path First | Link-state IGP using Dijkstra's algorithm; supports areas and fast convergence |
| **EIGRP** | Enhanced Interior Gateway Routing Protocol | Cisco-proprietary advanced distance-vector protocol using DUAL algorithm |
| **RIP** | Routing Information Protocol | Distance-vector IGP using hop count metric; limited to 15 hops |
| **IS-IS** | Intermediate System to Intermediate System | Link-state IGP used primarily by ISPs; similar to OSPF but uses CLNS addressing |
| **FHRP** | First Hop Redundancy Protocol | Protocols (HSRP/VRRP/GLBP) providing default gateway redundancy for LAN hosts |
| **VIP** | Virtual IP | Single IP representing a group of servers (load balancer) or redundant gateway |
| **VPC** | Virtual Private Cloud | Logically isolated section of a public cloud with custom networking |
| **VXLAN** | Virtual Extensible LAN | Overlay protocol encapsulating Layer 2 frames in UDP for data center segmentation |
| **GRE** | Generic Routing Encapsulation | Tunneling protocol encapsulating various network-layer protocols inside IP |
| **AH** | Authentication Header | IPsec header providing data integrity, authentication, anti-replay (no encryption) |
| **ESP** | Encapsulating Security Payload | IPsec protocol providing confidentiality, authentication, integrity for IP packets |
| **IKE** | Internet Key Exchange | Protocol negotiating security associations and cryptographic keys for IPsec VPNs |
| **ACL** | Access Control List | Rule set permitting/denying traffic based on source/destination IP, port, or protocol |

---

## 🔹 Layer 4: Transport
*End-to-end delivery, ports, reliability*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **TCP** | Transmission Control Protocol | Connection-oriented, reliable transport with sequencing, ACKs, flow control |
| **UDP** | User Datagram Protocol | Connectionless, low-overhead transport; no delivery/ordering guarantees |
| **QoS** | Quality of Service | Mechanisms prioritizing critical traffic via classification, marking, queuing |
| **TTL** | Time to Live | IP header field limiting packet lifespan (hops); prevents routing loops |

---

## 🔹 Layer 5: Session
*Session management, authentication handshakes*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **SIP** | Session Initiation Protocol | Signaling protocol for initiating/managing VoIP/video sessions (UDP/TCP 5060/5061) |
| **SAML** | Security Assertion Markup Language | XML-based standard for exchanging auth/authz data between IdP and SP for SSO |
| **SSO** | Single Sign-On | Authentication scheme allowing access to multiple apps with one credential set |
| **IKE** | Internet Key Exchange | *(Also L3)* Negotiates security associations for IPsec; establishes session keys |
| **EAPoL** | Extensible Authentication Protocol over LAN | *(Also L2)* Carries EAP authentication frames for 802.1X session establishment |

---

## 🔹 Layer 6: Presentation
*Encryption, encoding, data formatting*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **SSL** | Secure Sockets Layer | Deprecated cryptographic protocol for securing communications; superseded by TLS |
| **TLS** | Transport Layer Security | Cryptographic protocol providing encryption, integrity, authentication (successor to SSL) |
| **DNSSEC** | Domain Name System Security Extensions | Adds digital signatures to DNS records to authenticate responses and prevent spoofing |
| **DoH** | DNS over HTTPS | Encrypts DNS queries within HTTPS traffic (port 443) to prevent eavesdropping |
| **DoT** | DNS over TLS | Encrypts DNS queries using TLS (port 853) for confidentiality and integrity |

---

## 🔹 Layer 7: Application
*User-facing protocols and services*

| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **HTTP** | Hypertext Transfer Protocol | Application protocol for web content transfer; unencrypted, TCP port 80 |
| **HTTPS** | Hypertext Transfer Protocol Secure | HTTP encrypted with TLS; ensures confidentiality/integrity on TCP port 443 |
| **FTP** | File Transfer Protocol | Unencrypted file transfer over TCP ports 20 (data) and 21 (control) |
| **SFTP** | Secure File Transfer Protocol | File transfer over SSH (port 22); provides encryption and authentication |
| **TFTP** | Trivial File Transfer Protocol | Lightweight, unauthenticated file transfer using UDP port 69 |
| **SSH** | Secure Shell | Encrypted protocol for secure remote CLI access and file transfers (port 22) |
| **Telnet** | Teletype Network | Unencrypted remote CLI protocol; replaced by SSH for security |
| **SMTP** | Simple Mail Transfer Protocol | Protocol for sending email between servers; TCP port 25 (or 587 for submission) |
| **SMTPS** | Simple Mail Transfer Protocol Secure | SMTP secured with TLS; typically uses port 465 (implicit TLS) or 587 (STARTTLS) |
| **DNS** | Domain Name System | Hierarchical system translating domain names to IP addresses; UDP/TCP port 53 |
| **DHCP** | Dynamic Host Configuration Protocol | Auto-assigns IP addresses, subnet masks, gateways, DNS to clients (UDP 67/68) |
| **SNMP** | Simple Network Management Protocol | Protocol for monitoring/managing network devices; UDP ports 161 (queries)/162 (traps) |
| **LDAP** | Lightweight Directory Access Protocol | Protocol for accessing directory services (e.g., Active Directory); TCP port 389 |
| **LDAPS** | LDAP over SSL | LDAP secured with TLS/SSL encryption; uses TCP port 636 |
| **RDP** | Remote Desktop Protocol | Microsoft protocol for remote graphical access to Windows; TCP port 3389 |
| **SMB** | Server Message Block | Application protocol for file/print sharing and remote administration; ports 139/445 |
| **SQL** | Structured Query Language | Standard language for managing relational databases; targeted in SQL injection attacks |
| **NTP** | Network Time Protocol | Protocol synchronizing clocks across network devices; critical for logging/PKI |
| **PTP** | Precision Time Protocol | IEEE 1588 protocol providing sub-microsecond clock sync for industrial/telecom |
| **NTS** | Network Time Security | Security extensions for NTP providing authentication for time synchronization |
| **SLAAC** | Stateless Address Autoconfiguration | IPv6 method where hosts auto-configure addresses using router advertisements |
| **API** | Application Programming Interface | Set of protocols allowing software applications to communicate programmatically |
| **CDN** | Content Delivery Network | Geographically distributed servers caching content to reduce latency |
| **URL** | Uniform Resource Locator | Address specifying location and access method for an internet resource |
| **CNAME** | Canonical Name | DNS record mapping an alias domain name to a canonical (true) domain name |
| **MX** | Mail Exchange | DNS record specifying mail server(s) responsible for accepting email for a domain |
| **PTR** | Pointer | DNS record mapping an IP address to a domain name; used for reverse DNS lookups |
| **NS** | Name Server | DNS server authoritative for a domain; stores and provides DNS record responses |
| **SOA** | Start of Authority | DNS record containing administrative info about a zone (primary NS, serial, intervals) |
| **TXT** | Text | DNS record storing arbitrary text; commonly used for SPF, DKIM, DMARC email auth |
| **A** | Address | DNS record mapping a hostname to an IPv4 address |
| **AAAA** | IPv6 Address | DNS record mapping a hostname to an IPv6 address |

---

## 🔹 Cross-Layer / Management / Security
*Concepts spanning multiple layers or operational domains*

### 🔐 Security & Authentication
| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **CIA** | Confidentiality, Integrity, Availability | Three core principles of information security; foundational to risk management |
| **PKI** | Public Key Infrastructure | Framework of CAs, certificates, policies enabling secure key management |
| **IAM** | Identity and Access Management | Framework for managing digital identities, authentication, authorization |
| **MFA** | Multifactor Authentication | Authentication requiring ≥2 factors (knowledge, possession, inherence) |
| **RADIUS** | Remote Authentication Dial-In User Service | Centralized AAA protocol using UDP; common for network access authentication |
| **TACACS+** | Terminal Access Controller Access-Control System Plus | Cisco AAA protocol using TCP; separates auth/authz/accounting; encrypts payload |
| **NAC** | Network Access Control | Security framework enforcing policy-based access decisions for network joiners |
| **IDS** | Intrusion Detection System | Passive security device monitoring traffic for malicious patterns; alerts only |
| **IPS** | Intrusion Prevention System | Active security device detecting AND blocking malicious traffic in real-time |
| **SIEM** | Security Information and Event Management | Centralized platform aggregating security events for correlation and alerting |
| **DLP** | Data Loss Prevention | Tools monitoring/blocking sensitive data (PII, PCI) from leaving the network |
| **UTM** | Unified Threat Management | All-in-one security appliance combining firewall, IPS, AV, content filtering |
| **ACL** | Access Control List | *(Cross-layer)* Rule set permitting/denying traffic at L3/L4 boundaries |
| **IPsec** | Internet Protocol Security | Suite (AH, ESP, IKE) providing authentication, integrity, encryption for IP traffic |
| **VPN** | Virtual Private Network | Encrypted tunnel over public networks for secure remote access or site-to-site |
| **DoS** | Denial-of-Service | Attack disrupting service by exhausting resources on a single target |
| **DDoS** | Distributed Denial-of-Service | Attack using multiple compromised systems to overwhelm a target |

### 🌐 Cloud, Virtualization & Modern Architecture
| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **NFV** | Network Functions Virtualization | Running network services (firewalls, LBs) as software on commodity hardware |
| **SDN** | Software-Defined Networking | Architecture separating control plane (centralized controller) from data plane |
| **SD-WAN** | Software-Defined WAN | Application-aware WAN overlay optimizing traffic across multiple transports |
| **SASE** | Secure Access Service Edge | Cloud architecture converging SD-WAN and security services at the edge |
| **SSE** | Security Service Edge | Cloud-delivered security services (CASB, FWaaS, ZTNA) positioned near users |
| **ZTA** | Zero Trust Architecture | Security model assuming no implicit trust; requires continuous verification |
| **IaC** | Infrastructure as Code | Managing infrastructure via machine-readable definition files (Terraform, Ansible) |
| **IaaS** | Infrastructure as a Service | Cloud model providing virtualized compute, storage, networking (e.g., AWS EC2) |
| **PaaS** | Platform as a Service | Cloud model providing development/runtime environments without OS management |
| **SaaS** | Software as a Service | Cloud model delivering applications over internet (e.g., Office 365); vendor-managed |

### 📊 Operations, Monitoring & Documentation
| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **SLA** | Service-Level Agreement | Contract defining expected service metrics (uptime, latency, support response) |
| **IPAM** | IP Address Management | Tools/processes for planning, tracking, managing IP allocation and DNS/DHCP |
| **MIB** | Management Information Base | Hierarchical database of managed objects used by SNMP for device monitoring |
| **RPO** | Recovery Point Objective | Maximum tolerable data loss measured in time; determines backup frequency |
| **RTO** | Recovery Time Objective | Maximum acceptable downtime; drives DR strategy and resource allocation |
| **MTTR** | Mean Time To Repair | Average time required to diagnose, repair, and restore a failed system |
| **MTBF** | Mean Time Between Failures | Statistical measure of hardware reliability; average operational time before failure |
| **DR** | Disaster Recovery | Documented processes to restore critical systems after catastrophic failures |
| **EOL** | End-of-Life | Product phase where manufacturer stops selling the item |
| **EOS** | End-of-Support | Product phase where manufacturer ceases all updates and technical assistance |
| **GUI** | Graphical User Interface | Visual interface with icons/menus for managing systems |
| **CLI** | Command-Line Interface | Text-based interface for configuring devices via commands (e.g., Cisco IOS) |

### 🏢 Policy, Compliance & Segmentation
| Acronym | Full Form | Network+ Definition |
|---------|-----------|-------------------|
| **AUP** | Acceptable Use Policy | Document defining permitted/prohibited user activities on organizational resources |
| **EULA** | End User License Agreement | Legal contract defining permitted uses and restrictions for software/hardware |
| **GDPR** | General Data Protection Regulation | EU regulation mandating data privacy protections and user rights for personal data |
| **PCI DSS** | Payment Card Industry Data Security Standard | Security standards for organizations handling credit card data; mandates encryption/audits |
| **IoT** | Internet of Things | Network of internet-connected physical devices with limited compute/resources |
| **IIoT** | Industrial Internet of Things | IoT devices in industrial settings; requires OT security considerations |
| **SCADA** | Supervisory Control and Data Acquisition | Industrial control systems monitoring/controlling infrastructure (power, water) |
| **ICS** | Industrial Control System | Systems (SCADA, PLCs) controlling industrial processes; often isolated for security |
| **OT** | Operational Technology | Hardware/software controlling industrial equipment; prioritizes availability |
| **BYOD** | Bring Your Own Device | Policy allowing personal devices on corporate networks; requires MDM/NAC |

---

## 🎯 Exam Strategy: Layer-Based Mnemonics

```
🔹 Physical (L1): "Can Big Lions Sleep Quietly?" 
   → CRC, BNC, LC, ST, SFP, QSFP, TX/RX

🔹 Data Link (L2): "MACs Always Switch Very Rapidly"
   → MAC, ARP, CAM, Switch, VLAN, RSTP, LLDP

🔹 Network (L3): "IP Routes Never Get Lost"
   → IP, ICMP, Routing (BGP/OSPF/EIGRP), NAT, CIDR, VIP

🔹 Transport (L4): "TCP Undergoes Quality Testing"
   → TCP, UDP, QoS, TTL, Ports

🔹 Application (L7): "HTTP DNS SMTP FTP SSH"
   → Memorize ports: 80/443, 53, 25/587, 20/21, 22
```

---

## 📚 Quick Reference: Critical Ports for Network+

| Protocol | Port(s) | Transport | Layer |
|----------|---------|-----------|-------|
| FTP | 20/21 | TCP | 7 |
| SSH/SFTP | 22 | TCP | 7 |
| Telnet | 23 | TCP | 7 |
| SMTP | 25 | TCP | 7 |
| DNS | 53 | UDP/TCP | 7 |
| DHCP | 67/68 | UDP | 7 |
| TFTP | 69 | UDP | 7 |
| HTTP | 80 | TCP | 7 |
| NTP | 123 | UDP | 7 |
| SNMP | 161/162 | UDP | 7 |
| LDAP | 389 | TCP | 7 |
| HTTPS | 443 | TCP | 7 |
| SMB | 445 | TCP | 7 |
| Syslog | 514 | UDP | 7 |
| SMTPS | 587 | TCP | 7 |
| LDAPS | 636 | TCP | 7 |
| RDP | 3389 | TCP | 7 |
| SIP | 5060/5061 | UDP/TCP | 5/7 |

---

> 💡 **Pro Tip**: On the Network+ exam, when you see an acronym:
> 1. Identify its primary OSI layer first
> 2. Recall its port number (if applicable)
> 3. Remember one key security or troubleshooting implication
> 
> Example: **DNS** → Layer 7 → Port 53 → Vulnerable to poisoning; mitigated by DNSSEC/DoH/DoT

Let me know if you'd like this as a printable PDF, Anki flashcards, or a layered diagram for visual study! 🚀
