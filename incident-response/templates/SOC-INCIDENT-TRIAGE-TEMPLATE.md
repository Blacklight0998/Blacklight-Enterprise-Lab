
## SOC Alert Triage Report

> Standardized template for the initial triage, investigation, classification, and escalation of security alerts.

---

## 1. Case Information

| Field | Value |
|---|---|
| **Alert ID** | BL-ALT-YYYY-### |
| **Alert Name** | |
| **Analyst** | |
| **Date Opened** | YYYY-MM-DD |
| **Detection Time** | YYYY-MM-DD HH:MM TZ |
| **Detection Source** | SIEM / EDR / IDS / Firewall / User Report / Other |
| **Severity** | Informational / Low / Medium / High / Critical |
| **Priority** | P4 / P3 / P2 / P1 |
| **Status** | New / Investigating / Escalated / Resolved / Closed |

---

## 2. Alert Summary

### Description

Briefly describe what triggered the alert.

### Detection Logic

Document the rule, query, signature, or behavior that generated the alert.

```text
Detection rule / query / signature:
```

### Initial Context

Explain why this activity may represent a security concern.

---

## 3. Affected Entities

| Entity Type | Value | Context |
|---|---|---|
| Hostname | | |
| Username | | |
| Source IP | | |
| Destination IP | | |
| Domain | | |
| Process | | |
| File | | |

---

## 4. Initial Evidence

Record the evidence available at the beginning of the investigation.

| Timestamp | Source | Event / Observation |
|---|---|---|
| | | |
| | | |
| | | |

### Evidence Sources

- [ ] SIEM
- [ ] EDR
- [ ] Windows Event Logs
- [ ] Sysmon
- [ ] Firewall
- [ ] IDS/IPS
- [ ] DNS logs
- [ ] Authentication logs
- [ ] PCAP
- [ ] Email headers
- [ ] Threat Intelligence
- [ ] Other

---

## 5. Triage Questions

### Is the activity expected?

**Answer:**

**Evidence:**

---

### Does the activity present a security risk?

**Answer:**

**Evidence:**

---

### Are additional users, hosts, or systems involved?

**Answer:**

**Evidence:**

---

### Is there evidence of compromise?

**Answer:**

**Evidence:**

---

### Is immediate containment required?

**Answer:**

**Reason:**

---

## 6. Indicators & Artifacts

> An observed indicator is not automatically malicious. Record the context and validation status.

| Type | Value | Reputation / Status | Context |
|---|---|---|---|
| IP Address | | | |
| Domain | | | |
| URL | | | |
| SHA256 | | | |
| File | | | |
| Process | | | |
| User Account | | | |

---

## 7. Threat Intelligence Enrichment

| Indicator | Source | Result | Confidence |
|---|---|---|---|
| | VirusTotal / Other | | Low / Medium / High |

### Notes

Document relevant threat intelligence findings without treating third-party reputation results as definitive proof of malicious activity.

---

## 8. Analyst Assessment

### Disposition

- [ ] True Positive — Malicious
- [ ] True Positive — Suspicious
- [ ] Benign Positive
- [ ] False Positive
- [ ] Inconclusive

### Analyst Confidence

- [ ] Low
- [ ] Medium
- [ ] High

### Assessment

Explain your conclusion using the available evidence.

**Observed facts:**

- 

**Analyst hypothesis:**

- 

**Conclusion:**

- 

---

## 9. MITRE ATT&CK Mapping

| Tactic | Technique | Technique ID | Supporting Evidence |
|---|---|---|---|
| | | | |

> Map ATT&CK techniques only when the observed behavior provides sufficient evidence.

---

## 10. Scope Assessment

### Confirmed Affected Assets

- 

### Potentially Affected Assets

- 

### Additional Investigation Required

- 

---

## 11. Recommended Actions

### Immediate

- [ ] No action required
- [ ] Continue monitoring
- [ ] Collect additional logs
- [ ] Isolate endpoint
- [ ] Disable / restrict account
- [ ] Block IP / domain / hash
- [ ] Escalate investigation
- [ ] Preserve evidence
- [ ] Other

### Action Details

Describe the recommended action and the evidence supporting it.

---

## 12. Escalation Decision

| Field | Value |
|---|---|
| **Escalation Required** | Yes / No |
| **Escalation Level** | Tier 2 / Incident Response / Threat Hunting / Other |
| **Escalation Time** | |
| **Reason** | |

### Information Provided to Escalation Team

- Alert summary
- Relevant evidence
- Affected entities
- Indicators
- Actions already performed
- Outstanding questions

---

## 13. Analyst Notes

Record additional observations, uncertainties, assumptions, or investigation context.

```text
Analyst notes:
```

---

## 14. Closure

| Field | Value |
|---|---|
| **Final Status** | Resolved / Closed / Escalated |
| **Final Disposition** | |
| **Closure Time** | |
| **Resolution** | |

### Closure Summary

Briefly explain what happened, what was determined, and why the alert was closed or escalated.

---

## 15. Evidence References

| Evidence ID | Description | Location |
|---|---|---|
| EV-001 | | |
| EV-002 | | |

---

# Document Control

| Field | Value |
|---|---|
| **Framework** | Blacklight Incident Response Framework |
| **Template** | SOC Alert Triage |
| **Version** | 1.0 |
| **Environment** | Cybersecurity Training / Portfolio Lab |
| **Classification** | Public |
