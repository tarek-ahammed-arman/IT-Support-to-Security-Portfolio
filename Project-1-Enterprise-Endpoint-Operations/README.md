# Enterprise Endpoint Operations & SOC Foundations Lab

## Purpose

This repository demonstrates a hands-on enterprise-style Windows endpoint lab, simulating real-world IT Support and SOC workflows. The lab emphasizes **structured operational processes, incident detection, root cause analysis, and security validation**, rather than advanced tooling.  

Key focus areas:  

- Endpoint baseline assessment and validation  
- Performance monitoring and troubleshooting  
- Controlled incident simulation (CPU, disk, applications, network, identity)  
- Security hardening and verification  
- Evidence-based documentation

The project showcases **operational readiness and methodical problem-solving**, foundational skills for entry-level SOC, IT support, and endpoint security roles.

---

## Environment Overview

- **Platform:** Windows 11 Virtual Machine  
- **Hypervisor:** Oracle VirtualBox  
- **CPU:** 2 vCPU | **Memory:** 8 GB | **Storage:** 60 GB virtual disk  
- **Network:** NAT (isolated lab environment)  

### User Model

- **LocalAdmin** — Administrator  
- **User-1** — Standard User  
- **User-2** — Standard User  

### Snapshot Strategy

A **Clean-Baseline** snapshot preserves a known-good state, enabling safe rollback and repeatable incident testing.

---

## Project Phases

### Phase 0 — Lab Preparation

Environment setup and configuration validation.  
**Files:** Architecture-and-Baseline.md

### Phase 1 — Endpoint Baseline

Documented OS version, patching, hardware and resource usage, startup applications, services, security controls, event logs, and least privilege validation.  
**Files:** Architecture-and-Baseline.md, Baseline-Performance.md, Baseline-Event-Logs/

### Phase 2 — CPU Performance Incident

Simulated CPU saturation to demonstrate performance monitoring, root cause analysis, and remediation workflow.  
**Files:** Performance-Troubleshooting/CPU-RCA.md

### Phase 3 — Disk Bottleneck & Storage Exhaustion

Disk saturation and VM pause incident to illustrate I/O monitoring, performance investigation, and host-level capacity management.  
**Files:** Performance-Troubleshooting/Disk-RCA.md, Incident-Reports/VM-Storage-Exhaustion.md

### Phase 4 — Application Crash Incident

Controlled application termination to validate process-level observation, recovery verification, and evidence-based documentation.  
**Files:** Incident-Reports/App-Crash-Incident.md

### Phase 5 — Network & Identity Incidents

DNS failure simulation and account lockout to demonstrate basic network troubleshooting and identity incident handling.  
**Files:** Incident-Reports/Network-Failure-Incident.md, Incident-Reports/Identity-Troubleshooting.md

### Phase 6 — Security Hardening

Endpoint protection verification, firewall rule enforcement, and UAC review to illustrate post-incident security hygiene.  
**Files:** Security-Hardening/Defender-Analysis.md, Security-Hardening/Hardening-Checklist.md, Security-Hardening/Incident-Response.md

---

## Evidence Handling

Screenshots are organized by phase:

```
Screenshots/
├── Phase-0
├── Phase-1
├── Phase-2
├── Phase-3
├── Phase-4
├── Phase-5
└── Phase-6
```

File naming follows incident-based evidence standards for clarity and auditability.

---

## Skills Demonstrated

- Windows endpoint administration and baseline validation  
- Performance monitoring and troubleshooting  
- Root cause analysis (RCA) methodology  
- Event log review and evidence documentation  
- Identity and access troubleshooting  
- Network diagnostics  
- Virtualization awareness  
- Security hardening and compliance validation  
- Incident lifecycle documentation

---

## Incident Lifecycle Model

**Baseline → Detection → Analysis → Remediation → Verification → Hardening**  

This structure reflects **real-world operational procedures** used in IT support and SOC environments.

---

## Career Relevance

The lab aligns with responsibilities for:  

- IT Support Specialist  
- SOC Analyst (Tier 1)  
- Endpoint Support Engineer  
- Junior Security Engineer  

It demonstrates **operational readiness, investigative discipline, and security awareness**, building a foundation for advanced cloud security skills.

---

## Status

Project completed with **full documentation, evidence, and verified outcomes**.