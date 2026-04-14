**Appendix A: Confidentiality Agreements**

# APPENDIX A: CONFIDENTIALITY AGREEMENTS

## Overview

This appendix catalogs confidentiality agreements and non-disclosure agreements (NDAs) executed by Brian Spector, 2REAL LLC, and Fairplay Heroes in connection with the protected trade secrets. These agreements demonstrate compliance with the "reasonable measures" requirement of 18 U.S.C. § 1839(3)(A).

---

## Summary of Executed Agreements

| # | Agreement Type | Counterparty | Date | Status | Evidence Ref |
|---|----------------|--------------|------|--------|--------------|
| 1 | Mutual NDA | Technical Contributors | Various 2023-2024 | Executed | SignNow Archive |
| 2 | Mutual NDA | Business Development Partners | Various 2024 | Executed | SignNow Archive |
| 3 | Engagement Letter + NDA | Brown Rudnick LLP | July 17, 2025 | Executed (Breached) | A-BR-001 |
| 4 | Founder MOU w/ Confidentiality | Lilia Severina | February 2024 | Executed (Violated) | A-LS-001 |
| 5 | Contractor Agreement + NDA | Victor Chombo | April-June 2024 | Executed | A-VC-001 |
| 6 | Attorney-Client Privilege | All Legal Counsel | 2024-2025 | In Effect | Various |

---

## Category 1: Standard Mutual NDAs

### Description

Brian Spector and 2REAL utilized a standard mutual NDA template for all business engagements involving access to proprietary information. The template includes:

- Definition of "Confidential Information" covering technical specifications, source code, business plans, and financial information

- Mutual obligations of confidentiality

- Prohibition on disclosure to third parties without written consent

- Survival period of 5 years following disclosure

- Governing law and jurisdiction provisions

### Executed Agreements on File

**19 Mutual NDAs executed via SignNow**, covering:

| Category | Count | Purpose |
|----------|-------|---------|
| Technical Contributors | 8 | Development team, code reviewers |
| Business Development | 6 | Potential partners, investors |
| Consultants | 3 | Marketing, strategy advisors |
| Vendors | 2 | Infrastructure, tooling providers |

### Evidence Location

```
FBI_SUBMISSION/EVIDENCE_PACKAGE/02_PROTECTIVE_MEASURES/NDAs_executed/
├── SignNow_Downloaded_Docs_01_28_2026.zip (19 signed NDAs)
├── SignNow_Downloaded_Docs_01_28_2026 (1).zip
├── SignNow_Downloaded_Docs_01_28_2026 (2).zip
└── SignNow_Downloaded_Docs_01_28_2026 (3).zip
```

### SHA-256 Hash Verification

| File | SHA-256 |
|------|---------|
| SignNow_Downloaded_Docs_01_28_2026.zip | `98db43bd33ba54a34632df69ae29d23c5754ac8b9cbeb0ef86dd5d647f7c609a` |

---

\newpage

## Category 2: Brown Rudnick Engagement Letter (A-BR-001)

### Agreement Details

| Field | Value |
|-------|-------|
| **Document** | Engagement Letter |
| **Date** | July 17, 2025 |
| **Parties** | Brown Rudnick LLP ↔ Brian Spector & Nicola McNamee |
| **Retainer** | £100,000 GBP |
| **Duration** | 7 days (July 17-24, 2025) |

### Confidentiality Provisions

The Brown Rudnick engagement letter included standard solicitor-client confidentiality obligations including:

1. **Duty of Confidence** — All information provided by client is confidential

2. **No Third-Party Disclosure** — Without express written consent

3. **Document Retention** — Firm retains documents per professional standards

4. **Conflict Check** — Firm represents no conflicting parties

### Breach Documentation

Despite these obligations, Brown Rudnick:

| Date | Breach | Evidence |
|------|--------|----------|
| July 21, 2025 | Sent documents with metadata stripped (removing authorship) | Email records |
| July 24, 2025 | Abandoned representation without proper termination | Email records |
| Post-withdrawal | Retained access to produced documents | System logs |

### Evidence Location

```
FBI_SUBMISSION/EVIDENCE_PACKAGE/02_PROTECTIVE_MEASURES/NDAs_executed/
  └── 17 Jul 25 - Brown Rudnick Engagement Letter - Mr Brian Spector and Nicola McNamee.pdf
```

---

\newpage

## Category 3: Founder MOU — Lilia Severina (A-LS-001)

### Agreement Details

| Field | Value |
|-------|-------|
| **Document** | Memorandum of Understanding (Founder Agreement) |
| **Date** | February 2024 |
| **Parties** | Brian Spector / 2REAL ↔ Lilia Severina |
| **Scope** | Co-founder roles, equity split, IP ownership |

### Key Confidentiality Provisions

The Founder MOU included:

1. **Permanent Confidentiality Clause** — Obligations survive termination

2. **IP Assignment** — All developed IP belongs to 2REAL

3. **Non-Compete** — During and 12 months following termination

4. **Non-Solicitation** — Of employees, contractors, and clients

### Breach Documentation

Lilia Severina violated the MOU by:

| Date | Violation | Evidence |
|------|-----------|----------|
| March 15, 2024 | Transmitted malware to Nicola McNamee via Teams | Teams message logs |
| April 19, 2024 | Refused to return proprietary documents upon termination | Email correspondence |
| Post-termination | Continued representing herself as associated with IP | LinkedIn archives |
| 2024-2025 | Transferred trade secrets to Kaleidoco Inc. | Forensic evidence |

---

\newpage

## Category 4: Contractor Agreement — Victor Chombo (A-VC-001)

### Agreement Details

| Field | Value |
|-------|-------|
| **Document** | Contractor Services Agreement |
| **Date** | April-June 2024 |
| **Parties** | 2REAL ↔ Victor Chombo |
| **Scope** | Technical development services |

### Confidentiality Provisions

Standard contractor NDA terms including:

1. **Work Product Assignment** — All work product owned by 2REAL

2. **Confidential Information** — Defined to include all technical specifications

3. **Return of Materials** — Upon termination

### Consciousness of Guilt

Victor Chombo's Slack confession (June 10, 2024) demonstrates awareness of confidentiality obligations:

> [Spanish text acknowledging unauthorized disclosure]

**Evidence Reference:** D4 in Evidence Index

---

\newpage

## Category 5: Attorney-Client Privilege Agreements

### Overview

All legal counsel engaged by Brian Spector operated under attorney-client privilege, which constitutes an implicit confidentiality agreement under professional conduct rules.

### Firms Subject to Privilege

| Firm | Jurisdiction | Period | Status |
|------|--------------|--------|--------|
| Mishcon de Reya | UK | 2024 | Privilege compromised |
| Gunnercooke LLP | UK | 2024-2025 | Privilege compromised |
| Portner Law | UK | March-May 2025 | Privilege compromised |
| Taylor Hampton | UK | May 2025 | Privilege compromised (malware) |
| Brown Rudnick LLP | UK/US | July 2025 | Privilege compromised |
| Constantine Law | UK | Opposing counsel | N/A |

### Privilege Breach Documentation

Six UK law firms either:

1. Breached attorney-client privilege directly, or

2. Were compromised via malware distribution, or

3. Contained operatives working against client interests

**See:** APPENDIX_G (Contractor Exfiltration Network) for detailed breach analysis

---

\newpage

## Verification Statement

I, Brian Spector, declare under penalty of perjury under the laws of the United States (28 U.S.C. § 1746) that:

1. All confidentiality agreements described above are authentic

2. Digital copies are maintained with cryptographic hash verification

3. Original signed documents are available for production upon request

4. The agreements demonstrate "reasonable measures" to protect trade secrets as required by 18 U.S.C. § 1839(3)(A)

**Brian Spector**
\vspace{2em}

**Signature:** ____________________________
\vspace{2em}

**Date:** February 3, 2026

---

## Evidence Cross-Reference

| Appendix | Related Content |
|----------|-----------------|
| APPENDIX_B | Security policies referenced in agreements |
| APPENDIX_D | Forensic evidence of agreement breaches |
| APPENDIX_G | Contractor exfiltration network details |
| 04_PROTECTIVE_MEASURES | Summary of all protective measures |
