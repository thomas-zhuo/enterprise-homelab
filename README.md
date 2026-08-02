# Enterprise Homelab

![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise%20Inspired-6f42c1)
![Network](https://img.shields.io/badge/Core-10GbE-success)
![Firewall](https://img.shields.io/badge/Firewall-pfSense%20CE-3949ab)
![Virtualization](https://img.shields.io/badge/Virtualization-Proxmox%20VE-E57000)
![Documentation](https://img.shields.io/badge/Type-Engineering%20Case%20Study-orange)

> **An enterprise-inspired homelab that applies real-world networking, virtualization and cybersecurity principles through structured engineering design, implementation and operational documentation.**

---

# 🚀 Project at a Glance

| | |
|---|---|
| **Project Type** | Enterprise Homelab |
| **Purpose** | Practical Infrastructure Engineering & Cybersecurity |
| **Firewall** | pfSense CE |
| **Virtualization** | Proxmox VE |
| **Network Backbone** | 10GbE Gigabit Ethernet |
| **Internet** | 10Gbps XGS-PON |
| **Documentation Style** | Engineering Design Case Study |
| **Status** | 🚧 In Progress |

---

# 🎯 Overview

This repository documents the complete engineering lifecycle of building an enterprise-inspired homelab.

Rather than focusing only on implementation, the project documents the reasoning behind each technical decision - from requirements gathering and hardware evaluation to architecture design, deployment, operations and continuous improvement.

The objective is to apply enterprise engineering practices within a home environment while developing practical experience in networking, infrastructure engineering and cybersecurity.

---

# ✨ Highlights

This repository includes documentation covering:

- 📋 Requirements Analysis
- 🏛 Enterprise Network Architecture
- ⚖️ Engineering Design Decisions
- 🌐 VLAN & IP Address Design
- 🔥 pfSense Firewall Deployment
- 🔀 Managed Switching
- 📡 Enterprise Wireless Networking
- 🖥 Proxmox Virtualization
- 🔒 Security Hardening
- 📊 Monitoring & Observability
- 🤖 Infrastructure Automation
- 📚 Lessons Learned

---

# 🏗 High-Level Architecture

```text
                                  Internet
                                      │
                                      ▼
                            Huawei XGS-PON ONU
                                      │
                               10GbE SFP+ WAN
                                      │
                                      ▼
                    Dedicated Network Security Appliance
                               (pfSense CE)
                                      │
                          Routing, Security & VPN
                                      │
                               10GbE SFP+ LAN
                                      │
                                      ▼
                              10GbE Core Switch
                                      │
                                      ▼
      ┌───────────────────────┬───────────────────────┬───────────────────────┐
      │                       │                       │                       │
      ▼                       ▼                       ▼                       ▼
 User & Wireless         Smart Devices          Infrastructure        Lab & Services
      Network                Network                 Network               Network
      │                       │                       │                       │
      ▼                       ▼                       ▼                       ▼
 PCs, Mobile Devices     IoT & Cameras       Firewall, Switch, APs    Proxmox, NAS, VMs
 & Guest Devices                               & Hypervisor             & DMZ Services
             
```

*A detailed logical and physical architecture is documented in the Architecture section.*

---

# 📖 Documentation Roadmap

The repository is organised to follow the lifecycle of an infrastructure engineering project.

| Phase | Description |
|-------|-------------|
| 01 | Project Charter |
| 02 | Requirements Analysis |
| 03 | System Architecture |
| 04 | Design Decisions |
| 05 | Network Design |
| 06 | Hardware Selection |
| 07 | Firewall (pfSense) |
| 08 | Switching |
| 09 | Wireless |
| 10 | Virtualization |
| 11 | Infrastructure Services |
| 12 | Security |
| 13 | Monitoring & Observability |
| 14 | Automation |
| 15 | Operations |
| 16 | Roadmap |
| 17 | Lessons Learned |

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|------------|
| Firewall | pfSense CE |
| Hypervisor | Proxmox VE |
| Switching | Managed Layer 2/3 Switch |
| Routing | VLAN Segmentation |
| Internet | ViewQwest 10Gbps XGS-PON |
| Virtualization | KVM |
| Storage | Synology NAS |
| Operating Systems | FreeBSD, Debian, Linux |
| Management | Web UI, SSH |

---

# 🎯 Engineering Principles

The project is guided by several core engineering principles:

- 🔒 Security by Design
- 📈 Scalability
- ⚙️ Simplicity over Complexity
- 📚 Documentation First
- 🔍 Operational Visibility
- 🔄 Continuous Improvement

---

# 📈 Current Progress

| Component | Status |
|-----------|--------|
| Project Planning | ✅ |
| Hardware Selection | ✅ |
| Dedicated Firewall | 🚧 |
| VLAN Design | 🚧 |
| Managed Switching | ⏳ |
| Wireless Infrastructure | ⏳ |
| Virtualization Platform | ⏳ |
| Infrastructure Services | ⏳ |
| Monitoring | ⏳ |
| Automation | ⏳ |

---

# 📌 Repository Philosophy

> [!IMPORTANT]
> This repository focuses on **engineering decisions**, **architecture** and **operational practices**, rather than simply documenting configuration steps.

Every major technical decision is accompanied by its rationale, trade-offs and implementation details to demonstrate the engineering thought process behind the final solution.

---

# 📜 License

This project is currently intended as a personal engineering portfolio and learning repository.
