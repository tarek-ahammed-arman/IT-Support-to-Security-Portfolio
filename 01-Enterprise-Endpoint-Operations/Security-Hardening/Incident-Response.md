# PHASE 6 — SECURITY INCIDENT RESPONSE: FIREWALL RULE VERIFICATION

## Objective

Validate firewall enforcement mechanisms as part of post-incident security hardening and ensure the endpoint is prepared for containment and monitoring scenarios.

---

## STEP 6.6 — Firewall Rule Enforcement Review

Firewall rules were analyzed using **Windows Defender Firewall with Advanced Security**.

---

## STEP 6.6.1 — Inbound Rule Verification

### Action

Opened **Inbound Rules** panel.

### Observations

* Multiple inbound rules configured
* Rules applied across Domain, Private, and Public profiles
* System services protected by predefined policies

### Evidence

**Figure 6-10 — Inbound Firewall Rules**

![Inbound Rules](../Screenshots/Phase-6/Firewall_Inbound_Rules.png)

---

## STEP 6.6.2 — Outbound Rule Verification

### Action

Opened **Outbound Rules** panel.

### Observations

* Application-specific outbound policies present
* Traffic filtering mechanisms active
* Default outbound behavior consistent with Windows security posture

### Evidence

**Figure 6-11 — Outbound Firewall Rules**

![Outbound Rules](../Screenshots/Phase-6/Firewall_Outbound_Rules.png)

---

## STEP 6.6.3 — Rule Detail Inspection

Individual firewall rule properties were reviewed to confirm configuration parameters such as:

* Protocol
* Port scope
* Action (Allow / Block)
* Profile assignment

This confirms enforceable security controls exist at the host level.

---

## Incident Response Relevance

Firewall rules function as:

* Preventive controls against unauthorized access
* Containment tools during incident response
* Enforcement points for network segmentation
* Investigation artifacts during forensic analysis

---

## Verification Outcome

Firewall protection is:

* Active
* Configured
* Enforced
* Observable through administrative tools

---

# Phase 6 Incident Response Status: Completed

Firewall enforcement validated as part of endpoint hardening and incident readiness preparation.
