# APPENDIX D: FORENSIC REPORTS

## Overview

This appendix catalogs forensic analysis reports documenting the technical evidence of the cyber intrusion, malware deployment, and trade secret theft. These reports support the criminal referral under 18 U.S.C. § 1831 (Economic Espionage) and 18 U.S.C. § 1030 (Computer Fraud and Abuse Act).

---

## Primary Forensic Reports

### A10: CHAIN_EeTUR Infrastructure Analysis

| Field | Value |
|-------|-------|
| **Title** | FORENSICS REPORT: Advanced Persistent Threat and Cryptocurrency Theft Operation |
| **Original Date** | June 12, 2025 |
| **Updated** | **January 31, 2026** |
| **Pages** | 91 (original) + 15 (update) |
| **Analyst** | Alistair Blackwood / Brian Spector |
| **Case Reference** | BL-2024-000648 |
| **Classification** | CONFIDENTIAL - JUDICIARY AND LAW ENFORCEMENT ONLY |

#### January 31, 2026 Update

The CHAIN_EeTUR report has been updated with additional findings. See:

```
EVIDENCE/UPDATE_FORENSIC_REPORT_JAN_31_2026_CHAIN_EeTUR.pdf
```

#### Executive Summary

The CHAIN_EeTUR report documents a sophisticated malware infrastructure serving dual purposes:

1. **Cryptocurrency theft** from Particle Ink NFT customers via MetaMask address swapping

2. **Surveillance and attack** operations against Brian Spector and Nicola McNamee

#### Key Technical Findings

| Finding | Details |
|---------|---------|
| **Malware Type** | Steganographic wallpaper malware |
| **Infection Vector** | Microsoft Teams links → JavaScript drive-by → PNG payload |
| **Persistence** | Apple zero-day wallpaper extension exploit |
| **C2 Infrastructure** | French server routing; SELECTEL (AS49505) Russian hosting |
| **Dormancy Period** | 5 days between infection and activation |
| **Payload Size** | 1.7MB obfuscated JavaScript (producer360.io) |

#### Attack Timeline

| Date | Event |
|------|-------|
| November 2023 | Brian Spector infected (wallpaper vector) |
| March 15, 2024 | Nicola McNamee targeted via Teams (Lilia Severina sender) |
| June 2025 | Malware discovered and analyzed |
| January 2026 | Infrastructure remains operational at particleink.com/nfthome |

#### Evidence Location

```
EVIDENCE/FORENSICS_REPORT_CHAIN_EeTUR_INFRASTRUCTURE.pdf
EVIDENCE/FORENSICS_REPORT_CHAIN_EeTUR_INFRASTRUCTURE.md
```

#### SHA-256 Hash

```
cd0c96e56f5a1d1ff6a5c9a00dcd470c8576f8439556aec9fe671c00f2644a00
```

---

### A10b: APT29 Attribution Analysis

| Field | Value |
|-------|-------|
| **Title** | APT29 Attribution Analysis |
| **Date** | January 24, 2026 |
| **Pages** | 21 |
| **Attribution Confidence** | 92.5% APT29/SVR |

#### Attribution Methodology

| Category | Score | Evidence |
|----------|-------|----------|
| Technical Signatures | 8/8 match | Infrastructure, TTPs, tooling |
| Infrastructure Correlation | HIGH | SELECTEL hosting, French routing |
| Operational Patterns | HIGH | 18-24 month campaign cycle |
| Targeting Alignment | HIGH | UK cryptography expert (MIRACL/GCHQ/USAF) |

#### Technical Signature Analysis

| APT29 Signature | Present | Evidence |
|-----------------|---------|----------|
| Steganographic payloads | ✔ | PNG wallpaper concealment |
| Multi-stage delivery | ✔ | Stager → obfuscated JS → payload |
| Zero-day exploitation | ✔ | Apple wallpaper extension |
| Long-term persistence | ✔ | 19+ months undetected |
| Eastern European infrastructure | ✔ | SELECTEL (Russia), French routing |
| Cryptocurrency targeting | ✔ | MetaMask address swapping |
| Legal sector compromise | ✔ | 6 UK law firms |
| Hybrid warfare elements | ✔ | Cyber + legal + psychological |

#### Statistical Analysis

| Metric | Value |
|--------|-------|
| **APT29 Signature Match** | 8 of 8 documented techniques |
| **Probability of Coincidence** | <0.001% |
| **Attribution Confidence** | 92.5% |

---

### A10c: Email Impersonation Forensic Analysis

| Field | Value |
|-------|-------|
| **Title** | Ali Reza Sinai Multi-Persona Identity Fraud Operation |
| **Date** | January 31, 2026 |
| **Analyst** | Alistair Blackwood / Rachel Chen |
| **Evidence Base** | 135+ emails, 17 forensic analysis reports |
| **Classification** | CONFIDENTIAL - LAW ENFORCEMENT ONLY |

#### Executive Summary

Comprehensive forensic analysis establishing **mathematical certainty** that Ali Reza Sinai (barrister, Selborne Chambers) impersonated real solicitors (Alex Harvey at Constantine Law, Harriet Hall at Taylor Hampton) by sending emails from their accounts to systematically sabotage civil litigation while distributing APT29-attributed malware.

#### Key Findings

| Finding | Evidence | Probability |
|---------|----------|-------------|
| **French Server Key Finding** | All personas route through Azure France Central | 1 in 100 million |
| **UK Infrastructure Correlation** | 109 shared Exclaimer instances | 1 in 1 billion |
| **John Hayes Conspiracy** | 61.8% of Alex Harvey emails via Constantine Mimecast | Coordinated |
| **Triple Malware Distribution** | Identical SHA256 hash across three personas | **Definitive** |
| **Combined Probability** | All evidence coincidental | **1 in 2.5 quintillion** |

#### Criminal Conspiracy Evidence

Analysis of 34 "Alex Harvey" emails proves coordinated operation:

- **John Hayes (Constantine Law):** 21 emails via Mimecast (61.8%)

- **Ali Reza Sinai:** 13 emails via Exclaimer/Azure (38.2%)

#### Evidence Location

```
APPENDIX_O_Email_Impersonation_Forensics.md
EVIDENCE/EMAIL_ANALYSIS/ (17 source reports)
```

#### Cross-Reference

This report connects directly to CHAIN_EeTUR infrastructure analysis:

- Same French Azure routing patterns

- Same steganographic malware payloads

- Same APT29/Cozy Bear attribution indicators

---

### A11: Dual-Purpose Malware Analysis

| Field | Value |
|-------|-------|
| **Title** | Dual-Purpose Malware Technical Analysis |
| **Focus** | Cryptocurrency theft + surveillance |

#### Cryptocurrency Theft Mechanism

| Component | Function |
|-----------|----------|
| **Address Swapping** | Replaces legitimate recipient addresses during transaction signing |
| **Target** | MetaMask browser extension users |
| **Trigger** | Transaction initiation events |
| **Exfiltration** | Funds redirected to attacker-controlled wallets |

#### Surveillance Capabilities

| Capability | Evidence |
|------------|----------|
| Screen capture | Confirmed via forensic analysis |
| Keylogging | Keyboard event interception |
| File access | Document exfiltration |
| Audio capture | Microphone access |
| Network monitoring | Traffic interception |

---

\newpage

## Supporting Forensic Evidence

### A1: APT29 Malware Forensic Analysis

| Field | Value |
|-------|-------|
| **Source** | Victim devices |
| **Status** | Available for production |
| **Content** | Complete malware samples and analysis |

### A2: Steganographic Wallpaper Samples

| Field | Value |
|-------|-------|
| **Source** | Forensic images |
| **Status** | Available |
| **Content** | PNG files containing concealed payloads |

### A3: Particle Ink Malware Loading Infrastructure

| Field | Value |
|-------|-------|
| **Source** | Archive.org (Wayback Machine) |
| **Status** | **STILL OPERATIONAL** |
| **URL** | particleink.com/nfthome |
| **Significance** | Active criminal infrastructure |

### A8: Firmware-Level Persistence Evidence

| Field | Value |
|-------|-------|
| **Source** | Recovery partition |
| **File** | arm64eBaseSystem.dmg |
| **Status** | Available |
| **Significance** | Deep system compromise |

### A12: MetaMask Address Swapping Code

| Field | Value |
|-------|-------|
| **Source** | Deobfuscated malware |
| **Status** | Available |
| **Content** | Cryptocurrency theft implementation |

### A13: Apple Zero-Day Wallpaper Extension Exploit

| Field | Value |
|-------|-------|
| **CVE** | Pending |
| **Source** | Forensic analysis |
| **Significance** | Nation-state grade exploitation |

### A14: box-office.js Stager Script

| Field | Value |
|-------|-------|
| **Source** | Forensic extraction |
| **Function** | Initial payload delivery |
| **Status** | Available |

### A15: producer360.io Payload

| Field | Value |
|-------|-------|
| **Size** | 1.7MB obfuscated JavaScript |
| **Source** | Forensic extraction |
| **Status** | Available |

---

\newpage

## Third-Party Validations

### E2: Computer Forensics Lab Expert Report

| Field | Value |
|-------|-------|
| **Expert** | Joseph Naghdi |
| **Organization** | Computer Forensics Lab |
| **Date** | November 15, 2024 |
| **Key Finding** | Ali Sinai coincidence probability: 1 in 2.5 quintillion |

#### Statistical Analysis of Ali Sinai Personas

| Factor | Probability |
|--------|-------------|
| Same infrastructure (Azure France Central) | <0.001% |
| Same email signature service (Exclaimer) | <0.01% |
| Same naming patterns | <0.1% |
| Simultaneous dual-side representation | <0.0001% |
| **Combined Probability** | **1 in 2.5 quintillion** |

---

\newpage

## Law Firm Malware Distribution

### Taylor Hampton Malware (May 19, 2025)

| Field | Value |
|-------|-------|
| **Vector** | "Form of Authority" PDF |
| **Sender** | Megan O'Boyle (Solicitor) |
| **Attribution** | APT29 shell code |
| **Evidence** | Malware analysis |

### Jonathan Hill Malware (May 29, 2025)

| Field | Value |
|-------|-------|
| **Vector** | Exhibit L2 PDF |
| **Sender** | Jonathan Hill (Barrister) |
| **Attribution** | APT29 shell code |
| **Evidence** | Malware comparison analysis |

---

\newpage

## Email Infrastructure Analysis

### A4-A6: Ali Sinai Persona Infrastructure

| Component | Finding |
|-----------|---------|
| **Email Headers** | Azure France Central routing |
| **Signature Service** | Exclaimer management |
| **Impersonated** | Alex Harvey (Constantine Law), Harriet Hall (Taylor Hampton) |
| **Significance** | Same operative on both sides of Spector's litigation |

---

## MITRE ATT&CK Mapping

| Tactic | Technique | Evidence |
|--------|-----------|----------|
| Initial Access | Phishing (T1566) | Teams messages with malicious links |
| Execution | User Execution (T1204) | Victim clicks on malware link |
| Persistence | Boot/Logon Scripts (T1037) | Wallpaper extension persistence |
| Defense Evasion | Steganography (T1027.003) | Payload concealed in PNG |
| Credential Access | Input Capture (T1056) | Keylogging |
| Collection | Screen Capture (T1113) | Documented capability |
| Exfiltration | Exfiltration Over C2 (T1041) | Encrypted C2 communications |

---

\newpage

## Evidence Preservation

### Chain of Custody

| Evidence | Custodian | Collection Date | Hash Verified |
|----------|-----------|-----------------|---------------|
| CHAIN_EeTUR Report | Brian Spector | June 12, 2025 | ✔ |
| Malware Samples | Brian Spector | June 2025 | ✔ |
| Email Headers | Brian Spector | Various 2025 | ✔ |
| Forensic Images | Brian Spector | June 2025 | ✔ |

### Evidence Production Availability

| Evidence Category | Format | Size | Production Ready |
|-------------------|--------|------|------------------|
| Forensic Reports | PDF/MD | ~100 pages | ✔ |
| Malware Samples | Binary | ~5MB | ✔ |
| Email Evidence | EML/Headers | ~50MB | ✔ |
| Forensic Images | DMG/IMG | ~200GB | Upon request |

---

\newpage

## Verification Statement

I, Brian Spector, declare under penalty of perjury under the laws of the United States (28 U.S.C. § 1746) that:

1. All forensic evidence described above is authentic and has been preserved with chain of custody

2. The forensic analysis was conducted using industry-standard methodologies

3. APT29 attribution confidence of 92.5% is based on 8/8 technical signature matches

4. All evidence is available for production to federal investigators upon request


**Brian Spector**
\vspace{2em}

**Signature:** ____________________________
\vspace{2em}

**Date:** February 3, 2026

---

## Evidence Cross-Reference

| Appendix | Related Content |
|----------|-----------------|
| APPENDIX_C | Access logs documenting intrusion |
| APPENDIX_G | Contractor exfiltration network |
| APPENDIX_I | Email compromise indicators |
| 08_EVIDENCE_INDEX | Complete evidence catalog |
| 06_FOREIGN_GOVERNMENT_NEXUS | APT29/Russia/UKMoD/IRGC attribution context |
