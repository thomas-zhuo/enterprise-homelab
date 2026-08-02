# Enterprise Homelab

![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise%20Inspired-6f42c1)
![Network](https://img.shields.io/badge/Core-10GbE-success)
![Firewall](https://img.shields.io/badge/Firewall-pfSense%20CE-3949ab)
![Virtualization](https://img.shields.io/badge/Virtualization-Proxmox%20VE-E57000)
![Documentation](https://img.shields.io/badge/Type-Engineering%20Case%20Study-orange)

> **An enterprise-inspired homelab developed as an Infrastructure Engineering Case Study, demonstrating the complete lifecycle of designing, implementing, securing, and operating a modern network to support practical cybersecurity learning.**

---

# Project at a Glance

| | |
|---|---|
| **Project Type** | Enterprise Homelab |
| **Primary Focus** | Cybersecurity Infrastructure |
| **Engineering Discipline** | Infrastructure Engineering |
| **Firewall Platform** | pfSense CE |
| **Virtualization Platform** | Proxmox VE |
| **Network Backbone** | 10GbE Ethernet |
| **Internet Connectivity** | 10Gbps XGS-PON |
| **Documentation Style** | Engineering Case Study |
| **Status** | 🚧 In Progress |

---

# Executive Summary

The Enterprise Homelab is the cornerstone of my cybersecurity portfolio.

Rather than documenting only configuration steps, this repository captures the complete engineering lifecycle of building a secure, enterprise-inspired infrastructure - from project planning and requirements analysis to architecture, implementation, operations, and continuous improvement.

The environment serves as the secure foundation for future cybersecurity projects, including identity management, security monitoring, detection engineering, threat hunting, incident response, and cloud security.

---

# Objectives

This project aims to:

- Apply enterprise infrastructure engineering principles.
- Build a secure and scalable network using security-by-design principles.
- Develop practical cybersecurity skills through hands-on implementation.
- Document engineering decisions, trade-offs, and operational procedures.
- Create a reusable platform for future cybersecurity projects.

---

# High-Level Architecture

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
      ┌───────────────────┬───────────────────┬───────────────────┐
      │                   │                   │                   │
      ▼                   ▼                   ▼                   ▼
 User Network        IoT Network      Infrastructure       Lab Network
                                              │
                                              ▼
                              Proxmox • NAS • Services
```

*A complete logical and physical architecture is documented in the Architecture section.*

---

# Engineering Deliverables

The repository is organised to follow the lifecycle of an enterprise infrastructure engineering project.

| Phase | Deliverable |
|------|-------------|
| 01 | Project Charter |
| 02 | Requirements Analysis |
| 03 | Solution Architecture |
| 04 | Logical Network Design |
| 05 | Physical Infrastructure Design |
| 06 | Security Architecture |
| 07 | IP Addressing & VLAN Plan |
| 08 | Architecture Decision Records (ADRs) |
| 09 | Firewall Deployment |
| 10 | Switching Configuration |
| 11 | Wireless Deployment |
| 12 | Proxmox Deployment |
| 13 | Infrastructure Services |
| 14 | Security Baseline |
| 15 | Monitoring & Observability |
| 16 | Backup & Disaster Recovery |
| 17 | Operations Guide |
| 18 | Roadmap |
| 19 | Lessons Learned |

---

# Technology Stack

| Category | Technology |
|-----------|------------|
| Firewall | pfSense CE |
| Virtualization | Proxmox VE |
| Network | 10GbE Ethernet |
| Switching | Managed Layer 2/3 Switch |
| Internet | ViewQwest XGS-PON |
| Storage | Synology NAS |
| Operating Systems | FreeBSD, Linux |
| Management | Web UI, SSH |

---

# Engineering Principles

The project is guided by the following engineering principles:

- 🔒 Security by Design
- 🏗 Enterprise Architecture
- 📈 Scalability
- ⚙ Simplicity over Complexity
- 📚 Documentation First
- 🔍 Operational Visibility
- 🔄 Continuous Improvement

---

# Current Progress

| Component | Status |
|-----------|--------|
| Planning | ✅ |
| Requirements Analysis | ✅ |
| Architecture Design | 🚧 |
| Firewall Platform | 🚧 |
| Switching | ⏳ |
| Wireless | ⏳ |
| Virtualization | ⏳ |
| Infrastructure Services | ⏳ |
| Monitoring | ⏳ |
| Documentation | 🚧 |

---

# Repository Philosophy

> [!IMPORTANT]
> This repository focuses on engineering thinking as much as technical implementation.

Every major design decision is documented together with its rationale, trade-offs, and implementation approach.

The objective is not only to build a secure enterprise-inspired environment, but also to demonstrate the engineering process behind each decision.

---

# Relationship to the Cybersecurity Portfolio

This repository forms the secure infrastructure foundation for the rest of my cybersecurity portfolio.

```
Enterprise Homelab
        │
        ├── Cybersecurity Labs Portfolio
        ├── Windows Active Directory Lab
        ├── Security Monitoring & SIEM
        ├── Detection Engineering
        ├── Threat Hunting
        ├── Incident Response
        └── Cloud Security
```

Future repositories will build upon the infrastructure documented here.

---

# License

This repository is maintained as a personal engineering portfolio and learning project.
