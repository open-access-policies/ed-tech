# STU-POL-004: Student Data Sharing Policy - Consolidated Reviews

**Policy Title:** Student Data Sharing Policy
**Policy ID:** STU-POL-004
**Review Date:** 2026-01-18

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Security and Operations Subject Matter Expert

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive prohibition list (Section 3.1.1) addresses industry-specific concerns: no sale, no targeted advertising, no data brokers
- API security requirements (Section 3.4.2) specify industry-standard controls: OAuth 2.0, rate limiting, audit logging, scope limitations
- School-directed integrations section (Section 3.4.1) addresses LMS/SIS integration reality

**Areas of Concern:**
- Section 3.3.2 requires subcontractor breach notification within "[Number, e.g., 24] hours" but does not specify detection-to-notification or notification-to-company timelines
- No mention of Data Processing Addendum (DPA) requirements for subcontractors under GDPR or similar frameworks
- API security section lacks specifics on token expiration, refresh token handling, or certificate requirements

### Practical Implementation Feasibility

**Strengths:**
- Due diligence requirements (Section 3.3.1) are practical and achievable
- Subcontractor list maintenance requirement supports school procurement processes
- Re-disclosure prohibition with documentation requirements is operationally sound

**Concerns:**
- "Annual compliance attestations" for subcontractor oversight may be insufficient for critical vendors
- SOC 2 or equivalent certification requirement (Section 3.3.1) may exclude smaller specialized vendors
- No tiering of subcontractor requirements based on data access level or sensitivity

### Integration with Existing EdTech Operations

**Observations:**
- Policy integrates well with STU-POL-002 (School Official) for subcontractor flow-down
- Cross-reference to SEC-POL-005 (Vendor and Third-Party Risk Management) ensures security alignment
- Procurement role explicitly included in responsibilities for contract requirements

**Recommendations:**
1. Add tiered subcontractor requirements based on data sensitivity/volume
2. Include technical integration standards (API specifications, data format requirements)
3. Specify subcontractor monitoring frequency beyond annual attestations for critical vendors
4. Add guidance on handling subcontractor acquisitions or changes in control

**Stage 4 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Regulatory Attorney / Compliance Specialist

### Legal Compliance Accuracy

**FERPA Analysis:**
- Re-disclosure requirements (Section 3.5) correctly reflect 34 CFR 99.33 obligations
- Record of disclosures requirement (Section 3.5.2) properly documents name, interest, date, and description per 34 CFR 99.32
- Emergency disclosure provisions (Section 3.2.5) align with health or safety emergency exception
- Legal process disclosure procedures (Section 3.2.4) appropriately include school notification requirement

**COPPA Analysis:**
- Disclosure limitations (Section 3.2) align with COPPA's restrictions on disclosure to third parties
- Parental consent framework appropriately deferred to STU-POL-003

**State Law Analysis:**
- SOPIPA reference for no-sale prohibition is appropriate
- Student Privacy Pledge alignment noted in compliance table

**Concerns:**
- Section 3.2.4 should note that some legal processes (e.g., ex parte orders) may prohibit school notification
- Directory information exception not addressed in disclosure context
- No explicit mention of the studies exception (34 CFR 99.31(a)(6)) conditions despite Section 3.6.2 reference

### Citation Correctness

| Citation | Accuracy | Notes |
|----------|----------|-------|
| 34 CFR 99.33 | Correct | Re-disclosure prohibition |
| 34 CFR 99.32 | Correct | Record of disclosures |
| 34 CFR 99.31(a)(1) | Correct | School official subcontractors |
| 34 CFR 99.31(a)(6) | Correct | Studies exception |
| 16 CFR 312.5 | Correct | COPPA disclosure limits |
| SOPIPA | Correct | No sale prohibition reference |

### State Law Coverage Adequacy

**Assessment:**
- SOPIPA explicitly referenced for no-sale prohibition
- Student Privacy Pledge mentioned in compliance table
- State-specific requirements not enumerated

**Recommendations:**
1. Add note about state-specific disclosure notification requirements (e.g., data breach notification laws)
2. Consider listing states with affirmative operator obligations (California, Colorado, Connecticut)
3. Reference that some states require parental notification of third-party data sharing

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Writer / Documentation Standards Specialist

### Clarity and Readability

**Strengths:**
- Clear prohibition list in Section 3.1.1 with bold formatting for emphasis
- Disclosure categories (Section 3.2) logically organized by recipient type
- Subcontractor contractual requirements table (Section 3.3.2) provides actionable checklist

**Concerns:**
- Section 3.2.3 "Examples of Permitted Subcontractor Functions" could be formatted as a table for consistency
- "Before Legal Disclosure" and "After Emergency Disclosure" formatting differs (numbered list vs. numbered list)
- Some sections have very short numbered steps that could be presented as bullets

### Consistent Terminology

**Observations:**
- "Third party" consistently defined and used
- "Subcontractor" terminology consistent throughout
- "Re-disclosure" properly hyphenated throughout

**Issues Identified:**
- "DPA" used without expansion (referenced but not defined in this policy)
- "Contracting school" and "school" used interchangeably

### Format and Structure Compliance

**Strengths:**
- Consistent section numbering and hierarchy
- Tables used effectively for structured information
- Placeholder format consistent

**Recommendations:**
1. Add cross-reference definition for DPA (or expand on first use)
2. Standardize list formatting (bullets vs. numbers) for similar content types
3. Consider table format for permitted subcontractor functions
4. Add brief summary of key prohibitions at start for quick reference

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Analyst / Compliance Auditor

### Cross-Reference Accuracy

| Referenced Document | Exists/Verified | Notes |
|---------------------|-----------------|-------|
| STU-POL-001: Student Data Governance Policy | Yes | Reviewed in this batch |
| STU-POL-002: School Official Designation Policy | Yes | Reviewed in this batch |
| PRV-POL-001: FERPA Compliance Policy | Not reviewed | External reference |
| SEC-POL-005: Vendor and Third-Party Risk Management Policy | Not reviewed | External reference |
| ANNEX-005: School DPA Template | Not reviewed | Template document |

### Template Completeness

**Placeholder Audit:**
- [Company Name]: Used consistently throughout (15+ instances)
- [Number, e.g., 24] hours: Used for breach notification timeline
- [Role Title]: Used in Policy Owner field
- [Date]: Used in review date fields

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
- [x] Prohibitions clearly stated
- [x] Subcontractor requirements comprehensive
- [ ] Version control metadata present
- [ ] Effective date specified
- [x] Policy owner role defined
- [x] Review cycle defined

**Recommendations:**
1. Add document version number and revision history
2. Verify SEC-POL-005 exists and aligns with subcontractor requirements
3. Consider adding subcontractor list template or reference
4. Add effective date placeholder

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES

---

## Consolidated Verdict

**VERDICT: APPROVED WITH MINOR CHANGES**

### Summary of Required Changes

1. **Add DPA definition or cross-reference** on first use
2. **Add version control metadata** - version number, revision history, effective date
3. **Note legal process exceptions** for school notification when prohibited by court order
4. **Standardize list formatting** - consistent use of bullets vs. numbered lists
5. **Add subcontractor tiering guidance** based on data access sensitivity

### Commendations

- Comprehensive and unambiguous prohibition list (no sale, no advertising, no data brokers)
- Strong subcontractor management framework with due diligence and contractual requirements
- Appropriate API security controls specified
- Clear re-disclosure prohibition with documentation requirements
- Good integration with vendor risk management and school official policies
- Research sharing properly conditioned on FERPA studies exception compliance
