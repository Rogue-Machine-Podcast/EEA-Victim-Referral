**Appendix B: Security Policies**

# APPENDIX B: SECURITY POLICIES

## Overview

This appendix documents the security policies and procedures implemented by Brian Spector and 2REAL LLC to protect trade secret information. These policies demonstrate compliance with the "reasonable measures" requirement of 18 U.S.C. § 1839(3)(A) — that the owner "has taken reasonable measures to keep such information secret."

---

\newpage

## 1. Information Classification Policy

### Classification Levels

| Level | Description | Handling Requirements |
|-------|-------------|----------------------|
| **PROPRIETARY** | Core trade secrets, source code, algorithms | Encryption required; need-to-know access only |
| **CONFIDENTIAL** | Business plans, financial projections, partner data | Restricted distribution; NDA required |
| **INTERNAL** | General business documentation | Company personnel only |
| **PUBLIC** | Marketing materials, public announcements | No restrictions |

### Trade Secret Classification

**PROPRIETARY** (Core trade secrets, source code, algorithms):

1. **Triple-B Protocol Technical Specifications** — Bitcoin Bearer Bond protocol architecture (Ordinals-native L1)

2. **DREY FINANCE, FAIRPLAY HEROES, 2REAL Finance Codebases** — Complete source code repositories

3. **Cryptographic Implementation Details** — Key generation, signing mechanisms, threshold signature configurations

**CONFIDENTIAL** (Business plans, protocols, partner data):

4. **Fair Play Game Protocol** — Verifiable fairness algorithms and implementation

5. **Fairplay Heroes Protocol** — Provably fair raffle system (League of Entropy, Bitcoin hashes, RSA 4096-bit, Fisher-Yates)

6. **Business Plans & Revenue Models** — Financial projections, partnership strategies, market analysis

7. **Network Architecture** — Backend infrastructure, WebRTC implementation, API designs

**INTERNAL** (Company personnel only):

8. **Character Designs and Game Assets** — Original creative works (Axel, Rand0, Bitty, Hasher, Ori, Satoeshi, Phil, iBe, Tappy)

---

\newpage

## 2. Access Control Policy

### Physical Security

| Measure | Implementation | Status |
|---------|----------------|--------|
| Secure Development Environment | Dedicated workstations for sensitive work | ✔ Implemented |
| No Public Disclosure | Technical details never published | ✔ Maintained |
| Limited Distribution | Access restricted to essential personnel | ✔ Enforced |

### Digital Access Controls

| Measure | Implementation | Status |
|---------|----------------|--------|
| Multi-Factor Authentication | Required for all sensitive systems | ✔ Implemented |
| Unique User Credentials | Individual accounts for all users | ✔ Enforced |
| Role-Based Access Control | Access limited by job function | ✔ Implemented |
| Password Policy | Minimum 12 characters, complexity requirements | ✔ Enforced |

### Personnel Access Restrictions

| Role | Access Level | Approved Personnel |
|------|--------------|-------------------|
| Technical Lead | Full codebase access | Brian Spector |
| CMO | Business plans, marketing assets | Nicola McNamee |
| Contractors | Project-specific code modules only | Per-project basis |
| Legal Counsel | Litigation documents only | Attorney-client privilege |

---

\newpage

## 3. Data Protection Policy

### Encryption Standards

| Data State | Encryption Method | Implementation |
|------------|-------------------|----------------|
| **At Rest** | AES-256 | All storage devices |
| **In Transit** | TLS 1.3 | All network communications |
| **Backups** | AES-256 with separate key | Encrypted backup drives |

### Storage Security

| System | Security Measures |
|--------|-------------------|
| **Primary Development** | Encrypted SSD, full-disk encryption |
| **Cloud Storage** | Zero-knowledge encryption (ProtonDrive) |
| **Code Repositories** | Private repositories, SSH authentication |
| **Backup Media** | Hardware-encrypted external drives |

---

\newpage

## 4. Document Control Policy

### Version Control

| Measure | Implementation |
|---------|----------------|
| Git Repositories | All code under version control |
| Commit Logging | Complete audit trail of all changes |
| Branch Protection | Main branch protected; review required |
| Access Logging | All repository access logged |

### Document Handling

| Document Type | Handling Procedure |
|---------------|-------------------|
| Technical Specifications | Watermarked; recipient tracking |
| Source Code | Private repository only; no public forks |
| Business Plans | Password-protected; expiring links |
| Legal Documents | Attorney-client privilege; secure transmission |

### Destruction Protocols

| Scenario | Procedure |
|----------|-----------|
| Contractor Termination | Immediate revocation of all access |
| Device Disposal | Secure erase (DoD 5220.22-M standard) |
| Paper Documents | Cross-cut shredding |
| Cloud Data | Verified deletion; retention policy enforcement |

---

\newpage

## 5. Network Security Policy

### Development Environment Isolation

| Measure | Implementation |
|---------|----------------|
| Network Segmentation | Development network isolated from general access |
| Firewall Rules | Whitelist-only outbound connections |
| VPN Required | All remote access via encrypted VPN |
| DNS Security | Encrypted DNS; malicious domain blocking |

### Monitoring and Detection

| System | Coverage |
|--------|----------|
| Intrusion Detection | Network-level IDS/IPS |
| Endpoint Protection | EDR on all development machines |
| Log Aggregation | Centralized logging with retention |
| Anomaly Detection | Baseline monitoring for unusual activity |

---

\newpage

## 6. Employee Security Policy

### Pre-Employment

| Measure | Status |
|---------|--------|
| Background Verification | ✔ For all technical contributors |
| Reference Checks | ✔ Professional references verified |
| NDA Execution | ✔ Required before any access granted |

### During Employment

| Measure | Status |
|---------|--------|
| Need-to-Know Access | ✔ Minimum necessary access principle |
| Security Awareness | ✔ Regular briefings on threats |
| Acceptable Use Policy | ✔ Signed acknowledgment required |
| Device Management | ✔ Company-controlled devices for sensitive work |

### Termination

| Measure | Status |
|---------|--------|
| Exit Interview | ✔ Confidentiality obligations reviewed |
| Access Revocation | ✔ Immediate upon termination |
| Return of Materials | ✔ All devices, documents, credentials |
| Post-Employment Monitoring | ✔ For violations of non-compete/NDA |

---

\newpage

## 7. Third-Party Security Policy

### Vendor Requirements

| Requirement | Implementation |
|-------------|----------------|
| NDA Execution | Required before any engagement |
| Security Assessment | Review of vendor security practices |
| Data Minimization | Minimum necessary information shared |
| Contractual Protections | Security obligations in all contracts |

### Legal Counsel Requirements

| Requirement | Implementation |
|-------------|----------------|
| Conflict Check | Required before engagement |
| Secure Communication | Encrypted email preferred |
| Document Handling | Attorney-client privilege maintained |
| Access Limitations | Need-to-know within firm |

---

\newpage

## 8. Incident Response Policy

### Detection and Reporting

| Event | Response |
|-------|----------|
| Suspected Breach | Immediate notification to security lead |
| Unauthorized Access | Access revoked; investigation initiated |
| Malware Detection | Isolation; forensic preservation |
| Legal Process | Counsel engaged; response coordinated |

### Post-Incident Procedures

| Phase | Actions |
|-------|---------|
| Containment | Isolate affected systems |
| Eradication | Remove threat; patch vulnerabilities |
| Recovery | Restore from clean backups |
| Lessons Learned | Policy updates; training improvements |

---

\newpage

## 9. Compliance and Legal Protections

### Court-Ordered Protections

| Date | Court | Protection |
|------|-------|------------|
| April 29, 2024 | High Court (Roth J) | Interim injunction protecting IP |
| May 7, 2024 | High Court (Mann J) | Reaffirmed injunction; IP declared Spector's |
| August 8, 2025 | High Court (DM Dray) | Final order that provided declaratory relief via Severina's Schedule A undertakings |

### Regulatory Compliance

| Framework | Status |
|-----------|--------|
| GDPR (EU/UK) | Compliant — data protection measures implemented |
| CCPA (California) | Not applicable — no CA consumer data |
| SOC 2 Type I | Informal alignment — no formal audit |

---

## 10. Policy Enforcement and Review

### Enforcement Mechanisms

| Mechanism | Implementation |
|-----------|----------------|
| Technical Controls | Access controls, encryption, monitoring |
| Administrative Controls | Policies, training, NDAs |
| Physical Controls | Secure facilities, device management |

### Review Schedule

| Review Type | Frequency |
|-------------|-----------|
| Policy Review | Annual |
| Access Audit | Quarterly |
| Incident Review | After each incident |
| Penetration Testing | Annual (planned) |

---

\newpage

## How Security Was Circumvented

Despite these reasonable measures, trade secrets were obtained through criminal means including:

1. **APT29 Malware** — Nation-state grade steganographic malware bypassing endpoint protection (November 2023)

2. **Human Intelligence Asset** — Lilia Severina infiltrated as trusted co-founder (January-April 2024)

3. **Law Firm Compromise** — Six UK law firms either compromised or operationally controlled

4. **Litigation Abuse** — Discovery process weaponized to extract proprietary information

**Conclusion:** The security breach required sophisticated state-sponsored cyber operations combined with human intelligence tradecraft. This demonstrates that reasonable measures were in place, and the theft required extraordinary criminal activity to circumvent them.

---

## Verification Statement

I, Brian Spector, declare under penalty of perjury under the laws of the United States (28 U.S.C. § 1746) that:

1. The security policies described above were in effect during the relevant time period

2. These policies represent reasonable measures to protect trade secrets

3. The breach of these protections required sophisticated criminal activity


**Brian Spector**
\vspace{2em}


**Signature:** ____________________________
\vspace{2em}

**Date:** February 3, 2026

---

## Evidence Cross-Reference

| Appendix | Related Content |
|----------|-----------------|
| APPENDIX_A | Confidentiality agreements implementing policy |
| APPENDIX_C | Access logs demonstrating enforcement |
| APPENDIX_D | Forensic evidence of circumvention methods |
| 04_PROTECTIVE_MEASURES | Summary aligned with this policy |
