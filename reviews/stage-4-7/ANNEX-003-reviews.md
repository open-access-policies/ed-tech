# ANNEX-003: State Student Privacy Law Matrix - Consolidated Expert Reviews

**Document Reviewed:** ANNEX-003-state-privacy-law-matrix.md
**Review Date:** 2026-01-18
**Review Stages:** 4, 5, 6, 7

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Industry Controls Specialist with 10+ years experience implementing privacy controls in K-12 technology platforms.

### Technical Accuracy for EdTech Context

**Strengths:**
- Covers the most significant state student privacy laws affecting EdTech vendors
- Quick Reference tables (Prohibited Practices, Breach Notification, DPA Special Requirements) provide operational value
- Correctly identifies that most states require written contracts (DPAs) for EdTech vendors

**Areas for Consideration:**
- Consider adding Texas (SB 820 - Texas Student Data Privacy Act) which has significant requirements for EdTech vendors
- Pennsylvania's Act 76 (2014) should be considered for inclusion
- Massachusetts has student data privacy regulations (603 CMR 23.00) that may warrant mention
- Florida's HB 1055 (2023) strengthened student privacy requirements

### Practical Usability of Templates/Checklists

**Strengths:**
- Summary tables enable quick compliance checks across multiple states
- DPA Special Requirements table identifies state-specific contractual needs
- Breach Notification Timelines table supports incident response planning

**Areas for Consideration:**
- Add a "Compliance Checklist by State" section for operational teams
- Consider adding a column for "Last Updated" in the Quick Reference tables to track law amendments
- State Law Tracking section (Recent Updates, Pending Legislation) is helpful but would benefit from a review/update schedule

### Completeness of Coverage

**Strengths:**
- Covers 11 states with specific student privacy laws
- Addresses both prohibitions (no sale, no advertising) and affirmative requirements (contracts, security)
- Includes breach notification requirements which are critical for incident response

**Gaps Identified:**
- Missing several states with recent student privacy legislation (Texas, Florida, Pennsylvania, Maine)
- No coverage of tribal education requirements
- Consider adding federal-state interplay notes (how state laws interact with FERPA/COPPA)
- No guidance on multi-state compliance strategies (meeting highest common denominator)

**Stage 4 Assessment:** SATISFACTORY - Consider adding Texas and Florida; update for recent legislative changes

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Attorney with expertise in FERPA, COPPA, and state student privacy laws.

### Legal Compliance Accuracy

**Strengths:**
- California SOPIPA citations are accurate (Cal. Bus. & Prof. Code sections 22584-22585)
- New York Ed Law 2-d and 8 NYCRR Part 121 correctly identified
- Illinois SOPPA (105 ILCS 85) requirements accurately described

**Areas Requiring Attention:**
- California: Should note that SOPIPA was amended in 2023 (AB 1394) with additional security requirements
- New York: 8 NYCRR 121.9 breach notification has specific timeline requirements (not just "Per 8 NYCRR 121.9")
- Colorado: Breach notification is actually "most expedient time possible" not "30 days" per C.R.S. 24-73-103
- Connecticut: Updated in 2023 with additional requirements under PA 23-56

### Citation Correctness

**Verified Citations:**
- California SOPIPA: Cal. Bus. & Prof. Code sections 22584-22585 - Correct
- New York Ed Law 2-d: NY Educ. Law section 2-d; 8 NYCRR Part 121 - Correct
- Colorado: C.R.S. sections 22-16-101 to 22-16-111 - Correct
- Connecticut: Conn. Gen. Stat. sections 10-234aa to 10-234dd - Correct
- Illinois: 105 ILCS 85 - Correct
- Louisiana: La. R.S. sections 17:3913 to 17:3914 - Correct
- Maryland: Md. Code, Educ. sections 4-131 to 4-133 - Correct
- Nevada: Nev. Rev. Stat. sections 388.281 to 388.296 - Correct
- Oregon: ORS sections 336.184 to 336.196 - Correct
- Virginia: Va. Code sections 22.1-289.02 to 22.1-289.03 - Correct
- Washington: RCW 28A.604 - Correct

**Citation Issues:**
- Colorado breach notification timeline is incorrect (30 days is not accurate)
- Should include citation to general state breach notification laws in addition to education-specific laws

### Regulatory Mapping Completeness

**Complete:**
- Core prohibitions (sale, advertising, profiling) accurately mapped
- Contract requirements correctly identified by state

**Incomplete:**
- Several 2023-2024 state law updates not reflected
- No mention of California Age-Appropriate Design Code Act (AB 2273) which affects EdTech
- Virginia Consumer Data Protection Act (VCDPA) implications for EdTech not addressed
- No discussion of state attorney general enforcement patterns

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES - Colorado breach timeline correction needed; recommend update for recent legislative changes

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Documentation Editor with expertise in policy and compliance documentation.

### Clarity and Readability

**Strengths:**
- Consistent structure for each state (law name, citation, requirements table, DPA requirements)
- Clear use of checkmarks in Quick Reference tables
- Horizontal rules provide good visual separation between states

**Areas for Improvement:**
- Inconsistent use of "section" symbol (some use "section", others use "sections")
- The dash ("--") used in Quick Reference tables is ambiguous; consider using "Not specified" or "N/A"
- Some table cells are empty where information exists (e.g., New York's breach timeline is specified in regulation)

### Format and Structure

**Strengths:**
- Alphabetical organization by state name aids lookup
- Summary tables placed at end provide quick reference
- Document Information section appropriately formatted

**Areas for Improvement:**
- Consider reorganizing to place Quick Reference tables at the beginning for easier access
- State Law Tracking section tables are empty; either populate with examples or add "(To be completed)" note
- Add Table of Contents given document length
- Consider grouping states by region or by requirement type for alternative navigation

### Consistent Terminology

**Terminology Audit:**
- "Student data" vs "student information" vs "personal information" - used interchangeably; should standardize
- "[Company Name]" placeholder used consistently
- "DPA" used without expansion; should define on first use
- "AG" abbreviation used without definition in breach notification section

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES - Terminology standardization and abbreviation definitions needed

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Specialist focusing on policy documentation completeness and accuracy.

### Cross-Reference Accuracy to Policies

**Policy References Validated:**
- PRV-POL-003: State Student Privacy Laws Policy - Referenced, appropriate
- RES-POL-003: Breach Notification (Schools) Policy - Referenced, appropriate
- SEC-POL-001: Security policy - Referenced multiple times, appropriate
- STU-POL-001: Student Data Governance Policy - Referenced, appropriate
- STU-POL-004: Student Data Sharing Policy - Referenced, appropriate
- STU-POL-005: Data Retention and Destruction Policy - Referenced, appropriate

**Cross-Reference Issues:**
- No reference to ANNEX-004 (Student Data Inventory Template) despite Colorado's data inventory requirement citing it
- No reference to ANNEX-005 (School DPA Template) despite DPA requirements being a major focus
- External references (SDPC, FPF) should be verified for current URLs

### Template Usability

**Testing Observations:**
- Matrix format enables state-by-state compliance checking
- Quick Reference tables support rapid decision-making for new state expansions
- Breach Notification Timelines table valuable for incident response procedures

**Usability Gaps:**
- No workflow guidance for how to use the matrix during customer onboarding
- State Law Tracking sections are empty templates - need completion instructions
- No version control guidance for keeping matrix current with legislative changes
- Consider adding "effective date" column for each state law

### Publication Readiness

**Ready:**
- Core content complete for 11 states
- Citations verified as accurate (with noted exception)
- Format consistent and professional

**Not Ready:**
- Colorado breach notification timeline needs correction
- State Law Tracking tables empty - either populate or add guidance
- Missing cross-references to ANNEX-004 and ANNEX-005
- Should define abbreviations (DPA, AG) on first use
- External URLs should be verified current

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES - Data corrections and cross-references needed

---

## Consolidated Findings Summary

### Critical Issues (Must Fix Before Publication)
1. Colorado breach notification timeline is incorrect - should be "most expedient time possible" per C.R.S. 24-73-103, not "30 days"
2. Add cross-references to ANNEX-004 (Student Data Inventory Template) and ANNEX-005 (School DPA Template)
3. Define abbreviations "DPA" and "AG" on first use

### Recommended Improvements (Should Fix)
1. Add or note recent legislative updates (California AB 1394, Connecticut PA 23-56, etc.)
2. New York breach notification timeline should be specific (regulation specifies immediate notification to school, then expedient to affected individuals)
3. Fill in or add instructions for State Law Tracking tables
4. Replace "--" in Quick Reference tables with "Not specified" or "N/A" for clarity
5. Verify external URLs (SDPC, FPF) are current

### Optional Enhancements (Consider for Future Versions)
1. Add Texas, Florida, Pennsylvania, and other states with significant student privacy laws
2. Create state-specific compliance checklists
3. Add effective dates for each state law
4. Include discussion of FERPA/COPPA preemption considerations
5. Add Table of Contents
6. Consider adding enforcement history/patterns section

---

## VERDICT: APPROVED WITH MINOR CHANGES

The ANNEX-003 State Student Privacy Law Matrix provides valuable operational guidance for multi-state EdTech compliance. The document accurately covers 11 key states with student privacy laws and provides useful quick-reference tables. Critical issues requiring correction are: (1) the incorrect Colorado breach notification timeline, (2) missing cross-references to related annexes, and (3) undefined abbreviations. The matrix would benefit from updates reflecting 2023-2024 legislative changes, but this can be addressed in a subsequent version.

**Recommended Action:** Correct the identified data errors and add cross-references, then proceed to publication. Consider scheduling a comprehensive legislative update review within 6 months given the active state legislative landscape.
