# Endpoint Security & System Operations Lab

## Purpose

This project demonstrates a hands-on Windows endpoint security lab simulating real-world system operations and incident scenarios. It focuses on structured analysis of system behavior, including baseline validation, performance troubleshooting, incident simulation, and security hardening in a controlled environment.

Key focus areas:  

- Endpoint baseline assessment and validation  
- Performance monitoring and troubleshooting  
- Controlled incident simulation (CPU, disk, applications, network, identity)  
- Security hardening and verification  
- Evidence-based documentation

The project reflects practical skills in system security, incident analysis, and endpoint operations.

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

This lab aligns with foundational responsibilities in:

- IT Support and System Administration
- Security Operations and Incident Analysis
- Junior Security Engineering roles 

It demonstrates operational readiness, investigative discipline, and system-level security understanding, forming a foundation for advanced cloud security engineering skills.

---

## Status

Project completed with **full documentation, evidence, and verified outcomes**.
