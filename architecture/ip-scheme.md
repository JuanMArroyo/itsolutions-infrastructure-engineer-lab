# IT Solutions – IP Scheme

This document outlines the IP addressing plan for the IT Solutions enterprise environment.

## 🧩 Network Segments

| VLAN | Purpose | Subnet | Gateway |
|------|---------|--------|---------|
| 10 | Servers | 192.168.10.0/24 | 192.168.10.1 |
| 20 | Workstations | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Management | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Security Tools | 192.168.40.0/24 | 192.168.40.1 |

## 🖥️ Static Assignments

- DC01 – 192.168.10.10  
- WSUS – 192.168.10.20  
- Wazuh – 192.168.40.10  
- OpenVAS – 192.168.40.20  
- pfSense – 192.168.10.1 / 20.1 / 30.1 / 40.1

## 📘 Notes

This IP scheme supports segmentation, security, and scalability for enterprise operations.
