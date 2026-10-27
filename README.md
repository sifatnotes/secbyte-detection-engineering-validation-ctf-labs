# secbyte-detection-engineering-validation-ctf-labs
A comprehensive index of practical cybersecurity CTF labs focusing on Detection Engineering, Windows/Linux detection, Active Directory &amp; Cloud validation, EDR/SIEM rule testing, YARA &amp; Sigma validation, and Exfiltration/Impact detection.
# Detection Engineering, SIEM, EDR & Attack Validation CTF Labs

Welcome to the **Detection Engineering, SIEM, EDR & Attack Validation CTF Lab Collection**. This repository serves as a structured, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on building, validating, and optimizing defensive telemetry across operating systems (**Windows & Linux**), enterprise identity domains (**Active Directory**), cloud platforms, **EDR/SIEM** deployments, **YARA/Sigma** rule authoring, and late-stage attack vectors (Exfiltration & Impact).

---

## Lab Collection Index

### 1. Detection Engineering Foundations & Signature Mastery
* **Detection Engineering Foundations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-engineering-foundations](https://learn.secbyte.org/ctf/detection-engineering-foundations)  
  *Focus:* Understanding the detection lifecycle, log collection architecture, telemetry normalization, and building high-fidelity alert logic.

* **Sigma Rule Validation Mastery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/sigma-rule-validation-mastery](https://learn.secbyte.org/ctf/sigma-rule-validation-mastery)  
  *Focus:* Writing vendor-agnostic Sigma rules, converting them to target SIEM query languages, testing logic coverage, and reducing rule false positives.

* **YARA Rule Validation & Forensics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/yara-rule-validation-forensics](https://learn.secbyte.org/ctf/yara-rule-validation-forensics)  
  *Focus:* Authoring YARA signatures for malware memory and disk forensics, optimizing byte matching, and validating rule performance against binary samples.

### 2. Host & Environment Detection Labs
* **Windows Detection Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/windows-detection-essentials](https://learn.secbyte.org/ctf/windows-detection-essentials)  
  *Focus:* Analyzing Windows Event Logs (Sysmon, Security, System), process creation tracking (Event ID 4688), PowerShell logging, and registry modification alerts.

* **Linux Detection Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/linux-detection-lab](https://learn.secbyte.org/ctf/linux-detection-lab)  
  *Focus:* Monitoring Auditd, eBPF telemetry, syslog events, cron job persistence, privilege escalation (sudo/SUID abuse), and daemon security.

* **Active Directory Validation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/active-directory-validation](https://learn.secbyte.org/ctf/active-directory-validation)  
  *Focus:* Validating detections for AD attack vectors (Kerberoasting, DCSync, AS-REP Roasting, Golden/Silver Tickets, and Pass-the-Hash).

* **Cloud Attack Validation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/cloud-attack-validation](https://learn.secbyte.org/ctf/cloud-attack-validation)  
  *Focus:* Simulating cloud control plane and workload compromise scenarios to evaluate cloud provider audit trail visibility and detection fidelity.

### 3. SOC Validation, EDR/SIEM & Late-Stage Threat Detections
* **SOC Validation Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soc-validation-operations](https://learn.secbyte.org/ctf/soc-validation-operations)  
  *Focus:* Measuring operational SOC efficiency, testing analyst triage playbooks, evaluating alert SLA responsiveness, and validating escalation flows.

* **SIEM Detection Validation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/siem-detection-validation](https://learn.secbyte.org/ctf/siem-detection-validation)  
  *Focus:* Testing correlation rules across centralized SIEM platforms, checking log pipeline integrity, and detecting parsing anomalies.

* **EDR Detection Validation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/edr-detection-validation](https://learn.secbyte.org/ctf/edr-detection-validation)  
  *Focus:* Benchmarking EDR telemetry collection, process injection detection, behavioral blocking accuracy, and agent tampering alerts.

* **Data Exfiltration Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/data-exfiltration-detection-2](https://learn.secbyte.org/ctf/data-exfiltration-detection-2)  
  *Focus:* Detecting unauthorized data transfers via covert channels (DNS exfiltration, HTTPS POST spikes, cloud storage syncs, and ICMP tunneling).

* **Impact Detection Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/impact-detection-essentials](https://learn.secbyte.org/ctf/impact-detection-essentials)  
  *Focus:* Identifying destructive adversary behaviors, including ransomware encryption routines, volume shadow copy deletion, disk wiping, and service disruption.

---

## Learning Path

### Path A: Core Detection Engineer & Rule Author
1. **Fundamentals & Rules:** Start with [Detection Engineering Foundations](https://learn.secbyte.org/ctf/detection-engineering-foundations), [Sigma Rule Validation Mastery](https://learn.secbyte.org/ctf/sigma-rule-validation-mastery), and [YARA Rule Validation & Forensics](https://learn.secbyte.org/ctf/yara-rule-validation-forensics).
2. **Platform Specifics:** Master host telemetry in [Windows Detection Essentials](https://learn.secbyte.org/ctf/windows-detection-essentials) and [Linux Detection Lab](https://learn.secbyte.org/ctf/linux-detection-lab).
3. **Identity & Cloud:** Secure complex domains via [Active Directory Validation](https://learn.secbyte.org/ctf/active-directory-validation) and [Cloud Attack Validation](https://learn.secbyte.org/ctf/cloud-attack-validation).

### Path B: SOC Operations & EDR/SIEM Assessor
1. **Operations & Pipeline:** Begin with [SOC Validation Operations](https://learn.secbyte.org/ctf/soc-validation-operations) and [SIEM Detection Validation](https://learn.secbyte.org/ctf/siem-detection-validation).
2. **Endpoint Defense:** Benchmark EDR capabilities in [EDR Detection Validation](https://learn.secbyte.org/ctf/edr-detection-validation).
3. **Late-Stage Defense:** Catch advanced tactics using [Data Exfiltration Detection](https://learn.secbyte.org/ctf/data-exfiltration-detection-2) and [Impact Detection Essentials](https://learn.secbyte.org/ctf/impact-detection-essentials).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review scenario directives, log datasets, and system targets.
4. Author rules, analyze host/network telemetry, or execute validation scripts to capture flags.

---

## Target Audience

* **Detection Engineers & Blue Teamers:** Author, test, and validate Sigma/YARA rules and SIEM/EDR detection logic against real-world attack vectors.
* **SOC Analysts & Incident Responders:** Enhance triage capabilities across Windows, Linux, Active Directory, and cloud log sources.
* **Security Architects & Assessor Teams:** Empirically score defensive visibility, EDR agent efficacy, and data exfiltration detection limits.
* **Cybersecurity Students:** Gain practical experience in log analysis, telemetry engineering, and threat detection.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All exercises are intended strictly for authorized security training, defensive learning, and educational research purposes. Unauthorized testing against external systems is strictly prohibited.
