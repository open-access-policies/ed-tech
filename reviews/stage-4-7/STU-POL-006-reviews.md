# STU-POL-006: De-identification Policy - Consolidated Reviews

**Policy Title:** De-identification Policy
**Policy ID:** STU-POL-006
**Review Date:** 2026-01-18

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Security and Operations Subject Matter Expert

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive direct identifier removal table (Section 3.2.1) covers all common EdTech data elements
- Indirect identifier treatment table (Section 3.2.2) addresses quasi-identifier combinations common in educational data
- Aggregation thresholds (Section 3.1.3) follow NCES best practices for educational statistics
- Clear distinction between tokenization and pseudonymization with explicit warning that pseudonymized data is NOT de-identified

**Areas of Concern:**
- No mention of differential privacy techniques despite brief reference in Section 3.7.2 (longitudinal data)
- IP address truncation to /24 network may be insufficient in some contexts (still identifies organization)
- Device identifiers hashing "with salt" mentioned but no guidance on salt management or rotation
- No guidance on de-identification of AI/ML model outputs or embeddings derived from student data

### Practical Implementation Feasibility

**Strengths:**
- De-identification process workflow (Section 3.3) provides clear approval and execution steps
- Verification requirements (Section 3.3.3) include residual identifier review and risk assessment
- Risk assessment factors (Section 3.2.3) provide practical guidance for implementation
- De-identification log requirements (Section 3.6.1) support audit and compliance needs

**Concerns:**
- Cell size thresholds (10 for most, 5 for cross-tabulations) may be overly prescriptive for all contexts
- "Authorized personnel with de-identification training" requirement lacks specificity on training content
- Re-identification risk assessment process could benefit from quantitative guidance (k-anonymity, l-diversity metrics)

### Integration with Existing EdTech Operations

**Observations:**
- Clear integration with Data Science/Analytics team responsibilities
- Cross-reference to STU-PROC-006 (De-identification Procedure) suggests operational procedures exist
- Engineering responsibility for tools and technical controls is appropriate

**Recommendations:**
1. Add guidance on de-identifying AI/ML training data and model outputs
2. Include quantitative de-identification standards (k-anonymity >= X, l-diversity)
3. Specify de-identification training curriculum requirements
4. Add differential privacy guidance for learning analytics use cases
5. Consider graduated thresholds based on data sensitivity rather than fixed values

**Stage 4 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Regulatory Attorney / Compliance Specialist

### Legal Compliance Accuracy

**FERPA Analysis:**
- Section 3.1.1 correctly states FERPA de-identification standard: PII removed, recipient cannot reasonably identify
- FERPA PII list (Section 3.1.1) accurately reflects 34 CFR 99.3 definition
- "Reasonable determination" standard correctly referenced from FERPA guidance
- Important note that information requested by someone who reasonably knows student identity still counts as PII

**COPPA Analysis:**
- Section 3.1.2 correctly references 16 CFR 312.2 for personal information definition
- Standard that no reasonable possibility of re-identification aligns with FTC interpretation

**Additional Considerations:**
- Policy correctly notes that properly de-identified data is NOT subject to FERPA/COPPA
- Re-identification prohibition (Section 3.5) aligns with best practices and some state requirements

**Concerns:**
- No explicit reference to the DOE PTAC (Privacy Technical Assistance Center) guidance on de-identification
- The policy does not address the "mosaic effect" where multiple de-identified datasets could be combined for re-identification
- No mention of the FERPA "reasonable determination" documentation requirement

### Citation Correctness

| Citation | Accuracy | Notes |
|----------|----------|-------|
| 34 CFR 99.31(b)(1) | Correct | PII removal for de-identification |
| 16 CFR 312.2 | Correct | COPPA de-identification standard |
| NCES guidance | Correct | Statistical disclosure controls reference |
| SOPIPA | Correct | Referenced for sale prohibition context |

### State Law Coverage Adequacy

**Assessment:**
- State laws mentioned in context of sale prohibition (referencing STU-POL-004)
- No state-specific de-identification requirements enumerated
- Some states (California) have specific de-identification standards for research

**Recommendations:**
1. Add reference to DOE PTAC de-identification guidance
2. Address mosaic effect risk in quasi-identifier analysis
3. Note that some state laws have specific de-identification definitions that may differ
4. Add documentation requirement for "reasonable determination" per FERPA

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Writer / Documentation Standards Specialist

### Clarity and Readability

**Strengths:**
- Excellent table format for direct identifier removal (Section 3.2.1) with clear method per identifier type
- Aggregation thresholds table (Section 3.1.3) provides actionable numeric standards
- Definitions section (Section 5) is comprehensive with clear distinctions between similar concepts

**Concerns:**
- Section 3.2.3 (Quasi-Identifier Analysis) has a bulleted list followed by another bulleted list without clear separation
- The term "small cell suppression" is used before it's defined in Section 5
- "Differential privacy" mentioned in Section 3.7.2 without definition or explanation

### Consistent Terminology

**Observations:**
- "De-identification" vs. "deidentification" - consistently hyphenated throughout (correct)
- "Pseudonymization" properly distinguished from de-identification
- "Direct identifier" and "indirect identifier" used consistently

**Issues Identified:**
- "Personally identifiable information (PII)" and "personal information" both used - FERPA vs. COPPA terminology is correct but could be clarified for readers
- "Re-identification" hyphenation is consistent

### Format and Structure Compliance

**Strengths:**
- Consistent section numbering and hierarchy
- Tables used extensively and effectively
- Comprehensive definitions section

**Recommendations:**
1. Add brief definition or explanation of "differential privacy" in Section 3.7.2
2. Define "small cell suppression" earlier or add forward reference to definitions
3. Clarify FERPA "PII" vs. COPPA "personal information" terminology distinction
4. Add visual separator between quasi-identifier examples and risk assessment factors lists

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Analyst / Compliance Auditor

### Cross-Reference Accuracy

| Referenced Document | Exists/Verified | Notes |
|---------------------|-----------------|-------|
| STU-POL-001: Student Data Governance Policy | Yes | Reviewed in this batch |
| STU-POL-004: Student Data Sharing Policy | Yes | Reviewed in this batch |
| STU-POL-005: Data Retention and Destruction Policy | Yes | Reviewed in this batch |
| SEC-POL-002: Data Classification Policy | Not reviewed | External reference |
| STU-PROC-006: De-identification Procedure | Not reviewed | Procedure document |

### Template Completeness

**Placeholder Audit:**
- [Company Name]: Used consistently throughout (15+ instances)
- [Number, e.g., 10]: Used for aggregation thresholds
- [Number, e.g., 5]: Used for cross-tabulation thresholds
- [Number, e.g., 3] years: Used for documentation retention
- [Role Title]: Used in Policy Owner field
- [Date]: Used in review date fields

**All placeholders properly formatted and consistently applied.**

**Missing Elements:**
- No version number or revision history
- No document control information
- No effective date

### Publication Readiness

**Checklist:**
- [x] All sections complete with substantive content
- [x] Cross-references use consistent policy ID format
- [x] Tables render correctly in markdown
- [x] Regulatory citations formatted consistently
- [x] De-identification methods comprehensive
- [x] Re-identification prohibition clearly stated
- [x] Definitions section comprehensive
- [ ] Version control metadata present
- [ ] Effective date specified
- [x] Policy owner role defined
- [x] Review cycle defined with appropriate triggers

**Recommendations:**
1. Add document version number and revision history
2. Verify STU-PROC-006 (De-identification Procedure) exists and aligns
3. Add effective date placeholder
4. Consider adding example de-identification scenarios or case studies

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES

---

## Consolidated Verdict

**VERDICT: APPROVED WITH MINOR CHANGES**

### Summary of Required Changes

1. **Add version control metadata** - version number, revision history, effective date
2. **Define "differential privacy"** in Section 3.7.2 or add to definitions
3. **Add DOE PTAC reference** for de-identification guidance
4. **Clarify PII vs. personal information** terminology (FERPA vs. COPPA)
5. **Address mosaic effect risk** in quasi-identifier analysis section
6. **Add quantitative standards** reference (k-anonymity, l-diversity) for technical implementations

### Commendations

- Outstanding comprehensive coverage of de-identification techniques and standards
- Excellent distinction between tokenization and pseudonymization with clear warning about pseudonymized data status
- Strong aggregation threshold guidance following NCES best practices
- Comprehensive direct and indirect identifier treatment tables
- Robust re-identification prohibition framework with internal and external controls
- Well-designed verification and documentation requirements
- Special considerations section appropriately addresses small populations, longitudinal data, and sensitive elements

### Additional Observations

This policy represents one of the most technically comprehensive and well-structured policies in the set. The clear distinction between pseudonymization and de-identification, along with the explicit statement that pseudonymized data retains privacy protections, is particularly valuable for organizations that may conflate these concepts. The aggregation thresholds provide actionable numeric standards that can be directly implemented by analytics teams.
