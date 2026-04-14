**Chapter 8: Evidence Index**

\vspace{-2em}
# EVIDENCE INDEX {#sec-evidence-index}
\vspace{-0.5em}

## EVIDENCE ARSENAL — 91+ EXHIBITS

*Forensically Preserved • Hash-Verified*

### Evidence Categories Overview

| **Category** | **Count** | **Type** | **Examples** |
|--------------|-----------|----------|--------------|
| **A: FORENSIC** | 20 items | APT29 malware | Wayback proof |
| **B: COURT** | 12 items | Injunctions | CE-FILE tamper, TWO-PHASE FRAUD |
| **C: CORPORATE** | 7 items | Nevada filings | £100K invoices |
| **D: COMMS** | 7 items | Teams attack | Confessions |
| **E: THIRD-PARTY** | 4 items | Uber confirm | Google breach |
| **F: INTEL** | 4 items | OTSI report | 92.5% APT29 |
| **G: FBI IC3** | 4 items | Kaleidoco | IRGC |
| **H: POLICE** | 3 items | Kent Police | False arrest |
| **I: PATENT/IP** | 6 items | Triple-B spec, Spector's provisional patent, Kaleidoco patent | Brian Spector.pdf |
| **J: SOCIAL** | 23 items | Wayback Oct 2022 | **KEY FINDING:** Severina scrubbed Kaleidoco LinkedIn profile 14 MONTHS before infiltrating victim |

═════════════════════════════════════════════════════════════════
      ALL EVIDENCE AVAILABLE FOR IMMEDIATE PRODUCTION
═════════════════════════════════════════════════════════════════

## Evidence Categories

This index catalogs evidence supporting the Economic Espionage Act referral, organized by category and availability.

---

## Category A: Forensic/Technical Evidence

| # | Description | Hash/ID | Location | Status |
|---|-------------|---------|----------|--------|
| A1 | APT29 malware forensic analysis | — | — | *See A10 (106-page report)* |
| A2 | Steganographic wallpaper samples | `9922c25489d659d425e800f2f517991eb6d0f3b5ac886bcd39e3d822c8161da4` (base PNG) | CCMC/APPLE_SECURITY/CORE_EVIDENCE | **10 UNIQUE SAMPLES** |
| A3 | Particle Ink malware loading infrastructure | Wayback Machine | Archive.org | **STILL OPERATIONAL** |
| A4 | Email header forensics (Sinai personas) | `df15476f4f9862efbc468540fa3d2ca3642ec71b4722bedf874e47309e097ffd` | EMAIL_ANALYSIS/ | Available |
| A5 | Azure France Central routing evidence | `ddd03efb15293c4027924261a1fa57d6c87a30665a21faa8ba8caf09c95036f5` | EMAIL_ANALYSIS/ | Available |
| A6 | Exclaimer signature infrastructure | `07561c69d69d1893656ecb7e91e9bcad25f489ec37c747c0b86bfb3b200c5166` | EMAIL_ANALYSIS/ | Available |
| A7 | PDF metadata comparison (CE-FILE) | 9f8d1344 / c3dd4b55 | Court documents | Available |
| A8 | Firmware-level persistence evidence | `d49a3c6b1b0b1512d4e23a05957cfc3019039d3fedd729cfe43f9e16b40c32d8` | Recovery partition | Available |
| A9 | **EXHIBIT 9: Malware Executive Summary** | `7fbe455092c5563e57c89323949acaa7c9bb1af3ba754870023b1f1a94f6ff1e` | Court exhibit | Available |
| A10 | **CHAIN_EeTUR Forensics Report (106 pages)** | `cd0c96e56f5a1d1ff6a5c9a00dcd470c8576f8439556aec9fe671c00f2644a00` | APPENDIX_D_Forensic_Reports/ | **INCLUDED** |
| A10-U | **CHAIN_EeTUR Update (Jan 31, 2026)** | `339de6d7dbe869b1ffaacb8b4214eb2130c2e2bc3ad104f49dc4bfdb517ace3e` | EVIDENCE/ | **INCLUDED** |
| A10-V | **CHAIN_EeTUR Visual Summary** | `e30a740e144065278b014c1586709d9446c8c5b40a12fb42b9f2f8ed2f6206b0` | UPDATE_FORENSIC_REPORT/ | **INCLUDED** |
| A10b | **APT29 Attribution Analysis (21 pages)** | `d03281b745f3adb439171c303ba3ee071798f1cb35deeeeb9187a148206cf0fb` | APPENDIX_D_Forensic_Reports/ | **INCLUDED** |
| A13 | Apple zero-day wallpaper extension exploit | CVE pending | Forensic analysis | Available |
| A14 | box-office.js stager script v3.6.404 | `2dbe4fc38dae62af076f0bda9eb5cd776a8ae662ff8cf9d421672eb5799ff856` | Forensic extraction | **VERSION EVOLUTION DOCUMENTED** |
| A14b | box-office.js stager script v3.6.445 | `cbbb7b1120021d942f277d703e0341a92d3c357eb99b8fabf51a3958fc31ca68` | Live server Jan 2026 | **KILL SWITCH ACTIVATED** |
| A15 | producer360.io payload v3.6.404 (1.66MB) | `605f0cec582fec98396ef90d6b898d4e40540af7dbfbb8e3eb88dba5b9d10390` | Forensic extraction | Available |
| A15b | w2-prod.onrender.com C2 payload (16.87KB) | `99d453dd308e9bb16060bb87dc8a98ccb51f25a4d7778ae5d26d4cca05298643` | VirusTotal (July 4, 2025) | **NEW C2 ENDPOINT** |
| A18 | **box-office.js Version Comparison Forensics** | `e772daf2fd7f4fc39252ef92178889b60ac718af99442e5548fbe81309b8c19f` | Blackwood Ops Analysis | **KILL SWITCH DOCUMENTED** |
| A16 | **SELECTEL Network Traffic Capture (PCAP)** | `bf81ea0e6df0ec3311bb847ea1dca8db879a0b159a636e195b7f718016d9e526` | May 17, 2025 22:22:59 | **IMMUTABLE** |
| A17 | **Consolidated Email Impersonation Forensic Report** | `514a5357bb6ee99247fcabf25840210945c586e1d425cb72d5e32e98bbf48f1a` | APPENDIX O | **INCLUDED** |

### Key Forensic Finding: Email Impersonation Infrastructure (A17)

**Key Finding:** 109 email instances across 14 analytical parts prove Ali Sinai impersonated real solicitors (Alex Harvey, Harriet Hall) by sending emails from their accounts on BOTH sides of litigation using shared infrastructure.

| Evidence Type | Finding | Probability |
|---------------|---------|-------------|
| **Infrastructure Correlation** | Same Mimecast/Exclaimer signatures across personas | 1 in 2.5 quintillion |
| **Azure France Central** | Common routing for all personas | Wire fraud jurisdiction |
| **61.8% Mimecast Ratio** | Constantine Law emails via John Hayes infrastructure | Coordinated operation |

**See APPENDIX O for complete 14-part forensic analysis.**

### Key Forensic Finding: Dual-Purpose Malware

Brian Spector reverse-engineered the malware and discovered it served **two purposes**:

| Purpose | Description |
|---------|-------------|
| **Primary** | Cryptocurrency theft from Particle Ink NFT customers via MetaMask address swapping |
| **Secondary** | Surveillance and attack against Spector and Nicola |

#### Technical Details

- Address swapping during transaction signing (replaces legitimate recipient addresses with attacker-controlled)

- Zero-day Apple wallpaper extension vulnerability for persistence

- 5-day dormancy period between infection and activation

- Multi-stage payload: stager → obfuscated JS → steganographic PNG

- Russian APT methodology; Eastern European bulletproof hosting

- **STILL OPERATIONAL** at https://web.archive.org/web/20240301010203/https://www.particleink.com/nfthome#expand

### Key Forensic Finding: Live SELECTEL Traffic Capture (A16)

**Key Finding:** Live packet capture showing malware command-and-control traffic to SELECTEL (AS49505), a known Russian intelligence hosting provider.

| Field | Value |
|-------|-------|
| **Capture Date** | May 17, 2025 at 22:22:59 |
| **Destination** | SELECTEL infrastructure (St. Petersburg/Moscow) |
| **SHA-256** | `bf81ea0e...16d9e526` |
| **Status** | Hash-verified, immutable flag set |
| **Significance** | Direct network evidence of Russia nexus |

This PCAP provides irrefutable network-layer evidence that the malware was communicating with Russian infrastructure, corroborating the 92.5% APT29 attribution confidence.

### APT29 Attribution Evidence Summary (A10b)

**Attribution Confidence:** 92.5% APT29/SVR (Russian Foreign Intelligence Service)

#### Technical Signature Analysis

- **8/8 attack vectors** match documented APT29 techniques exactly

- **Statistical probability of coincidence:** <0.001%

- **Infrastructure correlation:** SELECTEL (AS49505) Russian hosting provider

- **Operational timeline:** 18-24 month campaign cycle (standard APT29)

#### Key Forensic Findings from CHAIN_EeTUR Report (A10)

- **Infection Timeline:** Spector (Nov 2023), Nicola (March 15, 2024)

- **Attack Vector:** Microsoft Teams → JavaScript drive-by → steganographic wallpaper

- **Persistence Duration:** 17+ months surveillance (Spector), 14+ months (Nicola)

- **Evidence Preserved:** 26 distinct malware payload variants with chain of custody

- **Technical Sophistication:** Nation-state grade steganographic concealment

#### Strategic Assessment

- Classic Russian hybrid warfare implementation combining cyber, legal, and psychological operations

- Targeting UK cryptography capabilities (MIRACL/GCHQ/USAF background) consistent with SVR priorities

- First documented foreign intelligence attack on UK judicial infrastructure

---

## Category B: Court Documents

| # | Description | Hash/ID | Date | Status |
|---|----------|-------------------|------|--------|
| B1 | Claim form BL-2024-000648 | `f24c4e318549e341ba4c85006bd921a09b2070cbf90610d599c2c5a38f88583f` | Apr 24, 2024 | Filed |
| B2 | Interim injunction (Roth J) | `28dc4ae3e508f88c5b03dafcd96e5d4ba47ec51da6e93e8f274e9d52f653d252` | Apr 29, 2024 | Granted |
| B3 | Interim injunction (Mann J) | `7eaeaea52692b2b04d821d522de6d56cdd5f60d09c8c4a95a12b64c70a55d072` | May 7, 2024 | Reaffirmed |
| B4 | Final Order (email version w/ Schedule A, 4 pages) | `9f8d134410aa81df4d4016e9823c68872389ab8f6616b33da31d7eaeb217aadd` | Sep 2, 2025 | Accompanies Referral |
| B5 | Final Order (CE-FILE version w/o Schedule A) | `c3dd4b55af11e75bced9f9fd143e62878bcca92ff038b554ae2f32ace466834a` | Sep 3, 2025 | **TAMPERED** Accompanies Referral |
| B6 | Court transcript (Aug 8, 2025) | `75d6691ff555ee5b918928a0e0773e6ac92e8c1f6ca4cc53d5f9e044b0a5ac34` | Aug 2025 | Contains fabricated dialogue |
| B7 | Defendant's Skeleton Argument | `046efc1a381ec16c136c8f5bc169de051381df8ce5efc33ab0f67821b1049e8b` | Mar 25, 2025 | Lists Rosenthal as witness |
| B8 | Defendant's DRD (target list) | `3fde227d0b24ca9cfcf8a0deae83d518d429dffd0436027f7ec467ca9233be86` | Mar 25, 2025 | Lists all victim emails |
| B9 | MG4F Refused Charge document | `9778dc57f9202c26e673a3d57d8caf00ac87790ac18075eb2ea34ea228e831c8` | Dec 19, 2025 | All charges refused |
| B10 | **Exhibit BS3/6: CE-FILE Judgment Metadata** | `c188945b0e57faddf39578c66562b500429cd292177b1284274a0d4a136b9138` | 30 May 2025 | **PHASE 1 FRAUD** |
| B11 | **Exhibit BS8-4: Transcript Impact Analysis** | `d788af77b67f644404b24584d7dc24dde7912da11fff57ec26e9d90b5810b4ed` | 13 Jun 2025 | **PHASE 2 FRAUD** |
| B12 | **eScribers Official Transcript (pp. 51-66)** | `80e0fe3a7325b8326c83d2e6d8dac67636d79c8368a41d822fa189de16dde0e3` | 8 Aug 2025 | **FRAUD ARGUED IN COURT** |

### Key Finding: Two-Phase Criminal Document Fraud (B10-B12)

**Key Finding:** Evidence of coordinated two-phase criminal document fabrication scheme:

| Phase | Date | Document | Key Evidence |
|-------|------|----------|--------------|
| **Phase 1** | 30 May 2025 | CE-FILE Word Documents | Created 64 days AFTER hearing; Creator: CULLEN, Samina; Modified: Martin Dray; 145 revisions |
| **Phase 2** | 13 June 2025 | JH2 Altered Transcript | 189 modifications; "has NOT received" → "has received"; Fake attribution: Acolad UK Ltd |

**The Forensic Trap:** Phase 1 proves CAPABILITY (Word documents enable editing). Phase 2 proves MOTIVE (189 changes all prejudice claimant).

**Court Confrontation:** Spector argued this fraud directly with Deputy Master Dray on August 8, 2025 (eScribers transcript pages 51-66). The Master acknowledged the "not" was missing but called Spector's example "pretty pathetic."

> "Sir, there is 157 different types of these changes that are **surgically done to prejudice my position and benefit the defendant**, all of them, every one." — Brian Spector, Court transcript pp. 51-57

---

## Category C: Corporate Records

| # | Description | Source | Date | Status |
|---|-------------|--------|------|--------|
| C1 | Kaleidoco Inc. Nevada registration | NV SOS | — | Public Record - Not Obtained |
| C2 | Particle Ink corporate records | — | — | Public Record - Not Obtained |
| C3 | Constantine Law filings | Companies House | — | Public Record - Not Obtained |
| C4 | EDGENEBULA LTD (15720185) | Companies House | — | Public Record - Not Obtained |
| C5 | Brown Rudnick engagement letter (v1) | `261ce7d1fb944b43b963e4f7f15177ea0e4ff2aef44e68982c81c038fd89eb21` | Jul 17, 2025 | Available |
| C5b | Brown Rudnick engagement letter (v2) | `45221d0eafea9d9879ee339e4f63bdd9d3dda25c2fdb434250ae52b3e9e78438` | Jul 17, 2025 | Available |
| C5c | Brown Rudnick termination letter | `a9adccb64e9b53fe718fea7317cb9b35d44e2d33fa8a19f8e2f3aa66eb730003` | Jul 24, 2025 | **7 DAYS** |
| C6 | Brown Rudnick invoice (Project Ghost) | `5965d836bbc559ba2cc62a837710e3da8320ecb9939ce4c89434f644c3cd5772` | Jul 23, 2025 | £100,000 total |
| C7 | Mishcon de Reya Invoice #5300029 | `e9d1a1c12859a1d8c3723b23f64ca596455e01bbc7d6bf7f700e27081a6ebafe` | Apr 22, 2025 | Marcus King £464 |

---

## Category D: Communications Evidence

| # | Description | Hash | Date | Status |
|---|-------------|------------|------|--------|
| D1 | Sealed Orders.eml (Alex Harvey) | `5e3f73699908c7276901ae353fb22be07037701bbda91f9b22f4c707df086362` | Aug 19, 2025 | Available |
| D2 | Severina termination email | `2f7062268b6e3790595582209cd9f709fd15b460676fe3a4564cd22e900cca73` | Apr 19, 2024 | Available |
| D3 | Teams messages (March 15 attack) | `b0f1d4d3a76e154359d662ca429328d66becedadf3c3b06679329f7e313f8ec1` | Mar 15, 2024 | 3 particleink links |
| D3b | Severina sends Nicola PI links | `4c5ad586713139f04297f798b18646a9bac0382826a1637a86226c3e2e1fd314` | Mar 15, 2024 | Screenshot |
| D3c | Severina asks for call | `4d2f2f287b71339d57166b1369b7e0092d2d4e59e4f8ed509f2d3cf43d16d2eb` | Mar 15, 2024 | Screenshot |
| D5 | "Joe Cervino" intimidation emails | `d7bbca63348aad367459688b119ff3502c5ddcd801197f06745d7c49eca659db` | Mar 5-10, 2025 | Amazon EC2 infrastructure |
| D7 | Hayes email to startup domain | `ed946323574644d308f7d71763e3f327b11a6f56345d99152e8a41d1d9807f6b` | Jul 10, 2024 | Pre-coordination proof |
| D7b | Constantine Law Invoice 7712 | `32df08a650b63900b6807d3a5e7c7d6d73f6664bdc2664fbc1d598a9106f10d4` | Jun 18, 2024 | Billing evidence |
| D7c | Constantine Law WIP SEV_1_1 | `bc1708a0c644ed16f7e09176cecf0473548ebfc2379e0cabed55c167c6b2c0d1` | Jul 5, 2024 | Work-in-progress |
| D7d | Constantine Law Invoice INVGES52 | `d038b71ec371c6a7ac95af3534a6dc7d4f3a6e789fd95ac0c4149317b8e1bc64` | Jul 10, 2024 | Billing evidence |

---

## Category E: Third-Party Validations

| # | Description | Source | Hash | Date | Status |
|---|-------------|--------|------------|------|--------|
| E1 | Uber "unauthorized recording" acknowledgment | Uber Technologies | `911b696c88b4d34d0444c68fb8f2606fc66e10a5ba89f075ed5eca08ca1b5f31` | Oct 2025 | IRGC_UBER_INCIDENT (15 files) |
| E2 | Computer Forensics Lab expert report | Joseph Naghdi | `be6bc0bf63a3b8949ea16814d30c7b6ea45bd6353489fb5cc072fc0dc7e56c24` | Nov 15, 2024 | 1 in 2.5 quintillion |
| E4 | Google Password Manager breach alert | Google | `e8545f775c85ad4113884492a0c587bf030f031c1f21c95f732210638b695e3e` | Mar 30, 2025 | 23 accounts compromised |
| E4b | Google breach alert (2nd screenshot) | Google | `bad24485520cfdd05db435f48d8c42ee918158fa88f8185bc65c25289edbe468` | Mar 30, 2025 | Account compromise |

---

## Category F: Intelligence/Sanctions Reports

| # | Description | Reference | Date | Status |
|---|-------------|-----------|------|--------|
| F1 | OTSI Sanctions Report | 4F0FA4 | Feb 23, 2025 | Filed |
| F2 | APT29 Attribution Analysis | Internal | Jan 24, 2026 | 92.5% confidence |
| F3 | Moscow conference documentation | `c58681b89806c9747345f4e264c32143dcbe6ee7e1d5a8a7b374fe1f396a9327` | May/Sept 2025 | Severina attendance |
| F3b | Moscow Annual Forum screenshot | `f0b0a6df9f5ca8630d605999c3ea0ee7182eb2748c5b7d4ab79ba80d0d974ca0` | Sept 2025 | Severina attendance |

---

## Category G: FBI IC3 Complaints

| # | Complaint ID | Date | Primary Subject |
|---|--------------|------|-----------------|
| G1 | 541e1fc82cd94884b9466da4ec11ae9f | Jun 3, 2025 | Kaleidoco malware |
| G2 | a67790ca490a489cbfb26816ace1548b | Jan 15, 2026 | IRGC surveillance |
| G3 | 3970dd925b284392aafafa57ac6e33e2 | Jan 16, 2026 | Marcus King fraud |
| G4 | 67a4bbc94b464c6ca48b6edfbefa57e1 | Jan 24, 2026 | Mishcon consciousness of guilt |

---

## Category H: Police Reports

| # | Reference | Agency | Date | Status |
|---|-----------|--------|------|--------|
| H1 | CAD-08-0678 | Kent Police | Jun 8, 2025 | Initial report |
| H2 | BS5-1 to BS5-5 exhibits | Kent Police | Jun 27, 2025 | Witness intimidation |
| H3 | 46XA/6148/25 | Kent Police | Dec 2, 2025 | False arrest custody ref |

---

## Category I: Patent/IP Documentation

| # | Description | Hash | Status |
|---|-------------|-------------|--------|
| I1 | Triple-B Protocol Technical Spec v2.0 | `785f35ac493b0cf37dffa9fc3471e06b87faf5719eda0697a36a29132c90d45a` | Trade secret |
| I2 | Provisional Patent Application (53 pages) | `471ea6dc868890bf7a42782cbe12eb66df5f53e87e482c6324c32853e0b52dff` | Filed |
| I3 | Fair Play Game Protocol (DRAFT-V3) | `59c677969fd343ddbe46a3ac3b28d0e57eaa1fc21374fa8f57b26b7a554c460b` | Trade secret |
| I4 | Character design documentation | `a081afb6c661218ce1963d27707dc2642b1226acc6aa66ec76b0bf59e00ba2a7` | Stolen and IP Poisoned |
| I5 | GitHub commits (DREY Finance) | Jan 2023 | Ownership proof |
| I6 | **Dual Reality (2REALITY) — Advances Gaming** | 2024 | Trade secret |

### Key Finding: Dual Reality (2REALITY) Technology (I6-I8)

**The Entertainment Innovation** that makes the Official Bitcoin Game Show commercially viable:

| Component | Description | Evidence |
|-----------|-------------|----------|
| **WebRTC Dual Streaming** | Low-latency dual reality streams | I6: Technical specification |
| **ML Transformation** | Real-time comedic animation pipeline | I6: AI-driven animation |
| **Dual Reality Engine** | Every action = two interpretations | I7: Computer Code |
| **AXEL Dual Behavior** | AI host operates differently per reality | I7: Computer Code |

**Format Design:** Players compete seriously while viewers see Monty Python-style absurdist spectacle. The disconnect between realities creates viral, shareable content.

---

## Category J: LinkedIn/Social Media Archives

| # | Description | Hash | Date | Status |
|---|-------------|------------|------|--------|
| J1 | Severina Kaleidoco "Blockchain Advisor" | `46c5d7e2782ec6295099593b6ee8077f91257a08dce80163d3eecf9051e750a4` | **Oct 2, 2022** | **PRESERVED** (20221002200427) |
| J2 | Kaleidoco CEO "See you in Vegas Severina!" | `7ba289e3e0ac38704ad8bb1a0fc43503a41d8527b2c89b29e3f0ba427be82c70` | Apr 20, 2024 | Archived |
| J3 | Moscow Datacenter conference (Severina) | `c58681b89806c9747345f4e264c32143dcbe6ee7e1d5a8a7b374fe1f396a9327` | Sept 2025 | **SCRUBBED** |
| J3b | Moscow Annual Forum (Severina) | `f0b0a6df9f5ca8630d605999c3ea0ee7182eb2748c5b7d4ab79ba80d0d974ca0` | Sept 2025 | **SCRUBBED** |
| J4 | Adrian Whant LinkedIn (IP references) | `a84b9d7c3fef9e71ec29dc663845bd7667017b6f5c382c688e71088e604b48e5` | Dec 2024 | Removal demanded |
| J5 | **Slack: Lucia Received OBGS/Axel Files** | `ba56d14cbee41263642a67c467e97f904152f0d7b79d8bf10e369b5924f41253` | Jul 19-30, 2024 | **Key Evidence** |
| J6 | **Draftable: Dual-Use Export Reference REMOVED** | `0a6f71debe1abb0ad06fd8d1ee4a6a21cfc693f4c25e5031e9c1231f62a75bc8` | Feb 2025 | **Key Evidence** |
| J7 | **CE-FILE: Sinai's Sanitized APOC Submitted** | `b081fb53abd2a5caba86d1bc2b6340cf4404bd0557f0bc97c31dd9dfaa92b44e` | Feb 21, 2025 | Gunnercooke filing |
| J8 | **Diff: EdgeNebula + Dual-Use BOTH Removed** | `34b19f91726a6ce390b124b633deca46b73fd05b0dcc3b3960e4ac65617ab236` | Feb 2025 | **Key Evidence** |
| J9 | **CE-FILE: APOC Download Link MISSING** | `abb8f793ef1c9d99f1fac3e2d72915e45d85a6dd88b1853874f33a5463f7a80e` | Jan 29, 2026 | **CONSCIOUSNESS OF GUILT** |
| J10 | **CE-FILE Close-Up: Download Icon Comparison** | `df42e429c6a894cea8ca4bfbb840bb12e8ddddbf193937312928d6af20c7dd61` | Jan 29, 2026 | **FIGURE EVIDENCE** |
| J11 | **Cassandra F.A.M. Discord Announcement** | `b0db2731a188bb5e648b767e2352caedceadf3f96b50db3a65f9d201ef1be056` | Jan 18, 2025 | **Key Evidence** |
| J12 | **Discord Server DESTROYED (New Launch)** | `eeba00a7fcbd87eabeba374b8de6f3625cd3df6dffb3fa185363e69cb1dfb71a` | Sept 16, 2025 | **CONSCIOUSNESS OF GUILT** |
| J13 | **Discord Bot Analysis** | `65ef31bc3714cbc846156b5da6661c3f7dc7707cf0fc29e625217d29362b4d60` | Apr 5, 2025 | Fake community evidence |
| J14 | **Adrian myoutlet.ai Wayback** | `3a58d3f4cb25052c49592e367f9f3b04232d4c0bb4104a40aa5dbca6484c0475` | Apr 2025 | Before scrubbing |
| J16 | **Adrian Digital Hollywood** | `46f7336c6996e0534fb7521a9c14ae34a7725859c1ce828ee2402a3325e8760f` | 2024-2025 | Before scrubbing |
| J17 | **Adrian LinkedIn SCRUBBED** | `8761ce39040e68aef0a1c0a1d4965487515bad3221ba5e8e27b35727c32d9a02` | Late 2025 | **CONSCIOUSNESS OF GUILT** |
| J18 | **Adrian LinkedIn Close-Up** | `d34686872aaf48532119e3cb8350528f7745e7bc8eee4ec143fc205902951ceb` | Late 2025 | myoutlet.ai removed |
| J19 | **Hebra AI Screenshot** | `79fc8daa7cb339ad8e3eb6fd294706aabe18359514a3c28de6aec5484a3fdd5c` | 2025-2026 | Same business = no non-compete |
| J20 | **Hebra AI Adrian's New Venture** | `007360c1e68e7dc2ee3ca171856003d2d284c0e4b7974e5ee614ef07e1561440` | 2025-2026 | Proves sham transaction |
| J20b | **Adrian Falsely Claiming 2REAL Work** | `ad7fe729a6d9374455177abb03ec2f73e9024d6057e79639dd802998201b4191` | 2025 | False attribution |
| J21 | **EdgeNebula Website Severina CCO** | `469b712bd179eafc5a3b2b4c4c47561d07815a774fa8c14a76809544f8b94071` | Feb 22, 2025 | **CONSCIOUSNESS OF GUILT** |
| J22 | **EdgeNebula Close-Up Founders** | `67481ab201565fa5a68a0da00b654d9b570095ce39466de0d5c909fba8c5ab33` | Feb 22, 2025 | Severina as CCO |
| J23 | **Cassandra "fam" Tweet to Animoca** | `32654ad96841565616f1ad8869a963a813e7892fc5793e8597d2916ffc80e176` | **Oct 21, 2024** | **"FAM" BRANDING PREDATES F.A.M. ANNOUNCEMENT** |
| J24 | **Animoca Insights "fam" Response** | `10eefa4fe74980cdaa2b6e15d0d1232e68c9d89cae05c346d6cc1fbd75586205` | **Oct 21, 2024** | **INSIDER TERMINOLOGY BETWEEN KALEIDOCO/ANIMOCA** |

### Key Finding: "FAM" Insider Terminology — Pre-Planned Branding (J23-J24)

**Key Finding:** On **October 21, 2024** — three months BEFORE Cassandra announced "F.A.M." on Discord — she tweeted:

> *"Grateful to be growing, evolving, and building with the @animocabrands fam... Keep cookin' 🔥"*

In the replies, @CryptoErx asked: *"is @animocainsights cooking too? 🧑‍🍳"*

**Animoca Ecosystem Insights** (@animocainsights) responded:

> *"turn up the heat fam!!!"*

**The word "fam" was already insider terminology between Kaleidoco and Animoca in October 2024.**

| Date | Event | Significance |
|------|-------|--------------|
| **Oct 21, 2024** | Cassandra tweets "fam" to Animoca | Insider branding already in use |
| **Jan 18, 2025** | Cassandra announces "F.A.M." on Discord | Stolen Axel AI launched with pre-planned name |
| **Sept 16, 2025** | Discord destroyed; new server | Evidence elimination |

**This proves:**

1. The Kaleidoco-Animoca relationship was active and public during litigation

2. "F.A.M." wasn't a spontaneous name — it was planned branding

3. Animoca was "cooking" with Kaleidoco while Severina was listed as their witness

4. The stolen Axel AI concept was being developed under the "fam" brand internally

| File | Description |
|------|-------------|
| `CAS_X_POST_FAM_OCT_2024_1.png` | Cassandra's "fam" tweet to Animoca |
| `CAS_X_POST_FAM_OCT_2024_2.png` | Animoca Insights "fam" response |

### Key Finding: Discord Destruction — Evidence Elimination (J11-J13)

**CONSCIOUSNESS OF GUILT:** On **January 18, 2025**, Cassandra Rosenthal announced F.A.M. in the Particle Ink Discord, describing it as:

> *"your F.A.M., Friend, Assistant and Mentor... they will travel with you throughout your daily life supporting you, helping you complete tasks, achieve your goals"*

**This is 2REAL's Axel AI product description VERBATIM.**

**Evidence Destruction Timeline:**

- **April 5, 2025:** OLD Discord ACTIVE (bot analysis screenshot from this date)

- **[Unknown date between April 5 - Sept 16]:** OLD Discord **DESTROYED** — eliminating Jan 18 announcement

- **September 16, 2025:** NEW Discord server launched (fresh start)

**CRITICAL DISCOVERY TARGET:** Subpoena Discord, Inc. for exact deletion date. If destroyed Sept 2-5, 2025 (coordinated with judgment/Hebra launch), this proves synchronized evidence destruction.

**The screenshot survives.**

| File | Description |
|----------------------|---------------------|
| `Cassandra_announcement_18_01_2025.png` | The confession — F.A.M. = Axel AI |
| `PARTICLE_INK_DISCORD_16_SEP_2025.png` | NEW Discord launch (Sept 16, 2025) |
| `05-04-2025-Particle_Ink_Analysis.png` | Bot analysis — fake community (OLD Discord still active April 5) |

### Key Finding: Adrian Whant Evidence Scrubbing (J14-J20)

- **CONSCIOUSNESS OF GUILT:** Adrian prominently featured myoutlet.ai everywhere (Wayback, LinkedIn, Digital Hollywood), then **SCRUBBED** all references after the "sale." He then started **Hebra AI** doing the **EXACT SAME THING** — proving no non-compete existed because the sale was a sham payment for stolen 2REAL intelligence.

| File | Description |
|------------------------|-----------------------|
| `WAYBACK_MY_OUTLETAI_APRIL_2025.png` | myoutlet.ai promotion before scrubbing |
| `ADRIAN_WHANT_DIGITAL_HOLLYWOOD.png` | Digital Hollywood speaker bio |
| `ADRIANWHAT_LINKEDIN.png` | LinkedIn AFTER scrubbing |
| `ADRIANWHANT_LINKEDIN_CLOSEUP.png` | Close-up showing myoutlet.ai removed |
| `HEBRA_AI_SCREENSHOT.png` | Hebra AI — same business model |
| `HEBRA_AI_ADRIAN_NEW_VENTURE.png` | Proves no non-compete = sham sale |

### Key Finding: Lilia Severina Scrubbed from EdgeNebula (J21)

- **CONSCIOUSNESS OF GUILT:** Severina was listed as **FOUNDER & CCO** (Chief Commercial Officer — head of sales) on EdgeNebula website. EdgeNebula filed **OTSI Sanctions Report (4F0FA4)** showing services to **RUSSIA**. Now she's been **SCRUBBED** from the website.

| Date | Event | Evidence |
|------|-------|----------|
| **Feb 22, 2025** | Severina listed as FOUNDER & CCO | `EDGE_NEBULA_WEBSITE_FEB_22_2025.png` |
| **Feb 23, 2025** | OTSI report filed — services to RUSSIA | Reference: 4F0FA4 |
| **Jan 2026** | Severina SCRUBBED; site returns 403 | edge-nebula.com/about-us/ |

- **Critical:** She was NOT listed on Companies House as a director despite being publicly presented as a "Founder." This is intelligence tradecraft — public legend without paper trail.

| File | Description |
|--------------------|-----------------------|
| `EDGE_NEBULA_WEBSITE_FEB_22_2025.png` | **Key Evidence** — Severina as FOUNDER & CCO (full page) |
| `EDGENEBULA_CLOSE_UP.png` | Close-up of "Meet Our Founders" — Severina clearly listed as CCO |

### Key Finding: CE-FILE Download Link Missing (J9-J10)

- **CONSCIOUSNESS OF GUILT:** `CE-FILE_29_JAN_2026_MISSING_LINK.png` shows that the APOC filed by **Daniel Taylor** (Taylor Hampton) containing **Jonathan Hill's** draft now has **NO DOWNLOAD LINK** in CE-FILE.

| Filed By | Document | Filed | CE-FILE Shows | Download |
|----------|----------|-------|---------------|----------|
| Daniel Taylor | Jonathan Hill's APOC draft | May 29, 2025 | May 30, 2025 | **MISSING** |

**Critical Connection:**

- **Daniel Taylor** — already flagged as malware distributor (May 29, 2025 PDF)

- **Jonathan Hill** — already flagged as malware distributor (May 29, 2025 Base64 DOCX)

- **The operatives hiding evidence are the SAME operatives who distributed malware**

### Key Finding: Sinai Removed BOTH National Security References (J6-J8)

- **Key Finding:** `DELETED_DUAL_USE_EDGE_NEBULA.png` shows the edit diff — Sinai systematically removed **BOTH** national security angles in the same edit session:

| Line | Action | What Was Removed |
|------|--------|------------------|
| 23 | DELETED | Footnote reference `1` |
| 24 | DELETED | Full `gov.uk/guidance/export-controls-dual-use-items...` URL |
| 29 | REPLACED | `(https://edge-nebula.com/about-us/)` link |

**EdgeNebula Connection:**

- **EDGENEBULA LTD** (Companies House: 15720185)

- Reported to **OTSI** for sanctions violations (Evidence C4)

- Sinai removed this reference from Spector's pleadings

### Key Finding: Sinai Removed Dual-Use Export Control Reference (J6-J7)

- **Key Finding:** `DRAFTABLE_DUAL_USE_MISSING.png` shows Ali Reza Sinai's draft APOC **removed** Spector's citation to UK government dual-use export control guidance.

| What Was Removed | Evidence |
|------------------|----------|
| `gov.uk/guidance/export-controls-dual-use-items-software-and-technology...` | Draftable comparison (J6) |
| Filed Feb 21, 2025 via Gunnercooke | CE-FILE screenshot (J7) |

**Implications of Suppression:**

| Hidden Element | Consequence |
|----------------|-------------|
| Spector's tech could be **export-controlled** | Theft = potential sanctions violation |
| National security dimension | Case stayed "civil dispute" |
| Transfer to Russia (SELECTEL) | Potential **illegal export** |
| NCSC/MI5/DBT jurisdiction | Proper authorities never notified |

**Sinai deliberately buried the national security angle** — keeping the case framed as John Hayes's "employment dispute" narrative while simultaneously operating on the defendant's side as "Alex Harvey."

### Key Finding: Lucia Chiesa Receiving (Not Creating) IP Assets

- **Key Finding:** Slack screenshot `Slack-Lucia-did-not-invent-axel3.png` proves Lucia Chiesa **RECEIVED** OBGS and Axel files from 2REAL—she did not create them.

| Date | Message | From | Significance |
|------|---------|------|--------------|
| **Jul 19, 2024 9:56 PM** | "the creative who worked on this saved his files locally and was on hols" + OBGS_LOGOS.ai.zip | Nicola | External creative (Intimation Agency) created logos |
| **Jul 19, 2024** | **@Lucia** tagged directly | Nicola | Lucia was RECIPIENT of files |
| **Jul 30, 2024 2:47 PM** | "Axel editable files are here @Daniela" | Nicola | 2REAL controlled/distributed Axel assets |

This destroys Lucia's portfolio claim (luchiesaa.com/obgs) that she created OBGS and Axel. She was **directly @mentioned when receiving files she now claims as her own work**.

---

## Evidence Availability Summary

| Category | Total Items | Available | Pending | Notes |
|----------|-------------|-----------|---------|-------------|
| A: Forensic/Technical | 20 | 20 | 0 | A2 = 10 unique malware samples; A14-A15 = version evolution; A18 = kill switch analysis |
| B: Court Documents | 12 | 12 | 0 | B5 tampered; B10-B12 TWO-PHASE FRAUD |
| C: Corporate Records | 7 | 7 | 0 | All available |
| D: Communications | 7 | 7 | 0 | All available |
| E: Third-Party Validations | 4 | 4 | 0 | Critical corroboration |
| F: Intelligence Reports | 4 | 4 | 0 | F3-F3b Moscow conference hashed |
| G: FBI IC3 | 4 | 4 | 0 | Filed |
| H: Police Reports | 3 | 3 | 0 | UK filed |
| I: Patent/IP | 6 | 6 | 0 | Trade secrets; I2-I3 hashed |
| J: Social Media | 23 | 23 | 0 | J5-J10 Key Evidence; J11-J24 Consciousness of Guilt; J23-J24 FAM branding |

---

## Additional Court Filings

- Complete court filings from BL-2024-000648 (Spector v Severina) are available upon request. This includes all CE-FILE submissions, witness statements, skeleton arguments, applications, and correspondence — too numerous to individually catalog here but preserved with full chain of custody.

---
\newpage
## Chain of Custody Declaration

I, Brian Spector, declare under penalty of perjury that:

1. All evidence described in this index is authentic and has not been modified since collection

2. Digital evidence maintains cryptographic hash verification where indicated

3. All evidence is available for production to federal investigators upon request

4. Evidence obtained from third parties (Uber, Google, etc.) includes contemporaneous documentation

**Brian Spector**
\vspace{2em}

**Signature:** ____________________________
\vspace{2em}

**Date:** February 3, 2026
