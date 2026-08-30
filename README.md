# IT Solutions – Infrastructure Engineer Lab

A complete enterprise‑grade IT environment designed to simulate the real‑world responsibilities of an **Infrastructure Engineer**. This project demonstrates end‑to‑end management of identity, networking, security operations, cloud fundamentals, and IT workflows using both on‑premises and cloud technologies.

This lab mirrors modern corporate environments and showcases the ability to design, deploy, secure, and maintain a full business infrastructure from scratch.

---

## 🔧 Professional Summary

This repository demonstrates practical Infrastructure Engineering skills through the deployment of a hybrid enterprise environment. It includes identity management, networking, cloud administration, security monitoring, patching, ticketing workflows, and documentation — the same responsibilities handled by real Systems and Infrastructure Engineers.

---

## 🏢 Business Scenario

**IT Solutions** is modeled as a mid-sized organization with hybrid identity, cloud workloads, and on-premises infrastructure.  
The environment is designed to simulate real operational requirements including:

- User lifecycle management  
- Identity troubleshooting  
- Network segmentation  
- Patch compliance  
- Security monitoring  
- Vulnerability remediation  
- Cloud resource provisioning  
- Ticketing and change management  

This project reflects the daily work performed in IT Operations, Systems Administration, and Cloud Support roles.

---

## 🧩 Skills Matrix

| Category | Skills Demonstrated |
|---------|----------------------|
| Identity & Access | AD DS, GPOs, Azure AD Connect, M365 Administration |
| Networking | VLANs, DHCP, DNS, Routing, NAT, Firewalling (pfSense) |
| Servers & Endpoints | Windows Server 2022, Windows 10/11, Linux Administration |
| Security | Wazuh SIEM, OpenVAS, MFA, Least Privilege, Patch Management |
| Cloud | AWS EC2, IAM, VPC, S3, Security Groups, Cloud Architecture |
| Operations | WSUS, GLPI Ticketing, Documentation, Change Management |

---

## 🧱 Core Objectives

This project demonstrates the ability to:

- Build and administer **Active Directory Domain Services (AD DS)**  
- Design and enforce **Group Policy Objects (GPOs)**  
- Manage **Windows Server** and **Windows 10/11** endpoints  
- Configure **pfSense** for routing, VLANs, and firewalling  
- Implement **WSUS** for patch management  
- Deploy **Wazuh SIEM** for security monitoring  
- Run **OpenVAS** for vulnerability scanning  
- Operate a **GLPI ticketing system**  
- Integrate on‑prem AD with **Microsoft 365** using Azure AD Connect  
- Understand AWS cloud fundamentals (EC2, IAM, VPC, S3, security groups)  

This lab is built to reflect real enterprise environments and Infrastructure Engineer responsibilities.

---

## 🔨 Deployment Workflow

1. Provision Proxmox hypervisor  
2. Deploy Windows Server 2022 VM  
3. Configure AD DS and create `itsolutions.local` domain  
4. Build OU structure and apply GPOs  
5. Join Windows 10/11 clients to the domain  
6. Configure pfSense firewall, VLANs, and routing  
7. Deploy WSUS for patch management  
8. Install Wazuh SIEM and OpenVAS  
9. Configure GLPI ticketing system  
10. Integrate AD with Microsoft 365 via Azure AD Connect  
11. Complete AWS cloud fundamentals labs  

---

## 🖥️ Technologies Used

### Identity & Access
- Active Directory Domain Services  
- Group Policy Management  
- Azure AD Connect  
- Microsoft 365 Admin Center  

### Servers & Endpoints
- Windows Server 2022  
- Windows 10/11 Enterprise  
- Ubuntu Server  

### Networking
- pfSense Firewall  
- VLANs  
- DHCP  
- DNS  
- Routing  
- NAT  
- Firewall rules  

### Security
- Wazuh SIEM  
- OpenVAS Vulnerability Scanner  
- Microsoft Defender  
- Least privilege access policies  

### Cloud
- AWS EC2  
- AWS IAM  
- AWS VPC  
- AWS S3  
- AWS Security Groups  
- Cloud architecture fundamentals  

### Operations
- WSUS Patch Management  
- GLPI Ticketing System  
- Documentation & Change Management  

---

## 🗺️ System Architecture

A high-level architecture diagram is included in the `/architecture` directory, illustrating:

- Network segmentation  
- Domain controller placement  
- Firewall and VLAN layout  
- Hybrid identity flow  
- Cloud resource integration  

---

## 📂 Repository Structure

itsolutions-infrastructure-engineer-lab/
├── architecture/
├── active-directory/
├── m365-hybrid/
├── cloud-basics/
├── security/
├── ticketing/
└── README.md

Each folder contains documentation, configuration steps, screenshots, and diagrams.

---

## 📌 Real-World Use Cases

- User onboarding/offboarding  
- Password resets and identity troubleshooting  
- Group Policy enforcement  
- Network segmentation and firewall rule management  
- Patch deployment and compliance  
- Security alert triage and log analysis  
- Vulnerability scanning and remediation  
- Cloud resource provisioning and access control  

---

## 🎯 Roles This Project Aligns With

This lab demonstrates the practical skills required for:

- Infrastructure Engineer  
- Systems Administrator  
- Cloud Support Associate  
- IT Operations Technician  
- Identity & Access Administrator  
- Junior Cloud Engineer  
- M365 Administrator  

---

## 🚀 Future Improvements

Planned enhancements include:

- Intune device management  
- Azure Virtual Machines  
- Terraform automation  
- Docker containerization  
- Load balancing & HAProxy  
- Advanced SIEM dashboards  
- Incident response playbooks  

---

## 📘 Professional Intent

This repository is designed as a demonstration of Infrastructure Engineering capability and serves as a portfolio piece for roles involving systems administration, cloud support, identity management, and enterprise IT operations.
