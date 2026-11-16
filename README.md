# Hritam Dutta

**Cybersecurity Professional | Computer Science Graduate | Security Operations & Defensive Security Engineering**

Computer Science graduate with a **9.14/10 CGPA** and more than three years of professional experience across security operations, incident response, threat hunting and technology risk. My experience includes SIEM/EDR-based investigations, security monitoring, enterprise application security and access-control risk assessment.

Alongside my professional work, I develop independent Python cybersecurity tools addressing security-event analysis and digital evidence integrity. I am interested in advancing my understanding of network and systems security, dependable detection methods, investigation traceability and the integrity of digital evidence.

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

My interests centre on the reliability and investigation of security events across networked and computer systems. I am particularly interested in:

- **Network and systems security:** understanding system and network behaviour, attack surfaces and defensive controls.
- **Detection engineering:** developing and evaluating methods for identifying suspicious authentication, network and DNS activity, including their limitations.
- **Digital forensics and evidence integrity:** preserving event provenance, verifying evidence integrity and supporting traceable investigations.

These interests connect my academic foundation in computer science with my professional experience in security operations and my independent project work.

---

## Featured Projects

Independent Python cybersecurity projects focused on defensive security engineering, security analysis and digital evidence integrity.

### 01. [SOC Sentinel](https://github.com/Hritam06/soc-sentinel)

**Python Security Monitoring, Detection & Investigation Toolkit** · **v3.0.0**  
<sub>Security Operations · Detection Engineering · Event Correlation · Investigation Reporting</sub>

SOC Sentinel addresses the practical problem of turning heterogeneous security-event records into structured, traceable findings for investigation. The V3.0.0 pipeline validates and normalizes JSON/JSONL events, applies heuristic authentication, network and DNS detections, correlates supported activity and generates investigation reports.

**Key Capabilities**

- Eight heuristic detection rules covering brute-force-like login attempts, password spraying, failure-then-success sequences, multi-source account targeting, authentication bursts, port scanning, connection fan-out and suspicious DNS queries.
- Event-level provenance for supported alerts, retaining event identifiers, source and target context, triggering conditions and evidence details.
- Cross-event correlation for supported authentication and network-activity relationships.
- Validated JSON/YAML configuration, environment-variable overrides, configurable thresholds and investigation windows, allowlists, severity overrides and process-local duplicate suppression.
- Explainable heuristic risk scoring with explicit asset-criticality and attack-progression inputs; these are not automatically inferred by the CLI.
- Structured JSON and self-contained HTML reporting, with relevant MITRE ATT&CK technique mappings.
- A reproducible evaluation runner that matches predictions to labels by event ID across six rules. The supplied dataset contains 46 labelled synthetic events; its perfect precision, recall and F1 results apply only to those controlled scenarios and do not establish production detection effectiveness.

**Technology Stack:** Python 3.11+, Pydantic, PyYAML, JSON, YAML, pytest, GitHub Actions.

**Validation:** 161 local tests passed on Python 3.14.8; GitHub Actions passed on Python 3.11 and 3.12. Dependency consistency and byte-compilation checks passed. Wheel and source distribution built successfully.

<sub>**Project Resources:** [Repository](https://github.com/Hritam06/soc-sentinel) · [Documentation](https://github.com/Hritam06/soc-sentinel/blob/main/README.md) · [Evaluation Methodology](https://github.com/Hritam06/soc-sentinel/blob/main/docs/EVALUATION.md) · [v3.0.0 Release](https://github.com/Hritam06/soc-sentinel/releases/tag/v3.0.0)</sub>

---

### 02. [KASEVRA - Digital Evidence & Integrity Toolkit](https://github.com/Hritam06/kasevra)

**Offline-First Digital Evidence & Integrity Toolkit** · **v2.0.0**  
<sub>Digital Forensics · Evidence Integrity · Forensic Reporting</sub>

KASEVRA addresses file-level evidence handling by providing an offline-first workflow to acquire selected files, record their SHA-256 hashes, verify collected content and compare it with reference baselines. Its V2.0.0 programmatic API extends this workflow with signed manifests, hash-linked custody records and structured reports.

**Key Capabilities**

- Selected-file acquisition with streamed SHA-256 hashing and a versioned evidence manifest.
- Canonical manifest serialization and digest validation.
- Independent verification that distinguishes matching, modified, missing, unexpected and errored evidence.
- Reference baseline creation and comparison.
- Ed25519 key management and detached signatures over manifest bytes.
- Hash-linked chain-of-custody events with append and validation helpers.
- Structured JSON and HTML reporting.
- V1 command-line interface retained for backward compatibility; V2 capabilities are exposed through programmatic Python APIs.

A matching hash supports an integrity comparison; it does not independently establish evidence authenticity, provenance or legal admissibility.

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
