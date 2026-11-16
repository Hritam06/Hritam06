# Hritam Dutta

**Cybersecurity Professional | Computer Science Graduate | Security Operations & Defensive Security Engineering**

Computer Science graduate with a **9.14/10 CGPA** and more than three years of professional experience in cybersecurity across security operations, incident response, threat hunting and technology risk. My work has included SIEM/EDR-based investigations, security monitoring, enterprise application security and access-control risk assessment.

I combine practical SOC experience with independent Python projects in security monitoring, detection engineering and digital evidence integrity. My academic and technical interests include network and systems security, cybersecurity engineering, digital forensics and security assurance.

[Portfolio](https://hritam06.github.io/hritam-portfolio/) · [LinkedIn](https://www.linkedin.com/in/hritam-dutta06/) · [GitHub](https://github.com/Hritam06) · [Email](mailto:hritam.dutta.official@gmail.com)

---

## Education

**Bachelor of Technology - Computer Science and Engineering**  
B. P. Poddar Institute of Management and Technology  
Affiliated to Maulana Abul Kalam Azad University of Technology, West Bengal  
*August 2019 - July 2023*

**CGPA:** 9.14 / 10

Relevant coursework: Computer Networks, Operating Systems, Computer Architecture, Distributed Systems, Cyber Security, Cryptography and Network Security, Data Structures and Algorithms, and Cloud Computing.

---

## Academic & Research Interests

- Network and systems security
- Security monitoring and detection engineering
- Intrusion detection and incident investigation
- Digital forensics and evidence integrity
- Secure systems and defensive security engineering
- Cybersecurity risk assessment and assurance

---

## Featured Projects

Independent Python cybersecurity projects focused on defensive security engineering, security analysis and digital evidence integrity.

### 01. [SOC Sentinel](https://github.com/Hritam06/soc-sentinel)

**Python Security Monitoring, Detection & Investigation Toolkit** · **v3.0.0**  
<sub>Security Operations · Detection Engineering · Event Correlation · Investigation Reporting</sub>

A defensive security-monitoring pipeline that ingests and normalizes JSON/JSONL security events, applies heuristic authentication, network and DNS detections, correlates related activity, and produces structured investigation reports with traceable alert evidence.

**Key Capabilities**

- Validated event ingestion and normalization, retaining source-event context and raw event data.
- Eight heuristic detection rules across authentication, network and DNS activity: brute-force-like login attempts, password spraying, failure-then-success sequences, multi-source account targeting, authentication bursts, port scanning, connection fan-out and suspicious DNS queries.
- Event-level alert provenance for supported detections, including event identifiers, source and target entities, triggering conditions, evidence context and recommended actions where supplied.
- Cross-event investigation correlation for supported authentication and network-activity relationships.
- Validated JSON/YAML configuration, environment-variable overrides, configurable thresholds and investigation windows, allowlists, severity overrides and process-local duplicate suppression.
- Explainable heuristic risk scoring with explicit asset-criticality and attack-progression inputs; these values are not automatically inferred by the CLI.
- Structured alerts and self-contained JSON/HTML investigation reporting, with relevant MITRE ATT&CK technique mappings.
- Reproducible evaluation against 46 labelled synthetic events across six detection rules. The supplied scenarios record precision, recall and F1 of 1.0; these controlled results do not establish production detection effectiveness.

**Technology Stack:** Python 3.11+, Pydantic, PyYAML, JSON, YAML, pytest, GitHub Actions.

**Validation:** 161 local tests passed on Python 3.14.8; GitHub Actions passed on Python 3.11 and 3.12. Dependency consistency and byte-compilation checks passed. Wheel and source distribution built successfully.

<sub>**Project Resources:** [Repository](https://github.com/Hritam06/soc-sentinel) · [Documentation](https://github.com/Hritam06/soc-sentinel/blob/main/README.md) · [Evaluation Methodology](https://github.com/Hritam06/soc-sentinel/blob/main/docs/EVALUATION.md) · [v3.0.0 Release](https://github.com/Hritam06/soc-sentinel/releases/tag/v3.0.0)</sub>

---

### 02. [KASEVRA - Digital Evidence & Integrity Toolkit](https://github.com/Hritam06/kasevra)

**Offline-First Digital Evidence & Integrity Toolkit** · **v2.0.0**  
<sub>Digital Forensics · Evidence Integrity · Forensic Reporting</sub>

An offline-first, file-level Python toolkit for digital evidence acquisition, SHA-256 integrity verification, baseline comparison, cryptographic signatures, chain-of-custody records and structured forensic reporting.

**Key Capabilities**

- Selected-file evidence acquisition with streamed SHA-256 hashing.
- Versioned V2 evidence manifest schema with canonical serialization and digest validation.
- Independent integrity verification identifying matching, modified, missing, unexpected and errored evidence.
- Reference baseline creation and comparison.
- Ed25519 key management and detached manifest signatures.
- Hash-linked chain-of-custody events with append and validation helpers.
- Structured JSON and HTML reporting.
- Existing V1 CLI preserved for backward compatibility, with V2 capabilities available through programmatic Python APIs.
- Offline-first operation and security-conscious evidence handling.

**Technology Stack:** Python, SHA-256, Ed25519, cryptography, Typer, Rich, pytest, Ruff, GitHub Actions.

**Validation:** 145 tests passed, 1 platform-specific test skipped locally. Cross-platform CI passed across Ubuntu, macOS and Windows with Python 3.11–3.14. Wheel and source distribution built and passed package validation.

**Project Resources:** [Repository](https://github.com/Hritam06/kasevra) · [Documentation](https://github.com/Hritam06/kasevra/blob/main/README.md) · [v2.0.0 Release](https://github.com/Hritam06/kasevra/releases/tag/v2.0.0)

---

## Professional Experience

### Deloitte USI | Hyderabad, India

**Cyber Security Analyst / SOC Analyst**  
*August 2026 - Present*

- Monitor, triage and investigate security alerts across enterprise environments.
- Analyse endpoint, server and network telemetry to investigate suspicious activity.
- Perform threat hunting and indicator-of-compromise analysis.
- Document findings and escalate incidents in accordance with SOC procedures and service-level expectations.

**Confidentiality & Privacy Risk Analyst**  
*May 2025 - August 2026*

- Conducted enterprise application security and privacy risk assessments.
- Reviewed application permissions, Microsoft Graph API access and third-party integrations.
- Identified potential data exposure, access-control weaknesses and privacy risks.
- Documented findings and recommended remediation measures.

### PwC India | Kolkata, India

**Associate - Cyber Security / SOC Analyst**  
*July 2023 - April 2025*

- Monitored and investigated security alerts across client environments.
- Performed alert triage, log analysis, IOC analysis and incident investigation.
- Supported threat hunting, incident escalation and closure within agreed SLAs.
- Contributed to client communications, junior analyst support and SOC process improvements.

**SOC Analyst Intern**  
*January 2023 - July 2023*

- Supported security monitoring, alert triage and initial investigation activities within the SOC.

---

## Technical Skills

**Security Monitoring & SIEM**  
Google SecOps, Splunk, Microsoft Sentinel, ArcSight, Securonix

**Endpoint Security & EDR**  
Microsoft Defender, CrowdStrike, SentinelOne, Cortex XDR

**Security Operations**  
Incident response, alert triage, threat hunting, IOC analysis, log analysis, detection and investigation

**Programming & Development**  
Python, JSON, Git, GitHub, pytest, GitHub Actions

**Digital Forensics & Integrity**  
SHA-256, evidence collection, hash verification, baseline comparison, structured reporting

**Computer Science Foundations**  
Computer networks, operating systems, distributed systems, computer architecture, cryptography and cloud computing

---

## Certifications

- [Microsoft Certified: Cybersecurity Architect Expert (SC-100)](https://learn.microsoft.com/api/credentials/share/en-us/HritamDutta06/4694B4ED07E2C6C7?sharingId=8B815602754225CD) · November 2026
- [Microsoft Certified: Security Operations Analyst Associate (SC-200)](https://learn.microsoft.com/api/credentials/share/en-us/HritamDutta06/AD228EF2176A5E0E?sharingId=8B815602754225CD) · October 2026
- [Microsoft Certified: Azure AI Fundamentals (AI-901)](https://learn.microsoft.com/api/credentials/share/en-us/HritamDutta06/9B0992F3CB5BFD5?sharingId=8B815602754225CD) · October 2026

---

I welcome conversations about cybersecurity, network and systems security, digital forensics, security engineering and defensive security research.
