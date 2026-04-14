# CHAIN OF CUSTODY MANIFEST

## FBI Economic Espionage Act Victim Referral Package

**Claim No:** BL-2024-000648 (UK High Court)

**Package Version:** January 2026

**Manifest Generated:** 2026-01-29

---

## Purpose

This manifest provides cryptographic verification of all evidence files referenced in the FBI EEA Victim Referral Package. SHA-256 hashes enable verification that evidence has not been tampered with after initial collection.

---

## Critical Court Documents

| File | SHA-256 Hash | Description |
|------|--------------|-------------|
| `BL-2024-000648 - Spector v Severina 2.pdf` | `9f8d134410aa81df4d4016e9823c68872389ab8f6616b33da31d7eaeb217aadd` | Order WITH Schedule A (received via email, 4 pages) |
| `BL-2024-000648 - Sealed Order dated 19 August 2025_from-ce-file.pdf` | `2b3b30d67a6af95f3f844eb2c1118d740c8b90864aae572939b9de834caf6743` | Order WITHOUT Schedule A (from CE-FILE, 3 pages) |
| `Spector v Severina - HCJ (ChD) - Judgment - 20250808 V Final copy.pdf` | `e2e036a96c6fd00fa4024b44df794f87e92b81288f384e22e28699c10fd5ab7e` | Deputy Master Dray's Judgment (August 8, 2025) |
| `Spector v Severina - HCJ (ChD) - Procs excl judgment - 20250808.md` | `a1bf9f9d24edeb417e05f13489e88eeef5685c111fd956aa03e103fcdf22bb34` | August 8, 2025 Hearing Transcript (Markdown) |

---

## Forensic Analysis Documents

| File | SHA-256 Hash | Description |
|------|--------------|-------------|
| `BS4-9_METADATA_FINDINGS_Spector_v_Severina_20250623_032322.pdf` | `47fb4068cda540ec65ceabef7f05e396d16b9c39402c667bf1cfdc17534d1d4d` | N434 Metadata Findings — batch creation June 13, 2025 |
| `BS4-12_TECHNICAL_NOTE_Spector_v_Severina_20250623_034447.pdf` | `3bd477ab2b882dc011ac2dac228fd9869aefbc6a605e8eff3d133412ce33cd32` | CE-FILE OCR Poisoning Technical Analysis |
| `apt29_attribution_and_methods_v2.md` | `58e8a83e121d65b1a536638b00eb419917f1ae9f543d98b30730a36336a0cbd8` | APT29 Attribution and Methods Analysis |

---

## Defendant's Evidence (Contains Fraud)

| File | SHA-256 Hash | Description |
|------|--------------|-------------|
| `2025_06_13 John Hayes Second Witness Statement (signed).pdf` | `7abc0d287ade92670cf6629b4f6f0db426c54472f5216a46926860fd50513cdd` | JH2 — Contains malformed N434 PDFs and 189-modification transcript |

---

## Contractor Exfiltration Evidence

| File | SHA-256 Hash | Description |
|------|--------------|-------------|
| `Kyle the Airtuber.eml` | `09702d11bae804c39147bba47f2b39dcfd52e724196aa06b78c0885a6a53ded3` | Victor Chombo's Patreon announcement (June 2025) |
| `Lilia Severina shared "Story and Characters Attempt 2" with you.eml` | `a081afb6c661218ce1963d27707dc2642b1226acc6aa66ec76b0bf59e00ba2a7` | Lilia's children's book development (March 2024) |

---

## Screenshot Evidence

| File | SHA-256 Hash | Description |
|------|--------------|-------------|
| `SCREENSHOTS/DRAFTABLE_DUAL_USE_MISSING.png` | `0a6f71debe1abb0ad06fd8d1ee4a6a21cfc693f4c25e5031e9c1231f62a75bc8` | Draftable comparison showing "Dual Use" removal |
| `SCREENSHOTS/DELETED_DUAL_USE_EDGE_NEBULA.png` | `34b19f91726a6ce390b124b633deca46b73fd05b0dcc3b3960e4ac65617ab236` | EdgeNebula Ltd Dual Use designation removed |
| `SCREENSHOTS/CE-FILE_29_JAN_2026_MISSING_LINK.png` | `abb8f793ef1c9d99f1fac3e2d72915e45d85a6dd88b1853874f33a5463f7a80e` | CE-FILE showing missing judgment links |
| `SCREENSHOTS/CE-FILE_29_JAN_2026_MISSING_LINK_CLOSE_UP.png` | `df42e429c6a894cea8ca4bfbb840bb12e8ddddbf193937312928d6af20c7dd61` | CE-FILE missing links close-up detail |
| `SCREENSHOTS/screencapture-worldbranddesign-drey-finance-brand-identity-2026-01-27-15_43_38.png` | `8811714324cfeac15587dcb5bb0e08a0d918bd7dcd83748e718596e0acb8712c` | WBDS Award for Nicola McNamee (June 29, 2023) |

---

## Verification Instructions

To verify file integrity:

```bash
# Single file verification
sha256sum "filename.pdf"

# Compare against manifest hash
# If output matches manifest, file has not been modified
```

---

## Evidence Collection Notes

### Collection Environment

- **Custody Holder:** Brian Spector

- **Primary Storage:** Secured local systems with encryption at rest

- **Backup:** Cloud backup with version history enabled

### Collection Methodology

1. **Court Documents:** Downloaded directly from CE-FILE or received via official court email

2. **Screenshots:** Captured using macOS built-in screenshot utility (timestamp metadata preserved)

3. **Email Evidence:** Preserved as .eml files with full headers intact

4. **Forensic Documents:** Generated using documented analysis tools with methodology notes

### Chain of Custody Log

| Date | Action | Actor | Notes |
|------|--------|-------|-------|
| 2024-2025 | Original collection | Brian Spector | Various dates per document type |
| 2026-01-29 | Manifest generation | Claude (AI Assistant) | SHA-256 hashes computed |
| — | Submission to FBI | [Pending] | — |

---

## Evidence Count Summary

| Category | Count |
|----------|-------|
| Court Documents | 4 |
| Forensic Analysis | 3 |
| Defendant Evidence | 1 |
| Contractor Evidence | 2 |
| Screenshots | 5 |
| **Total Hashed** | **15** |

**Total Evidence Files in Repository:** 9,983 files

---

## Additional Resources

For complete evidence, the following directories contain supplementary materials:

- `EVIDENCE/SCREENSHOTS/` — Visual evidence and screen captures

- `EVIDENCE/EVIDENCE_LAW360_LEXISNEXIS/` — Press coverage and media manipulation

- `EVIDENCE/ARGENTINA/` — Contractor exfiltration evidence

- `EVIDENCE/NIC_TIMELINE/` — Timeline establishing Nicola McNamee's prior work

---

*This manifest is provided as part of the FBI EEA Victim Referral Package and should be retained with all evidence submissions.*
