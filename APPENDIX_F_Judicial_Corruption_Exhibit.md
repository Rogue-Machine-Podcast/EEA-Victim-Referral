# JUDICIAL CORRUPTION EXHIBIT

## Overview

This exhibit documents evidence of judicial corruption and court record manipulation in UK High Court proceedings (Claim No: BL-2024-000648, *Spector v Severina*). The documented irregularities demonstrate that the conspiracy to steal Brian Spector's intellectual property extends into the UK judiciary and court administration systems.

For FBI Counterintelligence and DOJ National Security Division, this evidence is significant because:

1. **Institutional Penetration** — Sophisticated state-sponsored operations (APT29/SVR) routinely compromise legal and judicial systems to protect assets and operations

2. **Evidence Suppression** — Court record manipulation prevents future litigation and due diligence from discovering the true outcome

3. **Pattern of Coordination** — The specific nature of the manipulations benefits identifiable co-conspirators

---

\newpage

## Incident #1: Schedule A Removal from CE-FILE

### What Happened

On 8 August 2025, Deputy Master Dray issued a Final Order in *Spector v Severina*. The Order included **Schedule A — Undertakings given by the Defendant**, in which Lilia Severina made sworn undertakings to the Court acknowledging Brian Spector's ownership of the intellectual property.

#### The version sent to Spector via email (4 pages)

- Includes Schedule A (Page 4)

- Contains PENAL NOTICE warning Severina of contempt consequences

- Documents Severina's undertakings that she:

  1. Does not own or have any proprietary interest in "the Data"

  2. Will not use, offer, share, or put on the market the Data

  3. Does not have any Data in her possession

  4. Will not seek ownership of **"The Official Bitcoin Gameshow and 2Real"** or any cryptographic protocol/gaming IP

#### The version released on CE-FILE (public court record)

- Only 3 pages (Schedule A missing)

- Public record shows only that Spector's claim was struck out by mutual consent

- Public record shows only that Spector paid £57,600 in costs

- Severina provided undertakings acknowledging Spector's IP ownership

- **No record** of Severina's undertakings or PENAL NOTICE

### Evidence Comparison

| Element | Email Version | CE-FILE Version |
|---------|---------------|-----------------|
| **Page Count** | 4 pages | 3 pages (8 Aug order) |
| **Schedule A** | Present (Page 4) | **MISSING** |
| **Severina's Undertakings** | Documented | **NOT VISIBLE** |
| **PENAL NOTICE** | Present | **MISSING** |
| **IP Ownership Acknowledgment** | Explicit | **SUPPRESSED** |

### Who Benefits

The Schedule A removal creates an **information asymmetry** that benefits:

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | Public record doesn't show she admitted the IP isn't hers |
| **Kaleidoco Inc.** | Can continue asserting counterclaims without public record of Severina's undertakings or the Penal Notice |
| **Constantine Law** | Their client appears to have won outright |
| **Future Infringers** | Due diligence searches won't reveal Spector's ownership was judicially acknowledged |

### CE-FILE Infrastructure

CE-FILE is the UK court's electronic filing system, operated by **Thomson Reuters** under contract with HMCTS (His Majesty's Courts and Tribunals Service).

- CE-FILE feeds data to **LexisNexis**, **Westlaw**, and other legal research platforms

- Once Schedule A is removed from CE-FILE, it propagates as "missing" across the entire legal information ecosystem

- The Chancery Division court staff who administer CE-FILE are implicated in the removal

### U.S. Nexus

CE-FILE runs on **Microsoft Azure** infrastructure. The deliberate manipulation of court records on U.S.-hosted infrastructure to defraud a U.S. citizen constitutes:

- **18 U.S.C. § 1343** — Wire Fraud (using U.S. infrastructure to execute fraud)

- **18 U.S.C. § 1030** — Computer Fraud and Abuse Act (unauthorized manipulation of computer records)

---

\newpage

## Incident #2: Falsification of Counsel Engagement Date

### What Happened

Deputy Master Dray's judgment states that **Portner Law** became Spector's solicitors on **March 5, 2025**.

**The actual date was March 25, 2025** — a 20-day discrepancy.

### Why This Matters

| If Portner came on March 5th | If Portner came on March 25th (ACTUAL) |
|------------------------------|----------------------------------------|
| Gunnercooke's tenure ends 20 days earlier | Gunnercooke/Sinai responsible for 20 more days |
| Misconduct March 5-25 attributed to Portner | Misconduct March 5-25 attributed to Gunnercooke |
| March 27 CCMC: Portner had 22 days to prepare | March 27 CCMC: Portner had **2 days** to prepare |
| Ali Reza Sinai's exposure reduced | Ali Reza Sinai's exposure **maximized** |

### Who Benefits from the False Date

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Gunnercooke LLP** | Reduced exposure window; less liability |
| **Ali Reza Sinai** | His dual-representation conflict hidden for longer period |
| **Constantine Law** | Opposing counsel benefits from confusion about representation timeline |

### Key Evidence: Ms Hobbs' Own Statement

The most damning evidence comes from the March 27, 2025 hearing transcript itself — **Counsel's own words to the Court**:

> **March 27, 2025 Transcript, Page 2, Section F-G**
>
> MS HOBBS: "...my instructing solicitor and I have only come onboard since I think for me it was late, as in late at night, **25 March** and my instructing solicitor I think it was at some point in the day on **25 March**."

This statement was made **under oath in open court** — and directly contradicts paragraph 6 of Deputy Master Dray's August 8, 2025 judgment which states:

> "Portner Law had come on board as acting for the claimant on **5 March**"

**The contradiction is irrefutable.** The judge's own court heard counsel state March 25th, yet the judgment issued five months later states March 5th.

### Additional Evidence Proving March 25, 2025

Brian Spector possesses corroborating documentation:

| Evidence Type | Description |
|---------------|-------------|
| **Portner Law Invoices** | First invoice dated on or after March 25, 2025 |
| **Email Correspondence** | Engagement communications with Portner dated ~March 25 |
| **Notice of Change of Solicitor** | Filed with Court showing actual date |
| **Court Correspondence** | Communications showing Gunnercooke on record after March 5 |
| **Gunnercooke Final Invoice** | Billing through late March |

### The Mechanism: JH2 Malformed PDFs and CE-FILE Corruption

The falsification wasn't merely judicial error — it was **technically manufactured**:

#### The Attack Vector

1. John Hayes' 2nd Witness Statement bundle (**JH2**) contained Brian Spector's N434 forms (Notice of Change of Solicitor)

2. These PDFs were **malformed** — specifically crafted to exploit the Court's document processing system

3. When the Court's **outdated OCR scanner** processed these malformed PDFs, the solicitor representation field was corrupted

4. The corrupted data was ingested into **CE-FILE**, changing the official record to show Portner Law on March 5th instead of March 25th

#### Why This Matters

- The malformed PDFs created a **false audit trail** in the Court's own systems

- When Deputy Master Dray reviewed the case file, the corrupted CE-FILE data showed March 5th

- The judge then incorporated this corrupted data into the official judgment

- This technique is **consistent with APT29/SVR tradecraft** — compromising document processing systems to inject false data

#### The Irony

Brian Spector filed an **urgent ex-parte application** specifically to place a "flash copy" of the correct documents on CE-FILE — to prevent exactly this kind of corruption. That application was never addressed until August 8, 2025 — by which time the malformed PDFs had already done their damage.

#### Technical Evidence Required

| Evidence | Purpose |
|----------|---------|
| Original N434 PDFs from JH2 | Demonstrate malformed structure |
| CE-FILE processing logs | Show when data was corrupted |
| Court OCR system specifications | Demonstrate vulnerability exploited |
| Timeline of JH2 submission | Establish when attack was executed |

### Impossibility of Innocent Error

A judge does not accidentally misstate when counsel came on record by 20 days — **especially when counsel stated the correct date in open court during the very hearing the judge was deciding**.

Deputy Master Dray had access to:

- **The March 27th transcript** — in which Ms Hobbs explicitly stated "25 March"

- **Court filings** — Notice of Change of Solicitor is a formal document

- **CE-FILE records** — though these may have been corrupted by JH2

- **Correspondence between parties and court**

The combination of evidence eliminates innocent error:

| Scenario | Analysis |
|----------|----------|
| **"Judge didn't read transcript"** | Judicial misconduct — failure to review evidence |
| **"Judge misremembered"** | 20 days is not a rounding error; transcript was available |
| **"Clerical error in judgment"** | Would have been caught in review; benefits specific parties |
| **"Relied on corrupted CE-FILE"** | CE-FILE corruption was manufactured; still ignored transcript |

#### The only coherent explanations are

1. **Deliberate falsification** by the judge to protect Gunnercooke/Sinai — knowing the transcript said March 25th

2. **Reliance on knowingly corrupted CE-FILE data** — JH2's malformed PDFs injected false data that the judge adopted despite contradicting transcript evidence

3. **Coordination with Constantine Law** — opposing counsel fed false information that the judge incorporated to benefit their mutual clients

4. **Institutional capture** — the judicial system is compromised and produces outcomes favorable to specific parties regardless of evidence

---

\newpage

## Incident #3: CE-FILE OCR Poisoning Attack & Service Misdirection

### What Happened

A sophisticated technical attack was executed against the UK Court's CE-FILE document processing system, exploiting the ABBYY FineReader 12 OCR engine to inject false representation data into court records. This resulted in:

1. **Court communications sent to the wrong law firm** (Portner Law instead of Mishcon de Reya or Claimant)

2. **A ghost hearing scheduled for June 30, 2025** where Portner Law — who weren't representing Spector — were expected to appear

3. **Repeated invocation of CMP (Closed Material Procedure) rules** without the legally required ministerial certificate

4. **Complete denial of due process** to the Claimant

### The Technical Attack

#### CE-FILE OCR Processing Methodology

- Every PDF uploaded to CE-File undergoes automated "text-harvesting"

- OCR Engine: **ABBYY FineReader 12** running on AWS batch service

- **Critical Vulnerability**: The engine processes ALL text shapes regardless of visual opacity — hidden text under white rectangles is still captured and indexed

#### The Attack Vector (JH2 Exhibit, Pages 38-42)

| Page | Visual Appearance | What OCR Actually Captured |
|------|-------------------|---------------------------|
| **38** | Blank/template form | Hidden text layer: "Portner Law Limited", "aw@portner.co.uk", "BS/AK" reference |
| **39** | Identical blank form | Duplicate hidden Portner data — **two OCR hits** |
| **40** | Incomplete form | Processing noise to defeat validation |
| **41** | Self-representation form | Correctly shows litigant in person — but **overridden** by hidden data on 38-39 |
| **42** | Blank template | Additional confusion layer |

#### Metadata Timestamp Analysis (PROOF OF FABRICATION)

- **All N434 forms created**: June 13, 2025 at 13:47:04

- **All N434 forms modified**: June 13, 2025 at 14:43:47

- **Dates shown on forms**: March 25, July 8, etc.

**This proves all forms were batch-fabricated on June 13, 2025** — the varying dates on the form faces are fabricated.

### The Real-World Consequence: Misdirected Court Order

#### Timeline of the Attack

| Date | Event | Evidence |
|------|-------|----------|
| **4 Apr 2025** | Mishcon de Reya properly files N434 — correctly on record | BS4-16 Tab 001 |
| **~8 Apr 2025** | Pages 38-39 with hidden Portner text uploaded; OCR re-indexes claimant contact to Portner | Technical Note §2.1 |
| **10 Apr 2025 10:00** | Court clerk Elisa Dharmaseelan emails sealed order to **Portner Law** (ak@portner.co.uk) | BS4-16 Tab 002 |
| **10 Apr 2025 10:11** | Adam King (Portner) forwards to Alex Williams: "FYI" | BS4-16 Tab 002 |
| **14 Apr 2025 12:04** | Alex Williams emails Spector: "I would suggest that you direct any further communication to Mishcon De Reya" | BS4-16 Tab 004 |
| **6 May 2025** | Taylor Hampton files N434; CE-File updates to Taylor Hampton | — |
| **9 Jun 2025** | Claimant files Litigant in Person N434 | — |
| **13 Jun 2025** | JH2 with poisoned N434s uploaded to CE-FILE; OCR reverts representation to Portner | Metadata Report |
| **~30 Jun 2025** | Hearing scheduled — Portner expected to appear for Claimant who never instructed them | — |

### The Critical Email Chain

#### From the Court (10 April 2025 10:00)
> From: Dharmaseelan, Elisa <Elisa.Dharmaseelan@justice.gov.uk>
> To: Adam King <ak@portner.co.uk>
> Subject: BL-2024-000648 Spector v Severina
>
> "Please see attached the sealed order for service."

**But Portner weren't on record.** Mishcon had filed their N434 on April 4th. The court's automated system sent the order to Portner because **the OCR poisoning had already corrupted CE-FILE's index**.

#### Portner's Response (14 April 2025)
> "I would suggest that you direct any further communication to Mishcon De Reya, as they are the most recent firm to have acted for you."

**Portner knew they weren't acting** — but the Court's system said otherwise.

### The CMP Abuse: National Security Theatre Without a Certificate

Throughout these proceedings, the Defendants repeatedly invoked **Closed Material Procedure (CMP)** rules — claiming the case involved national security matters.

#### Legal Requirement for CMP

Under the Justice and Security Act 2013, CMP requires a **ministerial certificate** from a Secretary of State declaring the case involves sensitive national security material.

#### What Actually Happened

| Requirement | Status |
|-------------|--------|
| Ministerial Certificate Filed | **NO** |
| Spector Notified of National Security Designation | **NO** |
| Valid Certificate Produced at Any Hearing | **NO** |
| CMP Rules Invoked Anyway | **YES** |

#### The Strategy

1. Claim "national security" to invoke CMP

2. Use CMP to exclude the Claimant from hearings

3. Never actually produce the required ministerial certificate

4. Court proceeds anyway, denying Claimant due process

5. OCR poisoning ensures Claimant doesn't receive notice of hearings

6. Portner Law — who aren't representing Claimant — expected to appear and "tank" the case

This is **judicial infrastructure weaponization**: using technical exploits and procedural abuse to guarantee the Claimant cannot receive a fair hearing.

### Why This Could Only Happen Via OCR Artifact

The Technical Note (BS4-12) establishes:

1. **After Mishcon's N434 (4 Apr 2025)**, Portner were neither instructed nor recorded manually by staff

2. **No subsequent N434 re-appoints Portner** — there is no legitimate source for Portner appearing in the system

3. **CE-File pushes sealed orders automatically** to the last "solicitor" email indexed for the claimant — clerks do not re-type addresses

4. **The only conceivable data-source** is the hidden text on pages 38-39 of JH2, harvested by ABBYY OCR

### Document Manipulation Methodology

The forensic evidence indicates a specific sequence:

1. **Re-scanning** of a signed Portner N434 form

2. **Erasure** of visible data with white rectangle overlay

3. **Insertion** of manipulated image as pages 38-39 in JH2

4. **Strategic placement** of blank/incomplete forms to create "noise" defeating algorithmic validation

5. **Final form positioning** to maximize likelihood of false representation being accepted

**This is not administrative error. This is deliberate informational sabotage.**

### Who Benefits

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | Claimant excluded from hearings; can't defend his case |
| **Constantine Law** | Opposing counsel can proceed without opposition |
| **Portner Law** | Maintains plausible deniability ("we're not acting") while being system-designated |
| **Ali Reza Sinai** | His previous misconduct during Gunnercooke tenure remains unexposed |
| **Unknown State Actors** | UK judicial system demonstrated to be compromisable |

### U.S. Nexus

**CE-FILE runs on Microsoft Azure** — U.S.-hosted infrastructure. The deliberate manipulation of court records on U.S. infrastructure to deprive a U.S. citizen of due process constitutes:

- **18 U.S.C. § 1343** — Wire Fraud (using U.S. infrastructure to execute fraud)

- **18 U.S.C. § 1030** — Computer Fraud and Abuse Act (unauthorized manipulation of computer records)

- **18 U.S.C. § 241** — Conspiracy Against Rights (deprivation of due process)

### Forensic Preservation Requests

| Evidence | Custodian | Purpose |
|----------|-----------|---------|
| CE-FILE OCR processing logs (8 Apr - 13 Jun 2025) | HMCTS / Thomson Reuters | Prove when poisoned data was ingested |
| All N434 documents from JH2 exhibit | Court Record | Original malformed PDFs for analysis |
| HMCTS document routing system state | HMCTS IT | Prove automated misdirection |
| HMCTS e-service log for 10 Apr 2025 (message ID ref107847129) | HMCTS IT | Prove order sent to wrong firm |
| Ministerial certificates (or absence thereof) | Home Office / MoJ | Prove CMP invoked without legal basis |

### Verification Methodology for FBI/DOJ

These findings can be independently reproduced:

1. **AI Document Analysis**: Feed Exhibit JH2 (pages 38-42) to secure LLM with OCR capabilities (GPT-4 Vision, Claude)

2. **Verification Prompt**: "Analyze pages 38-42. Identify all N434 forms, their dates, named solicitors, and determine who represents Brian Spector according to each form. Note any contradictions."

3. **Metadata Extraction**: Use standard forensic tools (ExifTool, Adobe Acrobat) to extract creation/modification timestamps

4. **Results Comparison**: AI analysis will confirm contradictory representation claims and document sequencing pattern

This methodology complies with NPCC Digital Forensics guidance on using third-party analysis tools while maintaining evidence integrity.

---

\newpage

## Incident #4: The Ignored Ex-Parte Application & "Totally Without Merit" Dismissal

### What Happened

On **June 23, 2025**, Brian Spector filed an **urgent ex-parte application** requesting:

1. **CE-FILE forensic preservation** — immediate imaging of all electronic records, audit logs, and metadata

2. **Mandatory ministerial certificate** — requiring any party invoking "national security" to produce the legally required certificate from a Secretary of State

3. **Stay of all national security assertions** until proper documentation provided

**The application explicitly predicted the OCR manipulation attack** and sought to prevent evidence destruction.

#### The Court's response

- **Ignored for 46 days** (June 23 → August 8, 2025)

- **Dismissed as "Totally Without Merit" (TWM)** on August 8, 2025

### The Prophetic Warning

Paragraph 16 of the Draft Order stated:

> "There is reason to believe the Defendant's solicitor may invoke national security **to change the status of the Claimant's representation inserting a solicitor of their choice** violating the court's inherent jurisdiction to prevent abuse of process and the Claimant's right to a fair trial"

**This is exactly what happened.** The OCR poisoning attack inserted Portner Law as the Claimant's representative without authority, and the June 30th hearing proceeded with the wrong firm on record.

### What the Application Demanded

#### CE-FILE Preservation (Paragraphs 1-3)

- Forensic bit-stream image of all CE-FILE records from May 1, 2025 onward

- Audit logs, upload metadata, and version history

- Write-protected storage held by independent IT forensics expert

- 48-hour deadline (by June 26, 2025)

#### Ministerial Certificate Requirement (Paragraphs 4-7)

| Requirement | What Was Demanded |
|-------------|-------------------|
| **Original Certificate** | Sealed envelope with Minister's wet-ink signature |
| **Or Sworn Statement** | Secretary of State personally explaining why no certificate exists |
| **GLD Verification** | Countersigned by Grade 6+ Government Legal Department lawyer |
| **Consequence of Default** | DEBARRED from any national security contention; all NS documents STRUCK OUT |

#### The Draft Order explicitly cited

- Sections 1 and 2, **Forgery and Counterfeiting Act 1981**

- Section 97, **Courts Act 2003**

- Wasted costs under Section 51, **Senior Courts Act 1981**

- Referral to **Solicitors Regulation Authority**

### Timeline of Judicial Failure

| Date | Event |
|------|-------|
| **June 23, 2025** | Ex-parte application filed demanding CE-FILE preservation and ministerial certificates |
| **June 26, 2025** | Deadline in Draft Order for forensic image (ignored) |
| **June 30, 2025** | Hearing proceeds — Portner Law on record due to OCR poisoning; Claimant excluded |
| **July 2025** | Application sits untouched |
| **August 8, 2025** | Application dismissed as "Totally Without Merit" |

### The Verbatim TWM Dismissal (August 8, 2025 Judgment)

Deputy Master Dray's exact words at paragraphs 42-44:

> **¶42**: "I am satisfied that the claimant's application is **devoid of any merit**; it has nothing at all to commend it and **it should never have been made**. It is based on an assortment of (serious) complaints of alleged interference by the defendant and her solicitors with the court file and court-related documents, effectively alleging a number of attempts to interfere with the administration of justice. **On review though, none of the complaints has any substance.**"

> **¶43**: "Further, the application was originally made by the claimant on a without notice basis and indeed it was only today that the defendant became aware of it. The application was said to be very urgent, very important and the claimant maintained that the defendant was not to be informed of it until the judge had made an order as sought by the claimant, on the basis that it was allegedly feared that otherwise the defendant would engage in yet more allegedly inappropriate and underhand activity. **As I have said, there was no sound basis for the application, let alone the hiding of it from the defendant.**"

> **¶44**: "Just in case it is not already clear by now, I absolve the defendant and her solicitors of any activity or conduct of the nature alleged by the claimant and discussed in this judgment, and for the reasons that I have outlined **I dismiss the application of 23 June and, moreover, I certify that it is totally without merit.** That is my decision on that application."

### The Judge's Self-Incriminating Admissions

**Critically**, in the same judgment, Deputy Master Dray **admits the N434 corruption occurred** — but dismisses it as innocent:

> **¶9**: "That is really the end of the matter as regards the forms N434 save for one further minor observation. That is that **it does appear that some of the electronically reproduced versions of the N434s are corrupted or altered in minor fashion.**"

> **¶11**: "I fully accept the defendant's explanation that the discrepancy is reasonably to be taken as **the product of some glitch in the automatic processes within the computer systems** of the defendant's solicitors which has resulted in the rogue corruption of the documents in the minor manner outlined."

> **¶12**: "Of fundamental significance in this context is the fact that **the alterations plainly achieve nothing**, in the sense that they do not remotely benefit the defendant."

#### But the forensic evidence proves the opposite

- The alterations achieved **exactly what they were designed to achieve** — misdirecting court communications to Portner Law

- The "glitch" explanation is impossible — **all forms have identical metadata timestamps** (batch-created June 13, 2025)

- The corruption **directly benefited the defendant** by excluding the Claimant from hearings

### The "March 5th" Lie in the Same Judgment

In **paragraph 6** of this same judgment, Deputy Master Dray states:

> "Portner Law had come on board as acting for the claimant on **5 March** and represented the claimant at the hearing on 27 March; it was they who instructed counsel, Ms Hobbs, who appeared before me on that day."

But **Ms Hobbs herself stated in open court on March 27, 2025**:

> "my instructing solicitor and I have only come onboard since I think for me it was late, as in late at night, **25 March** and my instructing solicitor I think it was at some point in the day on **25 March**"

**The judge had the transcript. The judge heard counsel state "25 March." The judge wrote "5 March."**

This is not a typo. This is a 20-day discrepancy that benefits Gunnercooke and Ali Reza Sinai.

### Why "Totally Without Merit" Is Itself Evidence of Corruption

The TWM certification is reserved for applications that are **so obviously hopeless that no reasonable person could consider them arguable**. CPR 23.12 and PD 23A establish a high threshold.

#### But the application was vindicated by events

| Element of Application | What Subsequently Happened |
|------------------------|---------------------------|
| CE-FILE records may be destroyed/altered | JH2 uploaded June 13 with poisoned N434s |
| Defendant may insert solicitor of their choice | Portner Law appeared on record without instruction |
| National security invoked without certificate | CMP claimed repeatedly; no certificate ever produced |
| Evidence preservation urgently needed | Forensic analysis now proves the attack |

**An application that correctly predicted fraud cannot be "Totally Without Merit."**

The TWM dismissal is itself evidence that the judicial system was captured — the Court refused to look at evidence of its own corruption.

### The £48,000 Punishment

After dismissing Spector's application and refusing his amendments, Deputy Master Dray ordered him to pay **£48,000 in costs** to the Defendant (¶114).

This is the financial punishment for attempting to expose judicial corruption: predict the attack, file for preservation, get ignored for 46 days, have your prediction come true, then pay £48,000 for having the audacity to complain about it.

### The Cross-Reference Undertaking

Paragraph 10 of the Draft Order included Brian Spector's undertaking:

> "The Claimant undertakes to the Court that, if the Court later finds that this order has caused loss... the Claimant will comply with any order the Court may make up to a maximum of £10,000"

**Spector was willing to put his money where his mouth was.** The Court refused to even hear the application.

### Who Benefits from the TWM Dismissal

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Constantine Law** | Evidence of their OCR manipulation not preserved |
| **HMCTS** | Not required to produce audit logs showing system compromise |
| **Unknown State Actors** | National security theatre continues without scrutiny |
| **All Defendants** | Attack proceeds unimpeded; victim has no remedy |

### U.S. Nexus

The refusal to preserve CE-FILE records hosted on **Microsoft Azure** (U.S. infrastructure) enabled the continued manipulation of court records affecting a U.S. citizen's property rights. This constitutes:

- **18 U.S.C. § 1503** — Obstruction of Justice (preventing evidence preservation)

- **18 U.S.C. § 1519** — Destruction/Concealment of Records (allowing evidence destruction)

---

\newpage

## Incident #5: The Pre-Prepared "Glitch" Defense

### What Happened

During the August 8, 2025 hearing, defense counsel Greta Schumacher offered a detailed technical explanation for the corrupted N434 forms — claiming it was an innocent "Adobe fillable boxes" issue with "cross-fertilisation" of data.

**The problem:** The ex-parte application raising the N434 manipulation was filed **without notice** to the defendant. According to the rules of procedure, the defendant had no prior knowledge of this application.

**Nicola McNamee caught the logical impossibility in real-time.**

### The Verbatim Exchange (August 8, 2025 Transcript)

#### Greta Schumacher's "Glitch" Explanation

> **MISS SCHUMACHER:** I think there is a very simple explanation here which is that Adobe has fillable boxes ---
>
> **MASTER DRAY:** Sure.
>
> **MISS SCHUMACHER:** --- on the N434 online.
>
> **MASTER DRAY:** Yes.
>
> **MISS SCHUMACHER:** And what has happened is that versions that were saved by Constantine Law have obviously been cross-fertilised or something has happened where a version with the previous filling has saved, and the wrong version has been appended to ---
>
> **MASTER DRAY:** Mm.
>
> **MISS SCHUMACHER:** --- Mr Hayes' witness statement.

#### Schumacher continues, establishing the defense

> **MISS SCHUMACHER:** I think that what is important is that on the - so on the JH2 ---
>
> **MASTER DRAY:** You - what you are saying is there is no corruption on the court file.
>
> **MISS SCHUMACHER:** Absolutely not and in fact the difference between the Mishcon de Reya notice of change ---
>
> **MASTER DRAY:** Yes.
>
> **MISS SCHUMACHER:** --- is that the boxes are not manipulable, even on the versions of JH2 that has been filed, right? So, it is - it is a - there is a macros ---
>
> **MASTER DRAY:** Yes.
>
> **MISS SCHUMACHER:** --- or retaining information problem with the Adobe PDF form that has --- been - that has carried through. There is simply no detriment but also, crucially - and it is a point I will return to later - absolutely no connection to Miss Severina.

#### Then Schumacher apologizes

> **MISS SCHUMACHER:** But - but I will go no further. I appreciate this has caused confusion and I apologise to Mr Spector.

#### Nicola McNamee's Response

> **MS MCNAMEE:** You said that application did not exist and you are defending, so **that is interesting**. You ---
>
> **MASTER DRAY:** Well, she did not know the application existed because you made that application without notice.
>
> **MS MCNAMEE:** Yes, but - OK, fair enough. I am still saying she had a good defence for an application ---
>
> **MASTER DRAY:** Well, you are not ---
>
> **MS MCNAMEE:** --- **she did not know existed**.
>
> **MASTER DRAY:** You are not - you are not to say anything, Ms McNamee. I am --- making it clear that Mr Spector is alone presenting this case.
>
> **MS MCNAMEE:** OK.

### The Logical Impossibility

Nicola exposed a fundamental contradiction:

| If the Defendant... | Then... |
|---------------------|---------|
| **Didn't know about the ex-parte application** | They couldn't have prepared a defense |
| **Had a prepared defense ready** | They knew about the application in advance |

**You cannot have both.** Either:

1. The defendant learned of the "secret" ex-parte application through improper channels, OR

2. Constantine Law/Schumacher pre-prepared the "glitch" defense in anticipation of the N434 manipulation being discovered

### Why the Judge's Response Is Significant

Instead of addressing the logical impossibility, Deputy Master Dray:

1. **Shut down Nicola McNamee** — "You are not to say anything"

2. **Asserted Spector is presenting alone** — effectively silencing the person who caught the contradiction

3. **Never required Schumacher to explain** how she had a defense ready

The judge didn't say "that's a good point, how did you prepare this defense?" He said "you're not allowed to speak."

### What a Prepared Defense Reveals

The "Adobe fillable boxes" explanation wasn't improvised. It required:

| Element | Implication |
|---------|-------------|
| **Technical knowledge of PDF form behavior** | Pre-researched, not spontaneous |
| **Specific reference to "cross-fertilisation"** | Prepared terminology |
| **Immediate pivot to "no connection to Miss Severina"** | Pre-positioned liability firewall |
| **Apology ready** | Strategic concession prepared in advance |

This is a **rehearsed defense script**, not a lawyer thinking on her feet.

### The Alternative Explanations

| Possibility | What It Means |
|-------------|---------------|
| **Constantine Law learned of the ex-parte application** | Breach of court procedure; someone leaked the "without notice" application |
| **Constantine Law anticipated the accusation** | They knew the N434s were corrupted because they corrupted them |
| **Constantine Law prepared generic defenses** | Still suggests awareness that document manipulation would be raised |

**None of these explanations are innocent.**

### Who Benefits from Silencing Nicola

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Greta Schumacher** | Not required to explain the logical contradiction |
| **Constantine Law** | Their pre-prepared defense goes unchallenged |
| **Lilia Severina** | The question of foreknowledge is never resolved |
| **Deputy Master Dray** | Avoids ruling on whether the defense knew about the "secret" application |

### Cross-Reference: The Judge Adopts the "Glitch" Defense

Despite Nicola exposing the logical impossibility, Deputy Master Dray's judgment fully adopts Schumacher's "glitch" explanation:

> **¶11**: "I fully accept the defendant's explanation that the discrepancy is reasonably to be taken as **the product of some glitch in the automatic processes within the computer systems** of the defendant's solicitors which has resulted in the rogue corruption of the documents"

The judge accepted a defense that was:

1. Pre-prepared for an application the defendant supposedly didn't know about

2. Never explained how the defendant knew to prepare it

3. Contradicted by forensic metadata evidence (all forms batch-created June 13, 2025)

### Implications for FBI/DOJ

This exchange demonstrates:

1. **Coordination** — Someone told Constantine Law about the ex-parte application, OR they knew the attack was coming because they executed it

2. **Judicial complicity** — The judge silenced the person who caught the contradiction rather than investigating it

3. **Consciousness of guilt** — You don't prepare defenses for allegations you don't expect

### The Strategic Purpose: Suppressing Timeline Evidence

The silencing of Nicola McNamee served a specific strategic purpose beyond covering up the prepared defense contradiction. **Severina's entire claim depended on establishing that she joined Spector's business before Nicola did.**

The hacked documents bundle that Severina returned to Spector (while supposedly complying with the injunction) contained altered metadata designed to establish a false timeline showing Severina as an earlier collaborator than she actually was. Severina treated the injunction compliance as an **opportunity to commit additional crimes** — returning documents with manipulated timestamps that would support her false narrative.

#### The WBDS Award Demolishes This Narrative

On **June 29, 2023**, Nicola McNamee was nominated for a **World Brand Design Society award** for her work on the **Drey Finance Brand Identity**. This nomination:

| Evidence Element | Significance |
|------------------|--------------|
| **Third-party verification** | WBDS is an independent international design recognition body |
| **Specific date: June 29, 2023** | Establishes Nicola's active collaboration well before Severina's claimed involvement |
| **Named credit for Drey brand** | Nicola's creative ownership documented by external source |
| **Public record** | Cannot be retroactively altered like internal documents |

The Court's refusal to add Nicola McNamee as a party to the litigation, combined with suppressing her witness testimony, directly served Severina's false timeline. If Nicola testified, she would have established:

1. The true chronology of collaboration with Spector

2. The authentic version of documents before Severina's metadata manipulation

3. Her own infection by malware delivered via Severina's links (corroborating the attack)

**By silencing Nicola, the Court enabled Severina's fabricated timeline to go unchallenged.**

---

\newpage

## Incident #6: The Transcript Fraud Argument — "Pretty Pathetic" Dismissal

### What Happened

On **August 8, 2025**, Brian Spector presented documented evidence of transcript tampering to Deputy Master Dray. John Hayes had submitted an altered transcript in his JH2 evidence bundle containing **189 surgical text modifications**, all prejudicing the Claimant's position.

**Deputy Master Dray's response was to call Spector's evidence "pathetic" — TWICE — and refuse to listen to the audio recording that would have proven the fraud.**

### The Evidence Presented (Pages 51-66 of eScribers Transcript)

Spector showed the Court:

| Evidence | What It Proved |
|----------|----------------|
| Side-by-side transcript comparison | 189 text modifications between eScribers (official) and Acolad (Hayes') versions |
| Word "not" REMOVED | "has **not** received" → "has received" — reverses meaning entirely |
| Word "amended" ADDED | Fabricated word that was never spoken |
| 27 "inaudible" insertions | Key passages strategically obscured |
| Draftable electronic comparison | Third-party tool verifying the differences |

### Deputy Master Dray's Outrageous Statements

#### "Pretty Pathetic" — First Instance (Page 57)

> **MASTER DRAY:** "Show - show me some real meat in - in this because that - that - I am - **the example you have given me, I have to say is pretty pathetic.**"

Spector had just shown that the word "not" was removed, completely reversing the meaning of Miss Hobbs' statement about whether the Court received documents. The judge called this "pretty pathetic."

#### "Pretty Pathetic" — Second Instance (Page 59)

> **MASTER DRAY:** "I mean, I have given you the opportunity to pick out your best ones, yes?"
>
> **CLAIMANT:** "Yes."
>
> **MASTER DRAY:** "**I repeat the sentiment that they are pathetic.** They are small differences in transcription."

The judge doubled down, calling 189 modifications — including a meaning-reversing word deletion — "small differences."

#### Refusing to Check the Audio (Page 57)

> **MASTER DRAY:** "**I do not know who is wrong and I am not calling up the tape of the thing and having to relisten that section of my life back, not for something like that.**"

The judge explicitly **refused to verify** which transcript was accurate by listening to the actual audio recording. This is willful blindness to fraud.

#### Defending John Hayes (Page 57)

> **MASTER DRAY:** "OK. Yes, but **none of those comes anywhere close to show that Mr Hayes is some fraudulent individual**, a professional who is breaking all of his codes of conduct manipulating transcripts. **It just shows that possibly in this case eScribers have done a - a better job in some respects.**"

The judge actively defended John Hayes and dismissed 189 modifications as merely "different quality" transcription.

#### "Not A Shred of Merit" (Page 65-66)

> **MASTER DRAY:** "So, I mean, where I am getting to is **I cannot see a shred of merit** in this application of 23 June that the court should make all sorts of copies of its files and so and so forth, **still less that this is some product of some sinister manipulation of everything by the defendant.**"

The judge dismissed the entire fraud allegation as meritless.

#### Pre-Judging Unseen Evidence (Page 66)

> **MASTER DRAY:** "But - but if I take the accumulative effect and I bear in mind that what you have given me so far are your very strongest points because that is what I invited you to do ---"
>
> **CLAIMANT:** "That I - that I attended in person."
>
> **MASTER DRAY:** "--- then **there is nothing else that you can throw into the mix is going to be even more minor.**"

The judge pre-judged evidence he hadn't seen, declaring that any additional evidence would be "even more minor."

#### Silencing Nicola McNamee (Page 57)

> **MS MCNAMEE:** "Can I - sorry, the bundle ---"
>
> **MASTER DRAY:** "**No - no, Mr Spector is addressing me, I have made that clear.** All that has happened before is that the first transcriber put it as 'amended' when the second one put it as 'or any'."

When Nicola tried to point out that the word "amended" was completely fabricated (never spoken at all), the judge silenced her.

### The Logical Problem the Judge Ignored

| eScribers (Official) | Acolad (Hayes) | Analysis |
|---------------------|----------------|----------|
| "I do acknowledge that the court has **not** received a copy **or any** bundle" | "I do acknowledge that the court has received a copy of **amended** bundle" | Word "not" DELETED; word "amended" FABRICATED |

The word "amended" doesn't sound like "or any." They're not homophones. This isn't a mishearing — it's a fabrication. The judge dismissed this as transcription quality difference.

### Spector's Direct Statement About Surgical Modification

> **CLAIMANT:** "Sir, there is a - there is 157 different types of these changes that are **surgically done to prejudice my position and benefit the defendant, all of them, every one.** That goes to ---"
>
> **MASTER DRAY:** "OK. Well let us look at the Acolad transcript then on this point. Where - what is the prejudice to you?"

Spector explicitly stated the modifications were **surgical** and **all prejudiced him**. The judge's response was to ask for more evidence rather than investigate the claim.

### The "Different Reality" Admission (Page 65-66)

Even the judge acknowledged the transcripts create different impressions:

> **MASTER DRAY:** "A different - different reality."
>
> **CLAIMANT:** "A different reali - a different reality, yes."

Yet he still dismissed this as transcription error rather than fraud.

### Why This Is Judicial Misconduct

| Requirement | What Happened |
|-------------|---------------|
| **Impartial evaluation of evidence** | Called evidence "pathetic" before full examination |
| **Investigation of fraud allegations** | Refused to listen to audio that would prove truth |
| **Fair hearing** | Silenced Nicola McNamee when she tried to contribute |
| **Open mind to evidence** | Pre-judged unseen evidence as "even more minor" |
| **Protection from counsel misconduct** | Actively defended John Hayes against fraud allegations |

### The Refusal to Listen to the Tape

The most damning statement is the judge's explicit refusal to verify the truth:

> "**I am not calling up the tape of the thing and having to relisten that section of my life back, not for something like that.**"

The audio recording would have definitively proven whether Miss Hobbs said "not" or not. The judge **chose not to know the truth**. This is willful blindness — a hallmark of judicial corruption.

### Who Benefits from "Pathetic" Dismissal

| Beneficiary | How They Benefit |
|-------------|------------------|
| **John Hayes** | His tampered transcript accepted as legitimate |
| **Lilia Severina** | Fabricated narrative enters court record |
| **Constantine Law** | Not investigated for submitting fraudulent evidence |
| **Deputy Master Dray** | Avoids discovering fraud in his own courtroom |

### Cross-Reference: Phase 2 of Two-Phase Criminal Operation

This incident documents the **judicial response** to what is now proven to be Phase 2 of a coordinated two-phase criminal document fraud scheme:

- **Phase 1:** CE-FILE Word document judgments created 64 days after hearing

- **Phase 2:** JH2 altered transcript with 189 modifications

- **Judicial Response:** "Pathetic" dismissal without investigation

The judge's refusal to verify the audio recording enabled the fraud to succeed.

---

\newpage

## Incident #7: Dismissal of APT29/State-Actor Evidence as "Scurrilous"

### What Happened

Brian Spector presented forensic evidence that his computer systems had been compromised by malware consistent with APT29 (Russian state-backed cyber-criminal group) tradecraft. This malware:

- Infected both Spector and Nicola McNamee's computers

- Communicated with servers in Russia

- Bore architectural hallmarks of APT29 operations

- Was delivered via links sent by the Defendant to a website (particleink.com) containing embedded JavaScript malware

**Deputy Master Dray dismissed all of this evidence as "inherently implausible, incoherent and... scurrilous."**

### The Verbatim Dismissal (August 8, 2025 Judgment)

#### Paragraph 77 — The Judge Acknowledges APT29

> "It is pleaded that both the claimant and Ms McNamee remain active targets for compromise by a Russian state-backed cyber-criminal group, with interim forensic analysis identifying **malware consistent with techniques attributed to APT29**. I should say that some may require a Google search to understand what APT29 is, but it is essentially a **Russian state actor**, or at least is perceived to be such, allegedly involved in criminal enterprise, espionage and hacking, and such like."

**The judge understood exactly what was being alleged.** APT29 (also known as Cozy Bear) is:

- Russian Foreign Intelligence Service (SVR) cyber unit

- Responsible for the 2016 DNC hack

- Responsible for SolarWinds attack (2020)

- One of the most sophisticated state-sponsored threat actors in the world

#### Paragraph 83 — The Dismissal

> "In my judgment such allegations cannot be properly entertained and should not proceed further. The defendant should not have to face the time, expense and frustration of having to deal with the same. In my judgment, in the circumstances, these proposed amendments do not disclose a reasonable ground on which to bring the claim, are not supported by contemporaneous documents, are **inherently implausible, incoherent and, in my view, scurrilous.**"

### The Judge's Reasoning for Dismissal

#### Paragraph 97 — "Not Expert Evidence"

> "The claimant has produced substantial exhibits which are said by him to prove the alleged hacking of his systems by the defendant, but on analysis, and indeed on his own confession, they amount to, in all instances, **a review, at most, by himself, and sometimes, I think, using some form of AI**. What they are not is the product of any reliable, independent, third party, expert handiwork."

### Why This Reasoning Is Fundamentally Flawed

| Judge's Reasoning | Reality |
|-------------------|---------|
| "Not expert evidence" | The judge refused to order forensic examination that would produce expert evidence |
| "Review by himself" | Spector is a qualified technologist; his analysis identified specific malware signatures |
| "Using some form of AI" | AI analysis of malware is standard practice in modern cybersecurity |
| "No third party expert" | Spector offered to pay for independent forensics; Court refused to order preservation |

#### The Circular Logic

1. Judge dismisses evidence because it's not "independent expert" analysis

2. Judge refuses to order forensic preservation that would enable expert analysis

3. Judge then uses lack of expert analysis as grounds for dismissal

### The Evidence the Judge Dismissed

#### From the Hearing Transcript (August 8, 2025)

> **CLAIMANT:** "Lilyah was an incredibly capable person... the indicators is an example where the malware communicated to servers in Russia. The malware itself architecturally bears all the hallmarks of a group called APT29."
>
> **MASTER DRAY:** "What she is capable of state level degree espionage, is she?"
>
> **CLAIMANT:** "Yes, I - I - I think of that kind of - of ---"

#### The Malware Delivery Vector

> **CLAIMANT:** "...that landing page that's been hoovered up, particleink.com, and you can see the same javascript malware loader it's embedded in the page. That was used to attack Nicola and - and load malware onto her machine."

#### Spector's Technical Findings

- Microsoft logs documenting the infection

- Archive.org preservation of the malicious website

- Specific timestamps (Nicola infected March 15, 2024 between 6-7:30pm)

- Malware characteristics matching APT29 tradecraft

### The "Scurrilous" Label

The judge used "scurrilous" **three times** in his judgment:

| Paragraph | Context |
|-----------|---------|
| **¶40** | Suggesting Constantine Law altered transcripts: "a scurrilous and unfounded suggestion" |
| **¶83** | APT29/malware allegations: "inherently implausible, incoherent and... scurrilous" |
| **¶89** | Appendix 6 forgery allegation: "thoroughly ridiculous, baseless and scurrilous accusation" |

**"Scurrilous" means:** *making or spreading scandalous claims about someone with the intention of damaging their reputation.*

This is not a neutral judicial finding. This is the judge taking sides, characterizing the Claimant's evidence as malicious defamation rather than evaluating it on its merits.

### What the FBI/DOJ Should Note

#### 1. The Judge Acknowledged APT29 Is Real

He understood it's a Russian state actor. He didn't say APT29 doesn't exist or doesn't operate in this manner.

#### 2. The Judge Didn't Examine the Evidence

> "it is not possible nor sensible in the time available to try to go through the proposed amended statement of case on a line by line basis" (¶82)

He admitted he didn't have time to properly review the evidence.

#### 3. The Judge Refused Forensic Preservation

On June 23, 2025, Spector filed an urgent application for CE-FILE forensic imaging. The judge ignored it for 46 days, then dismissed it as "totally without merit."

#### 4. The Judge Demanded "Expert" Evidence Then Blocked It

He said Spector's evidence wasn't from a "third party expert" — but refused to order the forensic examination that would have produced such evidence.

### The "AI" Dismissal

The judge specifically disparaged Spector's use of AI in analysis:

> "a review, at most, by himself, and sometimes, I think, using some form of AI"

This is significant because:

- AI-assisted malware analysis is **standard practice** in cybersecurity

- Major security firms (CrowdStrike, Mandiant, Microsoft) use AI/ML for threat detection

- The judge treated "AI" as if it diminishes credibility rather than enhances analytical capability

### Cross-Reference: The June 23rd Application

The ex-parte application (Incident #4) specifically sought:

1. **CE-FILE forensic preservation** — would have produced "independent third party" evidence

2. **Independent IT forensics expert** — exactly what the judge later said was missing

3. **48-hour deadline** — urgency reflecting risk of evidence destruction

**The judge dismissed this application as "totally without merit" on August 8, 2025 — then complained Spector didn't have independent expert evidence.**

### Who Benefits from Dismissing APT29 Evidence

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | Not required to explain the malware on particleink.com (company she advised) |
| **APT29/SVR** | UK court rules their tradecraft "implausible" — precedent for future cases |
| **Constantine Law** | Don't have to respond to cyber-espionage allegations |
| **Unknown State Actors** | Demonstrated that UK courts will dismiss state-actor evidence without examination |

### The Pattern

This is not a neutral judge weighing evidence. This is a judge who:

1. **Acknowledged** the seriousness of APT29

2. **Refused** to preserve evidence

3. **Complained** about lack of "expert" evidence

4. **Blocked** the process that would create expert evidence

5. **Dismissed** all allegations as "scurrilous"

6. **Ordered** Spector to pay £48,000

The circular reasoning is not accidental. It's designed to ensure the APT29 evidence can never be properly examined.

---

\newpage

## Incident #8: The Expert Evidence Trap — "Too Early" Then "Where Is It?"

### What Happened

Brian Spector applied for permission to rely on an expert witness report from **Mr. Joseph Lufty** to support his cybersecurity allegations.

**Deputy Master Dray refused the application as "premature."**

Later in the same hearing, the judge complained that Spector didn't have independent expert evidence — and used this absence as grounds for dismissal.

**This is textbook judicial bad faith: block the evidence, then dismiss for lack of evidence.**

### The Expert Report Application (Earlier in Hearing)

#### Deputy Master Dray

> "Now then dealing with the expert report, my - my view is that **the time for expert evidence has not yet arrived**. That will be dealt with at the CCMC. We do not know when the day is but when we get to the CCMC, at that juncture we look at whether or not any expert evidence is required in relation to the claim, etcetera. So, it seems to me that **this application was premature**, and the appropriate order is simply to make no order on the application"

The judge explicitly:

- Ruled expert evidence was "not yet" appropriate

- Called the application "premature"

- Made "no order" on the expert report

### The Complaint About Missing Expert Evidence (Later in Same Hearing)

#### The Claimant tried to remind the judge of his earlier ruling

> **CLAIMANT:** "Yes, to - to the - the point that you made earlier where **it may be too early for - for forensic** ---"
>
> **MASTER DRAY:** "Well, **it may be too early for directions about that but that's not the question**. If you're alleging that this is all being done, you're alleging a very, very serious fraud and - and the like by her and - and malware attacks of a basis."
>
> **MASTER DRAY:** "**Have you had independent people over providing a report to you** to say..."

### The Truncated Evidence Bundle

The judge also received an **incomplete version** of Spector's evidence:

> **CLAIMANT:** "The reports that is - that accompanies the - the BS5 which unfortunately **you've only got 50 pages of**, but I do have a hard copy here which I would love to keep with you and if you have the time you can go through the **100 plus pages of attribution**."

| What Judge Received | What Actually Existed |
|---------------------|----------------------|
| BS5: 50 pages | BS5: 100+ pages of attribution |
| "Only 27 pages" (Judge's words) | Full forensic documentation |

The judge was ruling on **half the evidence** while complaining the evidence was insufficient.

### The Logical Impossibility

| Timeline | Judge's Position |
|----------|------------------|
| **Earlier in hearing** | "Expert evidence is premature — no order on your application" |
| **Later in hearing** | "Have you had independent people providing a report?" |
| **In judgment** | "Not the product of any reliable, independent, third party, expert handiwork" |

#### You cannot simultaneously

1. Block expert evidence as "premature"

2. Demand expert evidence as a condition for proceeding

3. Dismiss for lack of expert evidence

### The Named Expert: Joseph Naghdi (Not "Lufty")

The witness statement dated **June 17, 2025** explicitly identifies the expert:

> **Mr Joseph Naghdi** is Principal Consultant at Computer Forensics Lab, Euro House, 133 Ballards Lane, London N3 1LJ. He has **practised in digital forensics since 2007** and has **given expert evidence in both civil and criminal proceedings**. His full qualifications and Part 35 declaration are set out at pages 8-10 of his report.

**The expert report was already completed** — dated **15 November 2024**, commissioned by Gunnercooke LLP, produced and marked "BS-EX1".

#### The report's conclusions

- "There is a **high likelihood of deliberate tampering** with document metadata, including **impossible ZIP timestamps**"

- "Core document metadata is **missing** from multiple files"

- "Such anomalies are **strongly indicative of manipulation intended to mislead**"

This was not a request for permission to *find* an expert. This was a request for permission to rely on a **completed, signed expert report from a qualified digital forensics professional**.

The judge refused to let Naghdi's report be considered as "premature" — then complained there was no expert analysis.

### The Timeline Proves Bad Faith

| Date | Event |
|------|-------|
| **15 Nov 2024** | Mr Naghdi completes forensic report (BS-EX1) |
| **17 June 2025** | Spector files witness statement + application for permission to rely on Naghdi report |
| **8 August 2025** | Judge rules expert evidence "premature" — **52 days after application filed** |
| **8 August 2025** | Judge complains Spector has no "independent third party expert handiwork" |

**A completed expert report, filed 52 days before the hearing, from a forensics professional practicing since 2007, cannot be "premature."**

### What the Expert Report Found

The Naghdi report corroborated Spector's findings that the Defendant had tampered with documents:

> "The Computer Forensics Report **strongly corroborates** the Claimant's findings; the Defendant's tampering cannot be overlooked."

Specific findings:

- **Impossible ZIP timestamps** — metadata that cannot exist naturally

- **Missing core metadata** — deliberate stripping of document provenance

- **Manipulation intended to mislead** — not accidental corruption

This is exactly the "reliable, independent, third party, expert handiwork" the judge later claimed was missing.

### The June 17th Application

The witness statement explicitly sought:

1. **Permission under CPR 35.4** to rely on Naghdi's expert evidence

2. **Consequential directions** for expert timetable

3. **Confidentiality protection** for the sensitive findings

Spector even explained why he was filing "late":

> "When the Claimant assumed conduct of this litigation in person on 9 June 2025 he believed – mistakenly – that Mr Naghdi's report had already been filed. He discovered on 16 June 2025 that no expert evidence had in fact been lodged with the Court. **He acted promptly: the present application is issued within 1 day of that discovery.**"

### The "Premature" Lie

The judge's claim that expert evidence was "premature" is contradicted by:

1. **The application was filed June 17, 2025** — 52 days before the August 8 hearing

2. **The expert report was dated November 15, 2024** — 9 months before the hearing

3. **The CCMC was fixed for August 8, 2025** — exactly when expert evidence would be needed

4. **The witness statement said**: "Unless permission is granted immediately, it will be impossible to complete the experts' joint statement in time"

The application wasn't premature — it was **urgent precisely because the CCMC was approaching**.

### Cross-Reference: The Judgment

In **paragraph 97** of the August 8, 2025 judgment, Deputy Master Dray wrote:

> "The claimant has produced substantial exhibits which are said by him to prove the alleged hacking of his systems by the defendant, but on analysis, and indeed on his own confession, they amount to, in all instances, a review, at most, by himself, and sometimes, I think, using some form of AI. **What they are not is the product of any reliable, independent, third party, expert handiwork.**"

**But the judge blocked that "expert handiwork" earlier in the same hearing.**

### The Pattern of Evidence Suppression

| Evidence Type | Judge's Action | Result |
|---------------|----------------|--------|
| **Expert witness report (Lufty)** | "Premature" — no order | Expert evidence blocked |
| **CE-FILE forensic preservation** | Ignored 46 days, then TWM | Evidence destruction enabled |
| **BS5 attribution bundle** | Only 50 of 100+ pages received | Incomplete record reviewed |
| **Malware forensics** | Dismissed as "AI" analysis | Technical evidence disparaged |

### Who Benefits from the Expert Evidence Trap

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | Doesn't have to face expert forensic testimony |
| **Constantine Law** | No expert cross-examination of their "glitch" defense |
| **Deputy Master Dray** | Can dismiss for "lack of evidence" without examining evidence |
| **State Actors** | Forensic trail never professionally documented |

### The Procedural Trap

This is a classic **procedural catch-22**:

1. **Stage 1:** File expert evidence → Refused as "premature"

2. **Stage 2:** Present case without expert → Dismissed for lack of expert evidence

3. **Stage 3:** No appeal possible → TWM certification bars further review

The judge created a situation where:

- Expert evidence couldn't be submitted (premature)

- Non-expert evidence was dismissed (not reliable)

- There was no path to present *any* acceptable evidence

**This is not justice. This is evidence laundering.**

---

\newpage

## Incident #9: The Vanishing "27 Pages" Admission

### What Happened

During the August 8, 2025 hearing, Deputy Master Dray **admitted in open court** that he only received truncated evidence bundles:

| Bundle | What Judge Received | What Actually Existed |
|--------|---------------------|----------------------|
| **BS5** | 27 pages | Hundreds of pages |
| **BS5 Attribution** | 50 pages | 100+ pages |

**This admission does not appear anywhere in the judgment.**

The judge then dismissed the case partly for "lack of evidence" — without acknowledging that he only reviewed a fraction of the evidence submitted.

### The Verbatim Exchange (August 8, 2025 Transcript)

#### The Judge Admits He Only Has 27 Pages

> **MASTER DRAY:** "I have got here, 'BS5, confidential, Spector v Severina' and that comprises **27 pages**, so I - you are telling me about a page number in the hundreds so ---"
>
> **CLAIMANT:** "You should have had a BS5 series that was uploaded to you?"
>
> **MASTER DRAY:** "**It has only got 27 pages. That is my point.**"
>
> **CLAIMANT:** "Oh."
>
> **MASTER DRAY:** "**And you are talking about hundreds of pages.**"

#### Spector Points Out the 50-Page Truncation

> **CLAIMANT:** "Yes, it's just a total false mischaracterisation what my friend said. The reports that is - that accompanies the - the BS5 which unfortunately **you've only got 50 pages of**, but I do have a hard copy here which I would love to keep with you and if you have the time you can go through the **100 plus pages of attribution**."

### What the Judge Did Next

Instead of:

- Adjourning to obtain the complete evidence

- Noting in the judgment that he reviewed incomplete bundles

- Accepting the hard copy Spector offered to provide

The judge:

- Proceeded with the hearing on incomplete evidence

- Issued a judgment that doesn't mention the truncation

- Dismissed the case for "lack of evidence"

### What the Judgment Says

**Paragraph 97** (dismissing the cyber-attack evidence):

> "The claimant has produced substantial exhibits which are said by him to prove the alleged hacking of his systems by the defendant, but on analysis, and indeed on his own confession, they amount to, in all instances, a review, at most, by himself, and sometimes, I think, using some form of AI. **What they are not is the product of any reliable, independent, third party, expert handiwork.**"

#### What the judgment does NOT say

- That the judge only received 27 pages of BS5

- That the judge only received 50 pages of the 100+ page attribution evidence

- That Spector offered to provide the complete hard copies

- That the judge declined to review the full evidence

### The Omission Pattern

| What Happened in Court | What Appears in Judgment |
|------------------------|-------------------------|
| Judge: "It has only got 27 pages" | **NOT MENTIONED** |
| Judge: "You are talking about hundreds of pages" | **NOT MENTIONED** |
| Claimant: "you've only got 50 pages of" 100+ | **NOT MENTIONED** |
| Claimant offers hard copy | **NOT MENTIONED** |
| Judge dismisses evidence as insufficient | **YES — ¶97** |

This is **material omission**. The judge acknowledged on the record that he was reviewing truncated evidence, then issued a judgment dismissing that evidence as insufficient — without disclosing the truncation.

### Why This Matters for FBI/DOJ

This demonstrates either:

1. **Evidence Tampering** — Someone truncated the bundles before they reached the judge

2. **Judicial Bad Faith** — Judge knowingly ruled on incomplete evidence without disclosure

3. **Transcript-Judgment Divergence** — What the judge said in court doesn't appear in the approved judgment

### Cross-Reference: CE-FILE Manipulation

The truncation is consistent with the **CE-FILE OCR poisoning attack** documented in Incident #3:

- Documents uploaded to CE-FILE were manipulated

- The judge received corrupted/incomplete versions

- The judge then ruled based on the corrupted/incomplete versions

If the same parties who poisoned the N434 forms also truncated the evidence bundles, this represents a **systematic attack on the evidentiary record**.

### Who Benefits

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | 100+ pages of attribution evidence never reviewed |
| **Constantine Law** | Can claim "no evidence" when evidence was suppressed |
| **Deputy Master Dray** | Can dismiss without addressing the full evidentiary record |
| **State Actors** | Forensic documentation of their tradecraft never examined |

### The Offer Rejected

Spector explicitly offered to provide the hard copy:

> "I do have a hard copy here which I would love to keep with you and if you have the time you can go through the 100 plus pages of attribution."

The judge did not take him up on this offer. The judgment does not mention that this offer was made.

---

\newpage

## Incident #10: Weaponized Malware in Defendant's Legal Evidence

### What Happened

On **June 15, 2025**, Brian Spector filed an urgent application (N244) with the Court, supported by **CONFIDENTIAL EXHIBIT BS3-1** — a 16-page forensic analysis proving that the **Defendant's own legal evidence contained weaponized malware**.

Specifically, **Exhibit LS2** (Lilia Severina's Second Witness Statement, filed May 25, 2021) contained:

- **Three PNG image files with embedded shellcode** — executable malicious code hidden inside screenshot images

- **Microsoft Teams screenshots** showing the Defendant sending malware-laden links to Nicola McNamee on March 15, 2024

- **Metadata manipulation** indicating US Pacific timezone modification (Las Vegas — Kaleidoco headquarters)

**The Court never examined this evidence.** The application was filed 54 days before the August 8, 2025 hearing, yet Judge Dray dismissed all cyber-attack allegations as "scurrilous" without addressing the forensic proof sitting in his case file.

### The Shellcode Analysis

#### Three Malicious PNG Files Identified

| File | Shellcode Indicators | Key Findings |
|------|---------------------|--------------|
| **image-000.png** | 137 indicators | "rb5" C2 (Command & Control) markers; high-confidence malicious payload |
| **image-034.png** | Multiple sequences | Memory manipulation patterns; code injection signatures |
| **converted-049.png** | Payload delivery | Obfuscated execution mechanisms; staged delivery architecture |

#### What the Shellcode Analysis Found

From BS3-1:

> "Presence of shell-code indicators confirmed... The analysis identified **137 shellcode indicators** in image-000.png alone, including **C2 markers** characteristic of **command-and-control infrastructure**."

The technical findings are classified **URGENT - UK JUDICIARY IS IN DANGER** because:

1. **Legal evidence filed with the Court contained malware** — any court clerk, judge, or party opening these files could be compromised

2. **The malware architecture matches APT29 tradecraft** — the same state-sponsored threat actor Spector identified

3. **The Defendant filed this evidence herself** — she cannot claim ignorance of its contents

### The Microsoft Teams Screenshots

Exhibit BS3-1 included screenshots from Microsoft Teams showing:

| Date | Time | Action |
|------|------|--------|
| **March 15, 2024** | Multiple instances | Defendant (Lilia Severina) sends **particleink.com/nfthome** links to Nicola McNamee |
| **March 15, 2024** | 6:00-7:30 PM | Nicola's device infected with malware |

#### The Timeline Proves Delivery

1. Defendant sends link to particleink.com/nfthome (malware delivery site)

2. Nicola clicks link

3. Nicola's machine is compromised

4. Microsoft logs document the infection

5. Archive.org preserves the malicious JavaScript on the landing page

### The Kaleidoco/Particle Ink Connection

**particleink.com** is owned by **Particle Ink LLC**, a subsidiary of **Kaleidoco Inc.**

| Entity | Role | Significance |
|--------|------|--------------|
| **Kaleidoco Inc.** | Parent company | Las Vegas-based; Defendant was "advisor" |
| **Particle Ink LLC** | Subsidiary | Owns particleink.com domain |
| **Cassandra Rosenthal** | Co-CEO of Kaleidoco | **Defendant's witness** — prepared to fly to London to testify |

#### The Connection

- Defendant sends malware links from a company she advises

- That company's co-CEO (Cassandra Rosenthal) is a witness supporting her case

- The malware matches APT29/SVR tradecraft

#### The Audacity of Cassandra Rosenthal

Cassandra Rosenthal is the co-CEO of the company that **hosted the malware used to hack Brian Spector and Nicola McNamee**. Her company's website — particleink.com — delivered the weaponized JavaScript that compromised their systems.

And yet Cassandra Rosenthal was **prepared to fly from Las Vegas to London** to testify on Lilia Severina's behalf, supporting the Defendant's claim that *she* (not Spector) created the intellectual property. She never got the chance — the case was struck out before the final hearing.

This is not merely a conflict of interest. This is a co-conspirator positioning herself as an impartial witness while her own infrastructure was used to execute the cyber-attack. Had the case proceeded to trial, the Court would have accepted her testimony without examining whether her company's malware delivery site had any connection to the alleged state-actor compromise.

### Metadata Manipulation — Las Vegas Connection

#### Timezone Analysis from BS3-1

| Attribute | Value | Significance |
|-----------|-------|--------------|
| **Creation timezone** | UK (GMT/BST) | Document created in UK |
| **Modification timezone** | US Pacific (PST/PDT) | **Modified in Las Vegas** |
| **Kaleidoco HQ** | Las Vegas, Nevada | Matches modification timezone |

This is not an innocent technical artifact. The document was:

1. Created in the UK (where Defendant is based)

2. Modified in Las Vegas (where Kaleidoco is based)

3. Then submitted as legal evidence

### Wayback Machine Corroboration

**Archive.org captured particleink.com/nfthome on March 1, 2024** — proving the malware site existed before Defendant sent the links.

From BS3-1:

> "Wayback Machine confirms: Site existed **March 1, 2024** — 14 days before Defendant sent links to Nicola McNamee"

The malware delivery infrastructure was in place and operational when the Defendant sent the links. This is premeditated delivery, not accidental exposure.

### The June 15, 2025 Application

**N244 Application Notice** sought:

1. **Sealing/confidentiality order** for BS3-1 and BS3-6 (the shellcode analysis)

2. **Interim injunction** restraining disclosure of the malware findings

3. **Proper handling** of evidence that could compromise court systems

The application was filed **54 days before the August 8, 2025 hearing**. It was never addressed.

### The Judge's "Scurrilous" Dismissal — With Proof on File

#### Paragraph 83 of the August 8, 2025 judgment

> "In my judgment such allegations cannot be properly entertained and should not proceed further... these proposed amendments do not disclose a reasonable ground on which to bring the claim, are not supported by contemporaneous documents, are **inherently implausible, incoherent and, in my view, scurrilous.**"

#### But the forensic proof WAS on file

| What Judge Said | What Was Actually Filed |
|-----------------|------------------------|
| "Not supported by contemporaneous documents" | BS3-1 with SHA-256 hashed evidence, dated June 15, 2025 |
| "Inherently implausible" | 137 shellcode indicators in a single PNG |
| "Incoherent" | Clear forensic methodology documented |
| "Scurrilous" | Screenshots of Defendant sending the malware links |

The judge dismissed cyber-attack evidence as "scurrilous" when:

- The Defendant's own exhibit contained shellcode

- The Defendant's Teams messages showed her sending malware links

- The malware site was owned by her business associates

- The forensic analysis was professionally documented

### Chain of Custody Documentation

BS3-1 includes full chain of custody:

| Evidence | SHA-256 Hash | Date Captured |
|----------|--------------|---------------|
| Exhibit LS2 (original) | Documented | May 25, 2021 filing |
| image-000.png extraction | Documented | June 2025 analysis |
| particleink.com archive | Documented | March 1, 2024 Wayback |
| Microsoft Teams logs | Documented | March 15, 2024 |

This isn't speculation. This is forensically preserved, cryptographically verified evidence that the Court refused to examine.

### Why This Is Key Evidence

This evidence ties together **every element** of the conspiracy:

| Element | How BS3-1 Proves It |
|---------|---------------------|
| **State-actor involvement** | Shellcode matches APT29 tradecraft |
| **Defendant's direct involvement** | Teams screenshots show HER sending links |
| **Kaleidoco complicity** | They own the malware delivery site |
| **Evidence destruction motive** | They knew forensics would expose them |
| **Judicial corruption** | Judge dismissed "scurrilous" when proof was on file |

### Who Benefits from Ignoring the Malware Evidence

| Beneficiary | How They Benefit |
|-------------|------------------|
| **Lilia Severina** | Not required to explain why her legal evidence contains shellcode |
| **Kaleidoco Inc.** | Not required to explain why their website delivered malware |
| **Cassandra Rosenthal** | Was willing to testify that Defendant created the IP — while her company hosted the malware that hacked the actual creator |
| **APT29/SVR** | Tradecraft not officially identified; UK court precedent protects future operations |
| **Deputy Master Dray** | Avoids examining evidence that would prove his "scurrilous" dismissal was corrupt |

### The Pattern Completion

This incident completes the evidentiary pattern:

1. **Incident #3** — OCR poisoning attack on CE-FILE

2. **Incident #5** — Pre-prepared defense for "secret" application

3. **Incident #6** — Transcript fraud dismissed as "pathetic"

4. **Incident #7** — APT29 evidence dismissed as "scurrilous"

5. **Incident #8** — Expert evidence blocked then demanded

6. **Incident #10** — **Actual shellcode in Defendant's legal filing proves everything**

The Defendant filed weaponized malware as legal evidence. The Claimant identified it, documented it, filed forensic proof 54 days before the hearing — and the judge dismissed it without examination.

### U.S. Nexus

**Kaleidoco Inc.** is a Nevada corporation with headquarters in **Las Vegas**. The malware delivery site (particleink.com) was hosted on U.S. infrastructure.

This constitutes:

- **18 U.S.C. § 1030** — Computer Fraud and Abuse Act (deploying malware via U.S. systems)

- **18 U.S.C. § 1831** — Economic Espionage Act (state-actor tradecraft targeting U.S. citizen's IP)

- **18 U.S.C. § 1343** — Wire Fraud (malware delivery to facilitate IP theft)

### Forensic Preservation Requests

| Evidence | Custodian | Purpose |
|----------|-----------|---------|
| Original Exhibit LS2 (May 25, 2021) | UK Court Record | Original malware-laden filing |
| particleink.com server logs | Kaleidoco/Particle Ink | Prove malware delivery |
| Microsoft Teams server-side logs | Microsoft Corporation | Corroborate screenshots |
| Archive.org preservation | Internet Archive | Malware page capture |
| Kaleidoco corporate records | Nevada Secretary of State | Ownership chain |

---

\newpage

## Pattern Analysis

### Consistent Beneficiaries

Every documented irregularity benefits the same parties:

| Party | Sched A Removal | Date Falsify | OCR Poison | Evidence Block | Malware Ignore |
|-------|-----------------|--------------|------------|----------------|----------------|
| Lilia Severina | ✔ | ✔ | ✔ | ✔ | ✔ |
| Kaleidoco/Particle Ink | ✔ | — | — | ✔ | ✔ |
| Ali Reza Sinai | — | ✔ | ✔ | — | — |
| Gunnercooke LLP | — | ✔ | — | — | — |
| Constantine Law | ✔ | ✔ | ✔ | ✔ | ✔ |
| APT29/SVR | — | — | ✔ | ✔ | ✔ |

### Indicators of State-Sponsored Operation

The penetration of judicial systems is consistent with documented SVR/APT29 tradecraft:

| Indicator | Present in This Case |
|---------------------|-----------------------------|
| **Legal Infrastructure Compromise** | ✔ Multiple law firms, court system |
| **Record Manipulation** | ✔ CE-FILE, judicial findings |
| **Coordinated Timing** | ✔ Manipulations benefit same parties |
| **Technical Sophistication** | ✔ Exploits legal system knowledge + shellcode in legal filings |
| **Deniability Structure** | ✔ Each incident could be "error" in isolation |
| **Malware Tradecraft** | ✔ Shellcode with C2 markers matching APT29 architecture |
| **U.S. Corporate Infrastructure** | ✔ Kaleidoco (Nevada) owns malware delivery site |
| **Pre-Positioned Witnesses** | ✔ Kaleidoco co-CEO (Rosenthal) is Defendant's witness |

---

\newpage

## Impact on Trade Secret Status

### The "Total Loss" Calculation

The Schedule A removal doesn't disclose technical details (which would destroy trade secret secrecy). Instead, it creates a **different kind of total loss**:

| Loss Type | Description |
|-----------|-------------|
| **Reputational** | Public record shows Spector "lost" — deters partners, investors |
| **Evidentiary** | Future courts won't see Severina's ownership admission |
| **Commercial** | Due diligence searches return negative results |
| **Enforcement** | Can't point to public record of Severina's undertakings |

### Damages Implication

Under the Entire Market Value Rule framework, the Schedule A removal constitutes **additional consequential damages**:

- Cost to correct the public record

- Lost business opportunities due to false public narrative

- Legal fees to prove ownership that was already judicially acknowledged

- Reputational rehabilitation costs

---

\newpage

## Recommended FBI/DOJ Actions

### Immediate Preservation

| Action | Target |
|--------|--------|
| **Preserve CE-FILE logs** | Identify who removed Schedule A and when |
| **Preserve Azure access logs** | Microsoft can provide infrastructure access records |
| **Subpoena HMCTS records** | Original filing vs. what appears on CE-FILE |
| **Subpoena Thomson Reuters** | CE-FILE system administration records |

### Mutual Legal Assistance Treaty (MLAT)

The U.S.-UK MLAT enables FBI to request:

- CE-FILE system logs

- Chancery Division staff communications

- Deputy Master Dray's case file and notes

- Constantine Law's communications with the Court

### Witness Interviews

| Witness | Relevance |
|---------|-----------|
| **Chancery Division Staff** | Who processes CE-FILE uploads for BL-2024-000648 |
| **Thomson Reuters Administrators** | CE-FILE system access and modification logs |
| **Court Clerks** | Who handled the Order between drafting and publication |

---

## Evidence Index

| Evidence ID | Document | Description |
|-------------|----------|-------------|
| [[J1]](#sec-evidence-index) | BL-2024-000648 - Spector v Severina 2.pdf | Order WITH Schedule A (received via email) |
| [[J2]](#sec-evidence-index) | BL-2024-000648 - Sealed Order dated 19 August 2025_from-ce-file.pdf | Order WITHOUT Schedule A (from CE-FILE) |
| [[J3]](#sec-evidence-index) | Portner Law invoices | Proving March 25 engagement date |
| [[J4]](#sec-evidence-index) | Email correspondence | Engagement communications |
| [[J5]](#sec-evidence-index) | Notice of Change of Solicitor | Court filing showing actual date |
| [[J6]](#sec-evidence-index) | Gunnercooke final invoice | Billing through late March |
| [[J7]](#sec-evidence-index) | March 27, 2025 Hearing Transcript | **Key Evidence** — Ms Hobbs states under oath: "25 March" (Page 2, Section F-G) |
| [[J8]](#sec-evidence-index) | August 8, 2025 Judgment | Paragraph 6 falsely states "5 March" |
| [[J9]](#sec-evidence-index) | JH2 (John Hayes 2nd Witness Statement) | Contains malformed N434 PDFs |
| [[J10]](#sec-evidence-index) | Brian Spector's Urgent Ex-Parte Application | Filed to prevent CE-FILE corruption; never addressed until August 8 |
| [[J11]](#sec-evidence-index) | BS4-9: METADATA FINDINGS | Forensic proof: all N434s created June 13, 2025 13:47:04 despite showing different dates |
| [[J12]](#sec-evidence-index) | BS4-12: TECHNICAL NOTE | CE-FILE OCR manipulation analysis — hidden text layer extraction methodology |
| [[J13]](#sec-evidence-index) | BS4-16: PORTNER LAW MISDIRECTION | Email chain proving court sent sealed order to wrong firm (10 Apr 2025) |
| [[J14]](#sec-evidence-index) | Mishcon de Reya N434 (4 Apr 2025) | Proper Notice of Change filed — proves Mishcon on record |
| [[J15]](#sec-evidence-index) | Court email to Portner (10 Apr 2025 10:00) | Elisa Dharmaseelan sends sealed order to ak@portner.co.uk |
| [[J16]](#sec-evidence-index) | Portner response (14 Apr 2025 12:04) | Alex Williams: "direct any further communication to Mishcon De Reya" |
| [[J17]](#sec-evidence-index) | Deputy Master Dray Order (sealed 10 Apr 2025) | Shows "Portner Law Limited" as serving party — **but Portner weren't on record** |
| [[J18]](#sec-evidence-index) | Evidence of CMP invocation without ministerial certificate | National security theatre — no valid certificate ever produced |
| [[J19]](#sec-evidence-index) | DRAFT_ORDER_URGENT_22_06_25.pdf | Ex-parte application demanding CE-FILE preservation + ministerial certificates |
| [[J20]](#sec-evidence-index) | Application Notice dated 23 June 2025 | Formal filing of urgent preservation request |
| [[J21]](#sec-evidence-index) | Witness Statement of Brian Spector (23 June 2025) | Supporting evidence for ex-parte application |
| [[J22]](#sec-evidence-index) | August 8, 2025 Judgment (Full Transcript) | Contains: (1) TWM dismissal ¶42-44, (2) Judge admitting N434 corruption ¶9-12, (3) False "5 March" date ¶6, (4) £48,000 costs order ¶114 |
| [[J23]](#sec-evidence-index) | March 27, 2025 Transcript (Ms Hobbs' Statement) | Counsel states under oath "25 March" — contradicting ¶6 of August 8 judgment |
| [[J24]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (Schumacher "Glitch" Defense) | Pre-prepared defense for "without notice" application — Nicola McNamee catches logical impossibility |
| [[J25]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (McNamee Silenced) | Judge shuts down Nicola: "You are not to say anything" — rather than address contradiction |
| [[J26]](#sec-evidence-index) | August 8, 2025 Judgment ¶77 | Judge acknowledges APT29 is "Russian state actor... involved in criminal enterprise, espionage and hacking" |
| [[J27]](#sec-evidence-index) | August 8, 2025 Judgment ¶83 | Dismisses APT29 evidence as "inherently implausible, incoherent and... scurrilous" |
| [[J28]](#sec-evidence-index) | August 8, 2025 Judgment ¶97 | Rejects evidence because it's "not the product of any reliable, independent, third party, expert handiwork" — but judge blocked forensic preservation that would have produced such evidence |
| [[J29]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (Expert Report Refused) | Judge rules Joseph Lufty expert report application "premature" — makes "no order" |
| [[J30]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (Expert Evidence Demanded) | Same hearing — judge asks "Have you had independent people over providing a report to you?" |
| [[J31]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (BS5 Truncated) | Claimant: "you've only got 50 pages of" the 100+ page attribution evidence |
| [[J32]](#sec-evidence-index) | August 8, 2025 Hearing Transcript (27 Pages Admission) | Judge: "It has only got 27 pages. That is my point." — admits receiving truncated BS5 |
| [[J33]](#sec-evidence-index) | August 8, 2025 Judgment (Omission) | NO MENTION of truncated bundles despite judge acknowledging it in court |
| [[J34]](#sec-evidence-index) | Fourth Witness Statement of Brian Spector (17 June 2025) | Application for permission to rely on expert evidence — filed **52 days before** judge ruled it "premature" |
| [[J35]](#sec-evidence-index) | Joseph Naghdi Expert Report (BS-EX1, 15 Nov 2024) | Completed forensic report finding "high likelihood of deliberate tampering" with "impossible ZIP timestamps" — judge claimed no "third party expert handiwork" existed |
| [[J36]](#sec-evidence-index) | Computer Forensics Lab credentials | Naghdi: Principal Consultant, practicing since 2007, expert evidence in civil AND criminal proceedings |
| [[J37]](#sec-evidence-index) | CONFIDENTIAL EXHIBIT BS3-1 (16 pages, 15 June 2025) | Shellcode analysis of Exhibit LS2 — 137 indicators in image-000.png, C2 markers, memory manipulation patterns |
| [[J38]](#sec-evidence-index) | Exhibit LS2 (Defendant's 2nd Witness Statement, 25 May 2021) | Contains weaponized PNG files with embedded shellcode |
| [[J39]](#sec-evidence-index) | Microsoft Teams Screenshots (within LS2) | Show Defendant sending particleink.com/nfthome links to Nicola McNamee on March 15, 2024 |
| [[J40]](#sec-evidence-index) | Archive.org capture of particleink.com/nfthome (March 1, 2024) | Proves malware delivery site existed before Defendant sent links |
| [[J41]](#sec-evidence-index) | N244 Application Notice (15 June 2025) | Urgent application for sealing of BS3-1/BS3-6 — filed 54 days before August 8 hearing, never addressed |
| [[J42]](#sec-evidence-index) | BS-OPEN Bundle Index (15 June 2025) | Technical determination: "Presence of shell-code indicators confirmed" with SHA-256 hashes |
| [[J43]](#sec-evidence-index) | Kaleidoco Inc. corporate records | Nevada corporation; owns Particle Ink LLC; co-CEO Cassandra Rosenthal is Defendant's witness |
| [[J44]](#sec-evidence-index) | Metadata timezone analysis (BS3-1) | UK creation, US Pacific modification — Las Vegas = Kaleidoco HQ |
| [[J45]](#sec-evidence-index) | August 8, 2025 Judgment ¶83 | Judge dismisses cyber-attack evidence as "scurrilous" — when shellcode proof was on file for 54 days |

---

## Conclusion

The documented judicial irregularities are not isolated errors. They form a **pattern of coordinated manipulation** that:

1. Consistently benefits the same parties (Severina, Kaleidoco, Sinai, Gunnercooke)

2. Suppresses evidence of Spector's IP ownership

3. Creates false public narratives

4. Exploits U.S. infrastructure (Microsoft Azure) to execute the manipulation

This level of institutional penetration is consistent with a **state-sponsored intelligence operation** and warrants FBI Counterintelligence investigation under the Economic Espionage Act framework.
