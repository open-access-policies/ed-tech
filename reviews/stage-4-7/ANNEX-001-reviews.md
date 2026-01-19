# ANNEX-001: FERPA Control Mapping - Consolidated Expert Reviews

**Document Reviewed:** ANNEX-001-ferpa-control-mapping.md
**Review Date:** 2026-01-18
**Review Stages:** 4, 5, 6, 7

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Industry Controls Specialist with 10+ years experience implementing privacy controls in K-12 technology platforms.

### Technical Accuracy for EdTech Context

**Strengths:**
- The mapping accurately identifies the key FERPA provisions relevant to EdTech vendors operating as school officials
- Control references (STU-POL-001, SEC-POL-001, etc.) follow a logical naming convention consistent with enterprise policy frameworks
- The School Official Criteria table (34 CFR 99.31(a)(1)(i)(B)) correctly identifies all four criteria required for vendor designation

**Areas for Consideration:**
- The mapping could benefit from explicit mention of cloud storage considerations under Part 99.35, as most EdTech platforms operate in cloud environments
- Consider adding guidance on handling third-party single sign-on (SSO) integrations, which are common in K-12 environments and have FERPA implications

### Practical Usability of Templates/Checklists

**Strengths:**
- The Verification Checklist (Pre-Contract, Ongoing Operations, Contract Termination) provides actionable items for compliance teams
- Three-phase structure aligns with typical EdTech customer lifecycle management

**Areas for Consideration:**
- Consider adding frequency guidance for ongoing operations checks (quarterly, annually, etc.)
- A "responsible party" column in the checklist would improve accountability tracking

### Completeness of Coverage

**Strengths:**
- Covers all major FERPA parts relevant to EdTech vendors (99.3, 99.10, 99.20, 99.30, 99.31, 99.32, 99.33, 99.35)
- Includes both consent requirements and exceptions

**Gaps Identified:**
- No explicit coverage of 34 CFR 99.7 (annual notification to parents) from the school's perspective
- The studies exception (99.31(a)(6)) could use more detail on what "requires authorization" means operationally

**Stage 4 Assessment:** SATISFACTORY - Minor enhancements recommended

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Attorney with expertise in FERPA, COPPA, and state student privacy laws.

### Legal Compliance Accuracy

**Strengths:**
- Correctly identifies Provider as operating under 34 CFR 99.31(a)(1)(i)(B) school official exception
- Accurately describes the four criteria for school official designation
- Proper treatment of re-disclosure limitations under 99.33

**Areas Requiring Attention:**
- 34 CFR 99.10(b) states 45 days is the maximum, not a standard timeline; consider clarifying this is the outer limit
- The reference to 34 CFR 99.35 in the Security Requirements section should be to 34 CFR 99.31(a)(1)(ii), as 99.35 addresses disclosures to authorized representatives for audit/evaluation purposes
- The "studies exception" reference (99.31(a)(6)) should note this applies to organizations conducting studies for educational agencies, not commercial research

### Citation Correctness

**Verified Citations:**
- 34 CFR 99.3 (Definitions) - Correct
- 34 CFR 99.10 (Right to Inspect) - Correct
- 34 CFR 99.20 (Right to Amendment) - Correct
- 34 CFR 99.30 (Consent Requirements) - Correct
- 34 CFR 99.31 (Exceptions to Consent) - Correct
- 34 CFR 99.32 (Record of Disclosures) - Correct
- 34 CFR 99.33 (Re-disclosure Limitations) - Correct

**Citation Issue:**
- Part 99.35 header should reference 99.31(a)(1)(ii) for security in school official context; 99.35 covers different subject matter

### Regulatory Mapping Completeness

**Complete:**
- School official criteria fully mapped
- Consent and exceptions comprehensively addressed
- Disclosure logging requirements included

**Incomplete:**
- No mention of PTAC (Privacy Technical Assistance Center) guidance documents that interpret FERPA for EdTech
- Consider referencing the 2020 FERPA regulations on disclosures to authorized representatives

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES - Citation correction needed for Part 99.35 section header

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Documentation Editor with expertise in policy and compliance documentation.

### Clarity and Readability

**Strengths:**
- Tables provide clear, scannable format for regulatory mappings
- Consistent use of "FERPA Term," "Citation," and "Implementation" column structure
- Active voice used appropriately in checklist items

**Areas for Improvement:**
- The abbreviation "DPA" is used without initial definition in the document (first appears in Part 99.31 section)
- Some policy references (e.g., "STU-POL-001 Section 3.1") assume reader familiarity; consider adding a legend or brief descriptions
- The phrase "per school designation" in the Directory Information row could be clearer (suggest: "as designated by each school")

### Format and Structure

**Strengths:**
- Logical progression from definitions through operational requirements
- Clear visual separation using horizontal rules
- Appropriate use of markdown headers (##, ###)

**Areas for Improvement:**
- The "Part 99.35 - Security Requirements" section contains only two rows but references control from a different section (99.31); consider reorganizing
- Document Information table could be moved to the beginning for easier reference
- Consider adding a Table of Contents for easier navigation

### Consistent Terminology

**Terminology Audit:**
- "[Company Name]" placeholder used consistently throughout
- "School Official" capitalization is consistent
- "Education records" vs "educational records" - document uses both; standardize to "education records" per FERPA terminology

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES - Terminology standardization and DPA definition needed

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Specialist focusing on policy documentation completeness and accuracy.

### Cross-Reference Accuracy to Policies

**Policy References Validated:**
- PRV-POL-001: FERPA Compliance Policy - Referenced appropriately
- STU-POL-001: Student Data Governance Policy - Multiple valid references
- STU-POL-002: School Official Designation Policy - Core reference for designation
- STU-POL-003: Parental Consent and Rights Policy - Valid for rights sections
- STU-POL-004: Student Data Sharing Policy - Valid for disclosure sections

**Cross-Reference Issues:**
- STU-PROC-003 and STU-PROC-004 are referenced but not included in the References section
- STU-POL-005 is referenced in Part 99.31 (De-identified records) but not in References
- STU-POL-006 is referenced for de-identification but not in References

### Template Usability

**Testing Observations:**
- Checklist items are actionable and checkable
- Pre-Contract checklist could be used during sales/legal review process
- Ongoing Operations checklist suitable for quarterly compliance reviews
- Contract Termination checklist appropriate for offboarding process

**Usability Gaps:**
- No guidance on who should complete the checklist
- No version tracking mechanism within the checklist itself
- Consider adding "Date Completed" field to checklist sections

### Publication Readiness

**Ready:**
- Document structure is complete
- All placeholder fields are clearly marked with bracketed bold text
- Version 1.0 designation appropriate for initial release

**Not Ready:**
- References section incomplete (missing STU-PROC-003, STU-PROC-004, STU-POL-005, STU-POL-006)
- [Date] placeholders need completion instructions or examples
- Part 99.35 section header needs correction per Stage 5 findings

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES - Reference section updates required

---

## Consolidated Findings Summary

### Critical Issues (Must Fix Before Publication)
1. Part 99.35 section header incorrectly references security requirements; should reference 34 CFR 99.31(a)(1)(ii)
2. References section incomplete - missing STU-PROC-003, STU-PROC-004, STU-POL-005, STU-POL-006

### Recommended Improvements (Should Fix)
1. Define "DPA" on first use
2. Standardize terminology: use "education records" consistently (not "educational records")
3. Add frequency guidance to Ongoing Operations checklist
4. Add brief descriptions or legend for policy reference codes

### Optional Enhancements (Consider for Future Versions)
1. Add Table of Contents
2. Include PTAC guidance document references
3. Add responsible party column to checklists
4. Add cloud storage considerations to security section

---

## VERDICT: APPROVED WITH MINOR CHANGES

The ANNEX-001 FERPA Control Mapping document is substantially complete and accurate. The regulatory mappings are comprehensive and the checklist provides practical utility. Two issues require correction before publication: (1) the Part 99.35 section header citation error, and (2) the incomplete References section. These are straightforward corrections that do not require structural changes to the document.

**Recommended Action:** Correct the identified issues and proceed to publication. No additional review cycle required for minor corrections.
