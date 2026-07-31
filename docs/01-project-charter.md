# Project Charter

This document defines the purpose, objectives, scope, and guiding principles of the **Enterprise Home Network & Homelab** project. It serves as the project's governing document and establishes the foundation for all architectural, technical, and implementation decisions.

---

# 1. Purpose

To design, build, and operate a secure, scalable, enterprise-inspired home network and homelab that serves as a platform for hands-on learning, experimentation, and infrastructure engineering.

The project applies enterprise architecture principles and industry best practices within a residential environment while documenting the complete design and implementation journey.

---

# 2. Vision

To develop a production-quality homelab that demonstrates modern enterprise infrastructure design, enabling continuous learning, experimentation, and technical growth through practical implementation.

---

# 3. Objectives

This project aims to:

- Design and deploy a resilient enterprise-inspired network architecture.
- Implement secure network segmentation and access control.
- Build a scalable virtualization platform for infrastructure and application services.
- Develop practical skills in networking, virtualization, cybersecurity, and infrastructure operations.
- Establish monitoring, logging, and observability across the environment.
- Document architectural decisions, implementation procedures, and operational practices.
- Continuously improve the platform through iterative enhancements and emerging technologies.

---

# 4. Scope

## In Scope

- Enterprise-inspired network architecture
- Firewall, routing, and switching
- Network segmentation
- Virtualization platform
- Self-hosted infrastructure services
- Containerized applications
- Identity and access management
- Monitoring and logging
- Security hardening
- Backup and disaster recovery
- Infrastructure automation
- Technical documentation

## Out of Scope

- Commercial hosting
- Enterprise production workloads
- Multi-site high availability
- Carrier-grade networking
- Revenue-generating services

---

# 5. Success Criteria

The project will be considered successful when:

- Core infrastructure operates reliably and securely.
- Network segmentation functions according to the intended architecture.
- Security controls are implemented and validated.
- Monitoring provides sufficient operational visibility.
- Infrastructure can be rebuilt using documented procedures.
- Documentation accurately reflects the deployed environment.
- New services can be integrated without significant architectural redesign.

---

# 6. Constraints & Assumptions

## Constraints

| Area | Constraint |
|------|------------|
| Budget | Personal funding |
| Environment | Residential apartment |
| Hardware | Commodity x86 hardware |
| Availability | Single-site deployment |
| Time | Part-time development |

## Assumptions

- Reliable fibre Internet connectivity is available.
- Open-source software will be preferred where practical.
- Hardware can be upgraded incrementally over time.
- The environment is intended primarily for learning and experimentation.
- Future technologies can be integrated without major architectural redesign.

---

# 7. Risks

| Risk | Mitigation |
|------|------------|
| Hardware failure | Maintain regular backups and documented recovery procedures |
| Configuration errors | Implement changes incrementally and maintain version control |
| Security vulnerabilities | Apply regular updates and follow security best practices |
| Scope expansion | Follow a phased implementation roadmap |
| Documentation drift | Update documentation alongside infrastructure changes |

---

# 8. Guiding Principles

The project follows these engineering principles:

- **Security by Design** — Build security into every layer of the architecture.
- **Simplicity over Complexity** — Prefer straightforward, maintainable solutions.
- **Documentation First** — Record architecture, decisions, and implementation alongside development.
- **Incremental Improvement** — Build iteratively with continuous refinement.
- **Automation Where Practical** — Reduce manual effort through repeatable automation.
- **Open Standards** — Prioritise interoperable, vendor-neutral technologies where appropriate.
- **Reproducibility** — Ensure the environment can be rebuilt from documented procedures.
- **Continuous Learning** — Use the homelab as a platform for ongoing technical development.

---

# 9. Project Phases

| Phase | Description | Status |
|------|-------------|:------:|
| 1 | Planning & Architecture | ✅ Complete |
| 2 | Core Network Deployment | 🚧 In Progress |
| 3 | Virtualization Platform | ⏳ Planned |
| 4 | Infrastructure Services | ⏳ Planned |
| 5 | Security & Observability | ⏳ Planned |
| 6 | Automation & Optimisation | ⏳ Planned |

---

> **Project Philosophy**
>
> Build an enterprise-inspired infrastructure using practical, repeatable engineering practices while documenting every major architectural decision and implementation. The objective is not merely to operate a homelab, but to develop a well-engineered platform that supports continuous learning, experimentation, and long-term maintainability.
