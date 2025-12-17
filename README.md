<div align="center">
  
# Danny (Thu) Hoang
### Infrastructure Engineer | CCNA & Security+ | Hybrid Cloud Specialist

<a href="mailto:thuvhoang19@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/vietthuhoang"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/dannyhng"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/>

**Infrastructure Engineer bridging packets and pipelines.** <br/>
*Building, breaking, and automating infrastructure in a production-grade hybrid environment.*

</div>

---

### About Me
I am an Infrastructure Engineer transitioning from traditional networking to **NetDevOps**. While I have a strong foundation in routing and switching (Cisco CLI), my focus is on **Infrastructure as Code (IaC)**.  
I don't just study networking concepts; I build, break, and automate them in a production-grade hybrid environment. My goal is to bridge the gap between on-premise hardware and modern cloud automation.

### Current Focus
* **Infrastructure:** Architecting Hybrid Cloud environments using **Proxmox VE**, **Terraform**, and **Windows Server**.
* **Identity:** Unifying authentication across boundaries using **Microsoft Entra ID** and **Active Directory**.
* **Automation:** Replacing manual "ClickOps" with **Ansible** playbooks and **PowerShell** pipelines.

### Certifications

| Certification | Issued |
| :--- | :--- |
| **Cisco Certified Network Associate (CCNA)** | Issued June 2025 |
| **CompTIA Security+ (SY0-701)** | Issued Dec 2024 |
| **CompTIA A+** | Issued Sept 2025 |
| **CCNP Enterprise** | *In Progress* |

---

### Featured Engineering Projects

#### 1. Enterprise Hybrid Identity Infrastructure
*Bridging On-Premises Active Directory with Microsoft Entra ID using Infrastructure as Code.*
* **Architecture:** Deployed **Microsoft Entra Connect** to establish Password Hash Sync (PHS), unifying authentication across local LAN and Cloud boundaries.
* **IaC:** Replaced manual server builds with **Terraform**, automating the provisioning of Windows Server 2022, storage, and vNICs on Proxmox.
* **Automation:** Engineered a **PowerShell** pipeline that parses CSV datasets to programmatically provision users and trigger sync cycles, eliminating manual data entry.
* **Security:** Hardened auth protocols by enforcing **TLS 1.2+** and resolving virtualization time-skew issues.

#### 2. [Hybrid Homelab Network Architecture](https://github.com/dannyhng/hybrid-homelab-infrastructure)
*A documentation of my journey architecting a production-grade network environment using modern DevOps principles.*
* **Architecture:** Designed a split-topology network separating Critical Infrastructure (Proxmox/pfSense) from Compute (Bare Metal Docker).
* **Automation:** Wrote **Ansible** playbooks to handle system patching and inventory management across heterogeneous OS types.
* **Observability:** Deployed a full monitoring stack (**Prometheus/Grafana**) via Docker Compose with raw kernel scraping via host networking.
* **Security:** Implemented **Zero Trust** remote access using Tailscale Subnet Routing to eliminate open WAN ports.

#### 3. [Virtual Network Infrastructure (Cisco Packet Tracer)](https://github.com/dannyhng/ccna-full-config-lab)
* Designed a multi-site LAN/WAN topology using **IPv6, OSPF routing, and VLAN segmentation**.
* Implemented enterprise security policies using **ACLs, NAT, and router-based VPNs** to secure the network edge.
* Validated network resilience by implementing redundancy protocols (HSRP/STP) and performing failover testing.

---

### Technical Skills

| Category | Technologies |
| :--- | :--- |
| **Infrastructure as Code** | Terraform, Ansible, Docker, Proxmox VE |
| **Cloud & Identity** | Microsoft Entra ID (Hybrid), Azure AD, Windows Server 2022 |
| **Automation** | Python (Netmiko), PowerShell, Bash, Git, YAML |
| **Networking** | TCP/IP, OSPF, VLANs, DNS (AdGuard), VPN (Tailscale), pfSense |
| **Observability** | Prometheus, Grafana, Wireshark, Syslog |
| **Security** | Zero Trust Principles, ACLs, SSL/TLS (Nginx), IAM (Authentik) |

---

<div align="center">
  <i>"Manual configuration creates drift. Automation creates reliability."</i>
</div>
