# Enterprise Homelab

![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Project](https://img.shields.io/badge/Project-Enterprise%20Homelab-2ea44f)
![Firewall](https://img.shields.io/badge/Firewall-pfSense%20CE-3949ab)
![Hypervisor](https://img.shields.io/badge/Hypervisor-Proxmox%20VE-E57000)
![Network](https://img.shields.io/badge/Core_Network-10Gbps-success)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise%20Inspired-6f42c1)
![License](https://img.shields.io/badge/License-MIT-green)

> Designing and building an enterprise-inspired home network from the ground up using industry best practices in networking, virtualization, cybersecurity and infrastructure engineering.

---

# Overview

This repository documents the design, implementation and continuous evolution of my enterprise-inspired homelab.

Rather than simply connecting devices to the Internet, this project applies the same engineering principles commonly used in enterprise environments - focusing on security, scalability, reliability, maintainability and operational excellence.

The homelab serves as a platform for learning, experimentation and showcasing practical skills across networking, systems administration and cybersecurity.

The project is documented as an engineering case study, covering the complete lifecycle from requirements gathering and architecture design to implementation, validation and ongoing operations.

---

# Project Objectives

The primary objectives of this project are to:

- Design an enterprise-inspired network architecture
- Build a secure and scalable infrastructure
- Separate networking from virtualization using dedicated hardware
- Implement secure network segmentation using VLANs
- Support 10Gbps networking across the core infrastructure
- Deploy enterprise-grade security controls
- Build a resilient virtualization platform
- Implement centralized monitoring and logging
- Automate infrastructure management where appropriate
- Document engineering decisions throughout the project

---

# Architecture Overview

```text
                    Internet
                         │
              XGS-PON Fibre Service
                         │
             Huawei OptiXstar S800E ONU
                         │
                 pfSense Firewall
                 (Dedicated Appliance)
                         │
                  10Gbps Core Switch
        ┌──────────┬───────────┬──────────┐
        │          │           │
    Trusted LAN  Servers      Wireless
        │          │           │
   Workstations  Proxmox     Access Points
                    │
         Virtual Machines & Containers
```

---

# Core Design Principles

This infrastructure is designed around several key engineering principles.

## Security by Design

Security is incorporated into every stage of the design rather than being treated as an afterthought.

Examples include:

- Dedicated firewall appliance
- Network segmentation
- Least privilege
- Secure management network
- VPN
- IDS/IPS
- DNS filtering

---

## Scalability

The infrastructure is designed to support future growth with minimal redesign.

Examples include:

- 10Gb backbone
- Layer 3 switching
- Expandable virtualization platform
- Modular architecture
- Future High Availability support

---

## Reliability

Critical infrastructure is separated into dedicated functional layers.

Examples include:

- Dedicated firewall
- Managed switching
- Enterprise wireless
- Independent virtualization platform
- Monitoring
- Backup strategy

---

## Maintainability

Every engineering decision, architecture diagram and implementation step is documented to ensure the environment remains reproducible, understandable and easy to troubleshoot.

---

# Technology Stack

| Category | Technology |
|-----------|------------|
| Firewall | pfSense Community Edition |
| Firewall Hardware | Intel Core i7-13620H |
| Network Controllers | Intel I226-V / Intel 82599ES |
| Core Networking | 10Gb SFP+ |
| Virtualization | Proxmox VE |
| Switching | Managed Layer 3 Switch |
| Monitoring | Planned |
| VPN | WireGuard (Planned) |
| IDS / IPS | Suricata (Planned) |
| DNS Filtering | pfBlockerNG (Planned) |

---

# Project Roadmap

| Component | Status |
|-----------|--------|
| Requirements Analysis | ✅ Complete |
| Architecture Design | ✅ Complete |
| Hardware Evaluation | ✅ Complete |
| Firewall Platform | ✅ Complete |
| pfSense Deployment | ✅ Complete |
| Switch Configuration | 🚧 In Progress |
| VLAN Implementation | 🚧 In Progress |
| Wireless Infrastructure | 📋 Planned |
| Virtualization Platform | 🚧 In Progress |
| Infrastructure Services | 📋 Planned |
| IDS / IPS | 📋 Planned |
| VPN | 📋 Planned |
| Monitoring | 📋 Planned |
| Automation | 📋 Planned |

---

# Documentation

This repository is organised as a series of engineering documents.

| Section | Description |
|----------|-------------|
| Project Overview | Background, goals and project scope |
| Requirements | Functional and non-functional requirements |
| Architecture | Logical, physical and security architecture |
| Design Decisions | Trade-off analysis and engineering rationale |
| Network Design | IP addressing, VLANs, routing and DNS |
| Hardware Selection | Evaluation and hardware selection process |
| Firewall | Dedicated pfSense deployment |
| Switching | VLANs, trunks, LACP and switch configuration |
| Wireless | Enterprise Wi-Fi design |
| Virtualization | Proxmox infrastructure |
| Infrastructure Services | Self-hosted applications |
| Security | Hardening, VPN, IDS/IPS and segmentation |
| Monitoring | Metrics, logging and observability |
| Automation | Infrastructure automation |
| Operations | Backup, recovery and maintenance |
| Future Roadmap | Planned enhancements |
| Lessons Learned | Engineering reflections |

---

# Skills Demonstrated

This project demonstrates practical experience in:

### Infrastructure Engineering

- Requirements Analysis
- Solution Architecture
- Hardware Evaluation
- Infrastructure Design
- Technical Documentation
- Change Management

### Networking

- Enterprise Network Design
- Layer 2 & Layer 3 Switching
- VLAN Segmentation
- IP Address Planning
- Routing
- Firewall Policy Design
- DNS & DHCP

### Cybersecurity

- Network Segmentation
- Secure Perimeter Design
- VPN Architecture
- Infrastructure Hardening
- IDS / IPS Planning
- Zero Trust Principles

### Systems Administration

- pfSense
- FreeBSD
- Proxmox VE
- Linux
- Enterprise Network Hardware

---

# Future Enhancements

Planned improvements include:

- WireGuard Remote Access
- Suricata IDS / IPS
- pfBlockerNG
- IPv6
- High Availability (CARP)
- Centralised Logging
- Infrastructure Monitoring
- Automated Configuration Backups
- Configuration Management
- Network Access Control (802.1X)

---

# Repository Structure

```text
enterprise-homelab/
│
├── README.md
│
├── docs/
│   ├── 01-project-overview/
│   ├── 02-requirements/
│   ├── 03-architecture/
│   ├── 04-design-decisions/
│   ├── 05-network-design/
│   ├── 06-hardware-selection/
│   ├── 07-firewall/
│   ├── 08-switching/
│   ├── 09-wireless/
│   ├── 10-virtualization/
│   ├── 11-services/
│   ├── 12-security/
│   ├── 13-monitoring/
│   ├── 14-automation/
│   ├── 15-operations/
│   ├── 16-future-roadmap/
│   └── 17-lessons-learned/
│
├── diagrams/
├── screenshots/
├── configs/
├── scripts/
└── assets/
```

---

# Project Philosophy

This repository is intended to document **the engineering process**, not merely the final configuration.

Wherever possible, implementation decisions are supported by architectural reasoning, alternative approaches are evaluated, and technical trade-offs are documented.

The objective is to build a maintainable, enterprise-inspired infrastructure while continuously learning and applying industry best practices.

---

## License

This repository is maintained for educational, documentation and portfolio purposes.
