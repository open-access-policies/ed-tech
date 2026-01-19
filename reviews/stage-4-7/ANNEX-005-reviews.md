# ANNEX-005: School Data Processing Agreement Template - Consolidated Expert Reviews

**Document Reviewed:** ANNEX-005-school-dpa-template.md
**Review Date:** 2026-01-18
**Review Stages:** 4, 5, 6, 7

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Industry Controls Specialist with 10+ years experience implementing privacy controls in K-12 technology platforms.

### Technical Accuracy for EdTech Context

**Strengths:**
- Article 2 (School Official Designation) correctly addresses all four FERPA criteria for school official status
- Security provisions (Article 5) align with industry standards (TLS 1.2+, encryption at rest, SOC 2)
- Subcontractor provisions (Article 6) address common EdTech supply chain concerns

**Areas for Consideration:**
- Consider adding provisions for SIS/rostering integration requirements (many districts require Clever/ClassLink compatibility)
- Add language addressing multi-tenant architecture considerations (data segregation between schools/districts)
- Missing provisions for service level agreements (SLAs) for availability, which districts often require
- Consider adding "Accessibility" section addressing Section 508/WCAG compliance, increasingly required by schools

### Practical Usability of Templates/Checklists

**Strengths:**
- Clear article structure enables easy navigation
- Exhibits (A-D) provide modular attachment points for customization
- State-specific addenda checklist (Exhibit D) addresses multi-state compliance

**Areas for Consideration:**
- Add guidance notes in brackets indicating which sections are commonly negotiated
- Include alternative language options for contentious provisions (e.g., liability, indemnification)
- Provide suggested values for "[Number]" placeholders based on industry norms
- Consider adding an implementation checklist for post-signature operational setup

### Completeness of Coverage

**Strengths:**
- Covers all essential DPA components: definitions, data use, security, breach notification, retention, rights, audit
- Prohibited uses (Article 4) comprehensively address common state law requirements
- Parent/student rights support (Article 9) aligns with FERPA requirements

**Gaps Identified:**
- No liability/indemnification provisions (standard in commercial contracts)
- No limitation of liability clause
- Missing "Dispute Resolution" section
- No provisions for service modifications or updates that may affect data handling
- Missing "Insurance Requirements" section often required by larger districts

**Stage 4 Assessment:** SATISFACTORY - Consider adding liability, dispute resolution, and SLA provisions

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Attorney with expertise in FERPA, COPPA, and state student privacy laws.

### Legal Compliance Accuracy

**Strengths:**
- Article 2 (School Official Designation) correctly implements 34 CFR 99.31(a)(1)(i)(B) criteria
- Definition of "Student Data" (1.1) properly combines FERPA and COPPA definitions
- "Legitimate Educational Interest" definition (1.5) aligns with FERPA regulatory language
- Article 4 prohibitions align with SOPIPA, SOPPA, and other state law requirements

**Areas Requiring Attention:**
- Article 7.2 (Breach Notification) uses "[Number, e.g., 24] hours" but many state laws have specific requirements; consider making this "no later than 72 hours" as a baseline with state-specific addenda for shorter periods
- Article 8.2 mentions deletion "except as required by law" but should clarify that Provider may retain de-identified data per school authorization
- Article 9.3 states Provider does not contact parents "without School's authorization" but FERPA does not prohibit direct contact; clarify this is a contractual choice
- Consider adding statement about Provider's independent COPPA compliance (not relying solely on school consent)

### Citation Correctness

**Verified Citations:**
- 34 CFR section 99.3 (definitions) - Correctly referenced in Article 1
- 34 CFR section 99.31(a)(1)(i)(B) (school official criteria) - Correctly referenced in Article 1
- 16 CFR section 312.2 (COPPA definitions) - Correctly referenced in Article 1

**Recommendations:**
- Consider adding citation to 34 CFR 99.33 in Article 4.4 (re-disclosure prohibition)
- Article 12.1 should reference specific state laws that apply, or include mechanism for identifying applicable laws

### Regulatory Mapping Completeness

**Complete:**
- FERPA school official criteria fully addressed
- COPPA school consent model implicitly covered through educational purpose focus
- Common state law requirements (no sale, no advertising, no profiling) addressed in Article 4

**Incomplete:**
- No explicit mention of PPRA (Protection of Pupil Rights Amendment) which may apply to surveys/assessments
- No specific IDEA/Section 504 considerations for special education data
- Consider adding statement about compliance with applicable state student privacy laws (blanket coverage)

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES - Breach notification timeline and de-identification retention clarifications recommended

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Documentation Editor with expertise in policy and compliance documentation.

### Clarity and Readability

**Strengths:**
- Article/section numbering is clear and consistent
- Recitals provide good context for the agreement
- Defined terms are capitalized consistently throughout

**Areas for Improvement:**
- Article 7.2 bullet points would benefit from numbered sub-items for clarity
- Some articles mix SHALL and should language; standardize to "shall" for consistency
- Article 6.3 "work in good faith" is vague; consider more specific resolution mechanism
- Signature block could include email addresses for notice purposes

### Format and Structure

**Strengths:**
- Logical article progression from definitions through operations to termination
- Exhibits clearly separated and labeled
- Document Information table at end is appropriate

**Areas for Improvement:**
- Consider adding a cover page with key terms summary (effective date, parties, products)
- Article 11 (Term and Termination) could be earlier in the document per legal convention
- Missing article numbers after 12 (13, 14...) should provisions be added; consider reserving
- Exhibit B could use more detailed data element categories consistent with ANNEX-004

### Consistent Terminology

**Terminology Audit:**
- "Student Data" capitalized and used consistently as defined term
- "Provider" and "School" used consistently
- "Services" capitalized appropriately
- "DPA" used once in introductory material; ensure consistency
- "Educational Agency" used in Recitals but "School" used thereafter; clarify or standardize

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES - Minor terminology standardization and structure improvements recommended

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Specialist focusing on policy documentation completeness and accuracy.

### Cross-Reference Accuracy to Policies

**Policy References Validated:**
- STU-POL-002: School Official Designation Policy - Referenced, appropriate
- OP-POL-005: School District Onboarding Policy - Referenced, appropriate
- PRV-POL-003: State Privacy Laws Policy - Referenced, appropriate

**Cross-Reference Issues:**
- No reference to ANNEX-004 (Student Data Inventory Template) despite Exhibit B covering similar content
- No reference to RES-POL-003 (Breach Notification) despite Article 7 covering breach procedures
- SEC-POL-001 is mentioned in Usage Notes context but not in References

### Template Usability

**Testing Observations:**
- Template structure follows standard contract format, enabling legal team use
- Exhibits provide clear attachment points for customization
- State-specific addenda checklist (Exhibit D) supports multi-state operations

**Usability Gaps:**
- No guidance on which provisions are typically non-negotiable vs. flexible
- Exhibit A (Services Description) has no structure or suggested content
- Exhibit B data elements don't align exactly with ANNEX-004 categories
- Exhibit C (Subcontractor List) would benefit from additional columns (data access level, location justification)
- No version tracking for template itself separate from customer execution

### Publication Readiness

**Ready:**
- Core DPA structure complete with all essential articles
- Defined terms properly established
- Exhibits framework in place
- Legal language appropriate for commercial use

**Not Ready:**
- Add cross-references to ANNEX-004, RES-POL-003, and SEC-POL-001
- Align Exhibit B categories with ANNEX-004 for consistency
- Consider adding guidance notes for template users
- Clarify "Educational Agency" vs "School" terminology in Recitals
- Add "[Company Name]" Owner to Document Information (currently shows "Legal/Compliance" which is generic)

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES - Cross-reference additions and exhibit alignment needed

---

## Consolidated Findings Summary

### Critical Issues (Must Fix Before Publication)
None - No critical legal issues identified. Template provides sound legal foundation.

### Recommended Improvements (Should Fix)
1. Add cross-references to ANNEX-004 (Student Data Inventory Template), RES-POL-003 (Breach Notification Policy), and SEC-POL-001 (Security Policy) in References section
2. Align Exhibit B data element categories with ANNEX-004 structure for consistency
3. Standardize "Educational Agency" vs "School" terminology - recommend using "School" or "LEA" consistently
4. Clarify Article 8.2 regarding retention of de-identified data post-termination
5. Add baseline breach notification timeline (recommend 72 hours) with note about state-specific requirements

### Optional Enhancements (Consider for Future Versions)
1. Add Liability/Indemnification article (standard commercial provision)
2. Add Dispute Resolution article
3. Add Service Level Agreement provisions or reference to separate SLA
4. Add Insurance Requirements section
5. Expand Exhibit A with structured services description format
6. Add columns to Exhibit C: data access level, location justification, last audit date
7. Include alternative language options for commonly negotiated provisions
8. Add accessibility compliance provision (Section 508/WCAG)
9. Add PPRA acknowledgment for survey/assessment tools

---

## VERDICT: APPROVED WITH MINOR CHANGES

The ANNEX-005 School Data Processing Agreement Template provides a solid legal framework for EdTech vendor-school relationships. The template correctly addresses FERPA school official requirements, COPPA considerations, and common state law prohibitions. No critical legal deficiencies were identified. The recommended improvements focus on cross-reference alignment, terminology consistency, and optional commercial provisions that may be desired for enterprise customers. The template is suitable for use with schools and districts, with recognition that customer-provided DPAs or state standard agreements may supersede this template.

**Recommended Action:** Add the recommended cross-references and clarifications, then proceed to publication. Consider developing state-specific addenda templates as companion documents.
