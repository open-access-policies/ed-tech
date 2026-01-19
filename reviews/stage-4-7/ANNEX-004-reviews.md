# ANNEX-004: Student Data Inventory Template - Consolidated Expert Reviews

**Document Reviewed:** ANNEX-004-student-data-inventory-template.md
**Review Date:** 2026-01-18
**Review Stages:** 4, 5, 6, 7

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Industry Controls Specialist with 10+ years experience implementing privacy controls in K-12 technology platforms.

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive coverage of data element categories typical in EdTech platforms (identity, contact, educational, performance, usage, technical, demographic)
- Data Sources section (3.1, 3.2) correctly identifies common EdTech integration methods (SIS, Clever, ClassLink, SSO)
- Parent/Guardian data section appropriately separated from student data

**Areas for Consideration:**
- Consider adding "AI/ML derived data" category for platforms using adaptive learning or AI features
- Voice/audio data should be explicitly called out given rise of voice-based EdTech tools
- Biometric data is in Sensitive Data Flags but not in data elements inventory; consider adding to Section 2
- Missing "teacher-created content about students" (e.g., notes, observations) which some platforms store

### Practical Usability of Templates/Checklists

**Strengths:**
- Checkbox format (Yes/No) enables quick completion
- Standard columns (Collected?, Source, Purpose, Retention) cover essential data mapping needs
- Approvals section (8.1) provides clear accountability framework

**Areas for Consideration:**
- "Retention" column values may be inconsistent across data elements; consider providing standardized retention period options
- Add "Legal Basis" column to align with accountability requirements
- Consider adding "Sensitivity Level" or "Classification" column to each data element row
- Third-Party Access table (Section 6.1) has only 3 rows; should indicate expandability

### Completeness of Coverage

**Strengths:**
- Covers major data categories required by FERPA, COPPA, and state laws
- Includes technical data that is often overlooked in privacy assessments
- Data Classification section (4) addresses both regulatory and sensitivity classifications

**Gaps Identified:**
- No section for "data not collected" to document what has been explicitly excluded
- Missing data element: emergency contact information
- Missing data element: photo/profile image
- Accessibility accommodations data (beyond 504/IEP status) should be considered
- No coverage of data derived from student interactions (e.g., time-on-task, click patterns)

**Stage 4 Assessment:** SATISFACTORY - Consider adding AI/ML derived data and additional data elements

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Attorney with expertise in FERPA, COPPA, and state student privacy laws.

### Legal Compliance Accuracy

**Strengths:**
- Data Classification Summary (Section 4.1) correctly distinguishes Education Records (FERPA), Personal Information (COPPA), and Directory Information
- Sensitive Data Flags (Section 4.2) appropriately identifies categories requiring enhanced protections
- Permitted Uses (Section 5.1) aligns with typical DPA authorization structures

**Areas Requiring Attention:**
- "De-identified Data" classification needs clarification - should reference FERPA's de-identification standard (34 CFR 99.31(b)) which requires reasonable determination that student is not identifiable
- Free/reduced lunch status is protected under the Richard B. Russell National School Lunch Act and needs special handling notation
- SSN collection flag should include strong guidance that this is almost never appropriate for EdTech and requires specific authorization
- Directory Information classification should note that this is school-determined and opt-out rights exist

### Citation Correctness

**Observations:**
- Document does not contain regulatory citations (appropriate for a template)
- References to policies are appropriate (STU-POL-001, STU-POL-005, OP-POL-005)

**Recommendations:**
- Consider adding footnote references to relevant regulations for each classification category
- De-identified data standard should reference 34 CFR 99.31(b) explicitly

### Regulatory Mapping Completeness

**Complete:**
- Standard FERPA data elements covered
- COPPA personal information categories addressed
- State-required data inventory elements included (per Colorado and other state requirements)

**Incomplete:**
- No specific call-out for New York Ed Law 2-d required data element disclosure
- No connection to Student Privacy Pledge or other industry commitments
- Should include "lawful basis for processing" to address state laws with accountability requirements

**Stage 5 Assessment:** APPROVED - Minor clarifications recommended but no blocking issues

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Documentation Editor with expertise in policy and compliance documentation.

### Clarity and Readability

**Strengths:**
- Clear section headers with logical numbering (1, 2, 2.1, 2.2, etc.)
- Consistent table format across all data element sections
- Instructions section at beginning provides context for use

**Areas for Improvement:**
- "Collected?" column uses checkbox format but some columns use "Yes/No" text - should be consistent
- Section 2.9 "Other Data Elements" has only 3 rows; add "(add rows as needed)" instruction
- Post-Contract section (7.2) uses "[Number] days" for multiple different timelines; consider distinguishing or adding guidance on reasonable values

### Format and Structure

**Strengths:**
- Logical flow from customer info through data elements to usage to sharing to retention
- Approvals section at end provides workflow completion point
- Document Information table appropriately formatted

**Areas for Improvement:**
- Consider adding a section number index or Table of Contents
- Integration Details table (3.2) could be merged with Source Systems table (3.1) to reduce redundancy
- Revision History table (8.2) is empty; add example entry or "(To be completed)" note

### Consistent Terminology

**Terminology Audit:**
- "Student Data" vs "student data" - capitalization inconsistent; recommend lowercase except when defined term
- "[Company Name]" placeholder used consistently
- "School/District" used consistently
- "PII" used once without definition (Section 4.1 "Not PII"); expand on first use

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES - Minor formatting and terminology consistency improvements recommended

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Specialist focusing on policy documentation completeness and accuracy.

### Cross-Reference Accuracy to Policies

**Policy References Validated:**
- STU-POL-001: Student Data Governance Policy - Referenced, appropriate
- STU-POL-005: Data Retention and Destruction Policy - Referenced, appropriate for retention section
- OP-POL-005: School District Onboarding Policy - Referenced, appropriate for customer context

**Cross-Reference Issues:**
- No reference to ANNEX-001 (FERPA Control Mapping) despite FERPA classification being used
- No reference to ANNEX-002 (COPPA Compliance Checklist) despite COPPA classification being used
- Section 4.2 Sensitive Data Flags references "Additional Protections" but doesn't point to specific policies

### Template Usability

**Testing Observations:**
- Template can be completed systematically section-by-section
- Checkbox format accelerates data element documentation
- Customer Information section provides good context-setting for the inventory

**Usability Gaps:**
- No guidance on how often to update the inventory (annual? per change?)
- No workflow for handling changes (who initiates update, approval process)
- "Purpose" and "Retention" columns are free-text but would benefit from suggested values or picklists
- Third-Party Access and School-Directed Integrations sections could use example entries

### Publication Readiness

**Ready:**
- Template structure complete and logical
- All 8 sections present and appropriately organized
- Placeholder fields clearly marked with brackets

**Not Ready:**
- Add cross-references to ANNEX-001 and ANNEX-002 in References section
- Add guidance on update frequency in Instructions section
- Define "PII" on first use
- Consider adding example or guidance note to empty Revision History table
- Source Systems and Integration Details tables could be consolidated or better differentiated

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES - Add cross-references and minor usability improvements

---

## Consolidated Findings Summary

### Critical Issues (Must Fix Before Publication)
None - No critical issues identified. Template is structurally sound.

### Recommended Improvements (Should Fix)
1. Add cross-references to ANNEX-001 (FERPA Control Mapping) and ANNEX-002 (COPPA Compliance Checklist) in References section
2. Define "PII" on first use (Section 4.1)
3. Add guidance on inventory update frequency in Instructions section
4. Add reference to FERPA de-identification standard (34 CFR 99.31(b)) in Section 4.1 for De-identified Data classification
5. Add note to Sensitive Data Flags that SSN collection is rarely appropriate for EdTech

### Optional Enhancements (Consider for Future Versions)
1. Add "AI/ML derived data" category for adaptive learning platforms
2. Add "Data Not Collected" section to document explicit exclusions
3. Add data elements: emergency contact, photo/profile image, voice/audio
4. Provide suggested values or picklists for Purpose and Retention columns
5. Add example entries to Third-Party Access and School-Directed Integrations tables
6. Consider adding "Legal Basis" column to align with emerging accountability requirements
7. Consolidate or better differentiate Source Systems (3.1) and Integration Details (3.2) tables

---

## VERDICT: APPROVED WITH MINOR CHANGES

The ANNEX-004 Student Data Inventory Template is well-designed and comprehensive for its purpose. The template covers standard data elements collected by EdTech platforms and provides a systematic approach to data inventory documentation. No critical issues were identified. The recommended improvements focus on enhancing cross-references to related documents, adding minor clarifications, and improving usability guidance. The template is suitable for immediate use with minor refinements.

**Recommended Action:** Add the recommended cross-references and clarifications, then proceed to publication. The template provides strong operational value for EdTech data governance.
