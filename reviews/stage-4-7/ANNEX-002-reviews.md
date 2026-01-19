# ANNEX-002: COPPA Compliance Checklist - Consolidated Expert Reviews

**Document Reviewed:** ANNEX-002-coppa-compliance-checklist.md
**Review Date:** 2026-01-18
**Review Stages:** 4, 5, 6, 7

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Industry Controls Specialist with 10+ years experience implementing privacy controls in K-12 technology platforms.

### Technical Accuracy for EdTech Context

**Strengths:**
- Section 1 (Applicability Determination) correctly captures the key factors from the FTC's guidance on "directed to children" analysis
- School consent model in Section 3.1 accurately reflects the FTC's guidance on school authorization for COPPA consent
- The personal information inventory (Section 4.2) covers all COPPA-defined personal information categories including persistent identifiers

**Areas for Consideration:**
- Consider adding specific guidance on handling teacher vs. student accounts, as many EdTech platforms have mixed user types
- The "actual knowledge" determination (Section 1.2) could include guidance on age-gating mechanisms and when they create actual knowledge
- Add consideration for classroom/group accounts where individual children are not identified

### Practical Usability of Templates/Checklists

**Strengths:**
- Checkbox format enables systematic compliance verification
- Section 10 (Overall Compliance Status) provides clear summary dashboard
- Remediation Items table enables action tracking

**Areas for Consideration:**
- The checklist is comprehensive but lengthy; consider creating a "quick assessment" version for initial screening
- Add guidance on assessment frequency (annual, per product, per release, etc.)
- Service Provider Inventory table (Section 9.2) should include more rows or indicate it's expandable

### Completeness of Coverage

**Strengths:**
- Covers all major COPPA sections (312.4 through 312.11)
- Includes both direct parental consent and school consent models
- Security and retention requirements appropriately addressed

**Gaps Identified:**
- No mention of the FTC's safe harbor programs (CARU, PRIVO, etc.) which are relevant for EdTech companies
- Missing guidance on COPPA's audio/video file considerations, which are increasingly relevant for EdTech
- No coverage of "mixed audience" websites and the age-screening requirements

**Stage 4 Assessment:** SATISFACTORY - Comprehensive but consider adding safe harbor program references

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Attorney with expertise in FERPA, COPPA, and state student privacy laws.

### Legal Compliance Accuracy

**Strengths:**
- Correctly identifies that school consent requires: (1) educational purpose, (2) school benefit, and (3) no commercial use unrelated to education
- Prohibited practices list (Section 5.1) accurately captures COPPA restrictions
- Parental rights (Section 6) correctly reflects 16 CFR 312.6 requirements

**Areas Requiring Attention:**
- Section 3.2 (Direct Parental Consent) lists "Email-plus" as "(internal only)" but should clarify this is only permitted for internal operations per 16 CFR 312.5(b)(2)(ii), not for disclosures
- The verifiable parental consent methods should note that "knowledge-based authentication" has specific requirements under 312.5(b)(2)(v)
- Section 8 references 16 CFR 312.10 but should clarify this is about collection limitation, not just retention

### Citation Correctness

**Verified Citations:**
- 16 CFR 312.4 (Notice Requirements) - Correct
- 16 CFR 312.5 (Consent Requirements) - Correct
- 16 CFR 312.6 (Parental Rights) - Correct
- 16 CFR 312.7 (Collection Limitations) - Correct
- 16 CFR 312.8 (Security Requirements) - Correct
- 16 CFR 312.10 (Retention Limitations) - Correct but should also reference 16 CFR 312.3(e) for data minimization
- 16 CFR 312.11 (Service Provider Oversight) - Correct but this section is actually about "safe harbor" programs; service provider requirements are in 312.8

**Citation Issue:**
- Section 9 header references "16 CFR 312.11" but 312.11 covers safe harbor programs; service provider requirements are primarily in 312.8 (confidentiality and security) and 312.5 (operator liability for third parties)

### Regulatory Mapping Completeness

**Complete:**
- Notice requirements thoroughly addressed
- Consent mechanisms properly enumerated
- Parental rights comprehensively covered

**Incomplete:**
- No reference to the 2013 COPPA Rule amendments that expanded "personal information" definition
- Missing reference to FTC COPPA FAQ guidance (published 2023 update)
- Safe harbor program option not mentioned (312.11)

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES - Citation correction needed for Section 9 header

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Documentation Editor with expertise in policy and compliance documentation.

### Clarity and Readability

**Strengths:**
- Consistent use of checkbox format throughout
- Clear section numbering (1.1, 1.2, 2.1, etc.)
- Tables are well-formatted with appropriate columns

**Areas for Improvement:**
- Section 3.1 "School benefits for educational purposes" is grammatically awkward; suggest "School receives educational benefit from services"
- In Section 4.2, "Social Security number" should clarify this is almost never collected in EdTech contexts (to avoid alarm)
- Section 5.1 uses "VIOLATION" in capitals which may be unnecessarily alarming for a self-assessment tool

### Format and Structure

**Strengths:**
- Logical flow from applicability through specific requirements to summary
- Document Information section appropriately placed at end
- Remediation Items table provides actionable output

**Areas for Improvement:**
- Consider adding a "Section 0: Instructions" at the beginning explaining how to use the checklist
- The "Assessment" field in Section 10 uses different formats (Compliant/Needs Work vs. Yes/No elsewhere)
- Add page numbers or section quick-links for a document this length

### Consistent Terminology

**Terminology Audit:**
- "Personal information" vs "personal data" - document uses "personal information" consistently (correct per COPPA)
- "[Company Name]" placeholder used consistently
- "Parent" vs "Parent/Guardian" - should standardize; recommend "parent" per COPPA language with note that it includes guardians

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES - Minor grammatical and formatting improvements recommended

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Specialist focusing on policy documentation completeness and accuracy.

### Cross-Reference Accuracy to Policies

**Policy References Validated:**
- SEC-POL-001: Security policy - Referenced in Section 7, appropriate
- PRV-POL-002: COPPA Compliance Policy - Referenced in References section, appropriate
- STU-POL-003: Parental Consent and Rights Policy - Referenced in References section, appropriate

**Cross-Reference Issues:**
- Section 3.1 references "DPA" but the DPA template (ANNEX-005) is not referenced
- No cross-reference to ANNEX-001 (FERPA Control Mapping) despite FERPA/COPPA overlap in school contexts
- Service provider oversight section should reference STU-POL-004 (Student Data Sharing Policy) for subcontractor requirements

### Template Usability

**Testing Observations:**
- Checklist can be completed in a single session (estimated 30-60 minutes for initial assessment)
- Checkbox format works well for compliance tracking
- "Evidence/Notes" and "Notes" columns provide space for documentation

**Usability Gaps:**
- No clear guidance on who should complete the assessment (Privacy Officer? Product team? Legal?)
- Response times in Section 6.1 use "[Number] days" placeholder but no guidance on reasonable timeframes
- Service Provider Inventory only has 3 rows; should indicate expandability or use "add rows as needed"

### Publication Readiness

**Ready:**
- Document structure complete with all 10 sections
- Placeholder fields clearly marked
- Version 1.0 appropriate for initial release

**Not Ready:**
- References section should include ANNEX-005 (DPA Template)
- FTC COPPA FAQs reference should include URL or publication date
- Section 9 header citation needs correction per Stage 5 findings
- Consider adding "Instructions" section before Section 1

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES - Reference additions and citation correction required

---

## Consolidated Findings Summary

### Critical Issues (Must Fix Before Publication)
1. Section 9 header incorrectly cites 16 CFR 312.11 (safe harbor programs); service provider requirements are primarily in 312.8
2. Add cross-reference to ANNEX-005 (School DPA Template) in References

### Recommended Improvements (Should Fix)
1. Add URL or publication date for FTC COPPA FAQs reference
2. Clarify "Email-plus" is for internal operations only per 312.5(b)(2)(ii)
3. Standardize "parent" terminology with note about guardian inclusion
4. Reword Section 3.1 criterion: "School benefits for educational purposes" to improve clarity

### Optional Enhancements (Consider for Future Versions)
1. Add reference to FTC safe harbor programs (312.11) as compliance option
2. Create abbreviated "quick assessment" version for initial screening
3. Add guidance on audio/video file handling under COPPA
4. Include link to 2023 FTC COPPA FAQ update

---

## VERDICT: APPROVED WITH MINOR CHANGES

The ANNEX-002 COPPA Compliance Checklist is comprehensive and well-structured for practical use. The checklist covers all major COPPA requirements and provides a systematic approach to compliance verification. Two issues require correction: (1) the Section 9 citation error regarding service provider oversight, and (2) the missing cross-reference to the DPA template. These corrections are straightforward and do not require restructuring.

**Recommended Action:** Correct the citation and add the reference, then proceed to publication. The checklist is ready for operational use with these minor modifications.
