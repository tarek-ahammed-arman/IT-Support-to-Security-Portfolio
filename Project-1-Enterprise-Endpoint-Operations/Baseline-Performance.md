# PHASE 1 — PERFORMANCE BASELINE

## STEP 1.1 — Idle Performance Measurement

### Objective

Establish baseline system resource utilization under normal idle conditions to enable accurate anomaly detection during later incident simulations.

System performance metrics were captured using **Task Manager** while the endpoint was idle with no active workload.

### Evidence

**Figure 1-15 — Idle System Resource Utilization**

![Idle Processes](Screenshots/Phase-1/Idle_Processes_CPU.png)

### Baseline Metrics

| Resource | Observed Usage |
| -------- | -------------- |
| CPU      | ~0–2%          |
| Memory   | ~34%           |
| Disk     | ~1%            |
| Network  | 0%             |

### Observation

* CPU utilization remained near idle range with no abnormal spikes
* Memory consumption reflected standard background OS processes
* Disk activity was minimal and stable
* No active network traffic detected

### Outcome

A stable operational baseline was confirmed. These metrics provide a reliable reference point for identifying abnormal behavior during performance incident testing.

---

## STEP 1.2 — Startup Application Impact

### Objective

Evaluate startup applications to understand potential performance impact during system boot and login operations.

Startup programs were reviewed through Task Manager.

### Evidence

**Figure 1-16 — Startup Application Impact Assessment**

![Startup Apps](Screenshots/Phase-1/Startup_Applications.png)

### Observation

* Several applications showed measurable startup impact
* Applications were intentionally retained to support controlled performance degradation testing in later phases

### Outcome

Startup configuration was documented without modification to preserve realistic testing conditions.

---

# Phase 1 Performance Status: Completed

System idle performance characteristics and startup impact factors were successfully documented, establishing a reliable performance reference baseline for subsequent incident simulations.
