**Appendix C: Access Logs**

# APPENDIX C: ACCESS LOGS

## Overview

This appendix documents access logging and audit trail evidence demonstrating that Brian Spector and 2REAL maintained tracking systems for trade secret access. These logs support the "reasonable measures" requirement of 18 U.S.C. § 1839(3)(A) and provide forensic evidence of unauthorized access.

---

## 1. Version Control System Logs

### Git Repository Access

Brian Spector maintained private Git repositories with complete audit logging of all access and modifications.

#### Repository Access Summary

| Repository | Purpose | Access Control | Log Retention |
|------------|---------|----------------|---------------|
| `drey-finance` | Core protocol codebase | SSH key + 2FA | Complete history |
| `triple-b-protocol` | Bearer bond implementation | SSH key + 2FA | Complete history |
| `fairplay-game` | Game protocol | 2FA | Complete history |
| `2real-business` | Business documentation | 2FA | Complete history |
| `2real-business` | Software | 2FA | Complete history |

#### Commit History Statistics

| Repository | Total Commits | Contributors | Date Range |
|------------|---------------|--------------|------------|
| drey-finance | 847 | 3 | Jan 2023 - Apr 2024 |
| triple-b-protocol | 312 | 2 | Feb 2023 - Apr 2025 |
| fairplay-game-protocols | 156 | 2 | Feb 2024 - Nov 2024 |
| 2real-business | 1009 | 5 | Nov 2024 - present |

#### Access Logging Features

| Feature | Implementation |
|---------|----------------|
| Commit Attribution | All commits signed with verified identity |
| Push Logs | Complete record of all repository pushes |
| Clone Tracking | Logged via server-side hooks |

---

\newpage

## 2. Document Access Tracking

### Cloud Storage Access Logs

| Platform | Purpose | Access Logging | Evidence Ref |
|----------|---------|----------------|--------------|
| ProtonDrive | Secure document storage | Access timestamps | Cloud logs |
| SignNow | NDA execution | Signature tracking | SignNow audit |
| GitHub | Code repository | Complete commit history | Git logs |

### Document Distribution Tracking

| Document Type | Tracking Method | Recipients Logged |
|---------------|-----------------|-------------------|
| Technical Specifications | Watermarked PDFs | ✔ |
| Business Plans | Expiring links | ✔ |
| Legal Documents | Email records | ✔ |
| Source Code | Repository access | ✔ |

---

\newpage

## 3. Chain of Custody Manifests

### SHA-256 Hash Manifests

Brian Spector maintained cryptographic hash manifests for all evidence, enabling verification of integrity and tracking of access.

#### Manifest Summary

| Location ID | Files Processed | Manifest File | Date |
|-------------|-----------------|---------------|------|
| COURT_ORDERS_8AUG | 22 | SHA256_COURT_ORDERS_8AUG_20260124_225200.txt | Jan 24, 2026 |
| J_H_EML | 7 | SHA256_J_H_EML_20260124_225200.txt | Jan 24, 2026 |
| CCMC | 21,185,976 bytes | SHA256_LOCAL_CCMC_20260123_001420.txt | Jan 23, 2026 |
| CLOUD_FBI | 604,490 bytes | SHA256_LOCAL_CLOUD_FBI_20260123_001415.txt | Jan 23, 2026 |
| CHAIN_EeTUR | 165,952 bytes | SHA256_LOCAL_CHAIN_EeTUR_20260123_001405.txt | Jan 23, 2026 |

#### Evidence Location Index

| Location | Path | Manifest |
|----------|------|----------|
| PROJECT | /mnt/project/ | SHA256_PROJECT_20260122.txt |
| UPDATED_IC3 | ~/updated_ic3/ | User confirmed |
| ETHNIC_CLEANSING | ~/ETHNIC_CLEANSING/ | User confirmed |
| MALWARE_ANALYSIS | ~/malware-analysis/ | User confirmed |
| KENT_POLICE | ~/KENT_POLICE/ | User confirmed |

---

\newpage

## 4. Anomalous Access Events

### Detected Unauthorized Access

The following anomalous access events were detected, demonstrating both the existence of logging systems and evidence of unauthorized access:

#### March 31, 2025 — Email Account Compromise

| Event | Details |
|-------|---------|
| **Detection Method** | Google Password Manager breach alert |
| **Accounts Affected** | 23 accounts |
| **Evidence** | E4 — Google breach notification |
| **Attribution** | APT29/coordinated attack |

#### March 15, 2024 — Malware Transmission

| Event | Details |
|-------|---------|
| **Detection Method** | Teams message analysis (retrospective) |
| **Vector** | 3 Particle Ink links via Microsoft Teams |
| **Perpetrator** | Lilia Severina (APT29 operative), Cassandra Rosenthal |
| **Evidence** | D3 — Teams message logs |

#### November 2023 — Initial APT29 Infection

| Event | Details |
|-------|---------|
| **Detection Method** | Forensic analysis (June 2025) |
| **Vector** | Steganographic wallpaper malware |
| **Duration** | 19 months undetected |
| **Evidence** | A1, A2 — Forensic analysis reports |

---

\newpage

## 5. Access Control Verification

### Personnel Access Matrix

| Person | Role | Access Granted | Access Revoked | Status |
|--------|------|----------------|----------------|--------|
| Brian Spector | Technical Lead | Founding | N/A | Active |
| Nicola McNamee | CMO | Feb 2024 | N/A | Active |
| Pratheek Gupta | Snr Dev | Feb 2024 | Nov 2025 | **DEACTIVATED** |
| Lilia Severina | Co-founder (claimed) | Feb 2024 | April 19, 2024 | **REVOKED** |
| Victor Chombo | Contractor | April 2024 | June 2024 | **REVOKED** |

### Access Revocation Logs

| Date | Person | Systems Affected | Revocation Method |
|------|--------|------------------|-------------------|
| April 19, 2024 | Lilia Severina | All systems | Credential rotation, repository removal |
| June 2024 | Victor Chombo | Project repositories | Repository access removed |

---

\newpage

## 6. Third-Party Access Logs

### Legal Counsel Document Production

| Firm | Documents Provided | Date Range | Log Type |
|------|-------------------|------------|----------|
| Mishcon de Reya | Litigation files | 2024 | Email records |
| Gunnercooke LLP | Case materials | 2024-2025 | Email records |
| Portner Law | Court filings | Mar-May 2025 | Email records |
| Brown Rudnick LLP | Full case file | Jul 17-24, 2025 | Email records |

### Brown Rudnick Anomaly

| Date | Event | Evidence |
|------|-------|----------|
| July 21, 2025 | Documents returned with metadata stripped | Email comparison |
| July 24, 2025 | Firm withdrew representation | Email records |
| Post-withdrawal | Documents retained by firm | Absence of return confirmation |

---

\newpage

## 7. Forensic Access Analysis

### APT29 Surveillance Duration

Based on forensic analysis, the following unauthorized access timeline was reconstructed:

| Start Date | End Date | Duration | Systems Accessed |
|------------|----------|----------|------------------|
| Nov 2023 | June 2025 | 19 months | Brian Spector MacBook Pro and iPhone 13 |
| Mar 15, 2024 | June 2025 | 14 months | Nicola McNamee MacBook Pro and iPhone 13 |

### Data Exfiltration Indicators

| Indicator | Detection | Evidence |
|-----------|-----------|----------|
| Unusual outbound traffic | Forensic analysis | A10 — CHAIN_EeTUR report |
| Encrypted C2 communications | Network logs | Infrastructure analysis |
| File access timestamps | Filesystem forensics | Recovery partition analysis |
| Custom software | malware analysis | A10 — CHAIN_EeTUR report |

---

## 8. Hash Collision Analysis

### Critical Finding

Hash collision detected between evidence locations, indicating either:

1. Legitimate duplication of court materials, or

2. Evidence cross-contamination requiring investigation

| File 1 | Location | Hash |
|--------|----------|------|
| image001.jpg | J_H_EML | 21973cf4f713db2e1beb657daeb12a5d6f3a3888008b0b4cd0a5a44533823961 |

| File 2 | Location | Hash |
|--------|----------|------|
| Sealed Orders.jpg | COURT_ORDERS_8AUG | 21973cf4f713db2e1beb657daeb12a5d6f3a3888008b0b4cd0a5a44533823961 |

**Status:** Requires forensic binary comparison

---

\newpage

## 9. Evidence Preservation

### Chain of Custody Declaration Categories

| Category | Source | Method | Date Range |
|----------|--------|--------|------------|
| A: Court Communications | ProtonDrive exports | Digital preservation | Aug 2025 |
| B: Counsel Correspondence | Email archives | Email export | Jun 2024 - present |

### Preservation Compliance

| Requirement | Status |
|-------------|--------|
| Hash manifests generated | ✔ Complete |
| Evidence indexed | ✔ Complete |
| Chain of custody declarations | Pending signature |
| Backup verification | ✔ Complete |

---

## Verification Statement

I, Brian Spector, declare under penalty of perjury under the laws of the United States (28 U.S.C. § 1746) that:

1. Access logging systems were implemented as described above

2. The logs accurately reflect access to trade secret information

3. Anomalous access events were detected through these logging systems

4. All evidence is preserved with cryptographic hash verification


\vspace{2em}
**Brian Spector**
\vspace{2em}

**Signature:** ____________________________

**Date:** February 3, 2026

---

## Evidence Cross-Reference

| Appendix | Related Content |
|----------|-----------------|
| APPENDIX_A | Agreements governing access |
| APPENDIX_B | Policies enforced through logging |
| APPENDIX_D | Forensic reports detecting unauthorized access |
| 08_EVIDENCE_INDEX | Complete evidence catalog |
