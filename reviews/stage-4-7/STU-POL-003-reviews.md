# STU-POL-003: Parental Consent and Rights Policy - Consolidated Reviews

**Policy Title:** Parental Consent and Rights Policy
**Policy ID:** STU-POL-003
**Review Date:** 2026-01-18

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Security and Operations Subject Matter Expert

### Technical Accuracy for EdTech Context

**Strengths:**
- Dual consent model (school-based vs. direct parental) accurately reflects EdTech operational reality
- Verification methods for verifiable parental consent (Section 3.1.2) align with FTC-approved methods and are technically implementable
- Response timeline table (Section 3.7) provides clear SLA targets for engineering and operations teams

**Areas of Concern:**
- No mention of technical mechanisms for consent capture (consent management platforms, audit trails for consent records)
- Section 3.2.2 states "[Company Name] does not charge for providing access to records" but no technical mechanism for self-service access is described
- Verification requirements table (Section 3.8) lacks technical implementation guidance (e.g., identity verification APIs, knowledge-based authentication providers)

### Practical Implementation Feasibility

**Strengths:**
- School-as-intermediary model reduces direct operational burden while maintaining compliance
- Clear escalation path: parent contacts school, school contacts company
- Exception handling for deletion (Section 3.4.3) addresses real-world edge cases

**Concerns:**
- 5 business day initial response for all request types may be aggressive for organizations without automated intake systems
- No guidance on handling conflicting directions between divorced/separated parents
- Section 3.5.1 has a markdown formatting error: "**[Company Name]** Response:**" should be "**[Company Name] Response:**"

### Integration with Existing EdTech Operations

**Observations:**
- Cross-references to STU-PROC-003 (Parent Rights Request Procedure) suggests operational procedures exist
- ANNEX-006 (Parent Rights Notice Template) provides practical implementation support
- Clear delineation of Customer Success role in request handling

**Recommendations:**
1. Add guidance on consent management platform integration or record-keeping requirements
2. Include technical specifications for data export formats in access requests
3. Address custody disputes or legal guardian verification scenarios
4. Consider adding self-service parent portal capabilities in future versions

**Stage 4 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Regulatory Attorney / Compliance Specialist

### Legal Compliance Accuracy

**FERPA Rights Analysis:**
- Right to inspect and review (Section 3.2) correctly reflects 34 CFR 99.10
- 45-day deadline for providing access correctly stated per FERPA
- Right to request amendment (Section 3.3) correctly limited to factual errors, not grades or evaluative content, per 34 CFR 99.20-21
- Eligible student rights transfer (scope section) accurately described

**COPPA Rights Analysis:**
- Verifiable parental consent methods (Section 3.1.2) align with 16 CFR 312.5(b) approved methods
- Email-plus notation "for internal operations only" correctly reflects FTC guidance
- Right to refuse further collection (Section 3.5) and right to delete (Section 3.4) properly reflect 16 CFR 312.6
- 30-day deletion timeline is reasonable and compliant

**Concerns:**
- No explicit mention of the FERPA hearing right if school denies amendment request (34 CFR 99.21)
- Video verification listed as consent method but FTC has not explicitly approved this; may need qualification
- "Dual enrollment" rights transfer statement could be more nuanced (depends on who maintains records)

### Citation Correctness

| Citation | Accuracy | Notes |
|----------|----------|-------|
| 34 CFR 99.10 | Correct | Right to inspect education records |
| 34 CFR 99.20 | Correct | Right to request amendment |
| 16 CFR 312.6 | Correct | COPPA parental rights |
| 16 CFR 312.5 | Correct | Verifiable parental consent |
| 34 CFR 99.3 (Parent definition) | Correct | Includes natural parent, guardian, acting as parent |
| 34 CFR 99.3 (Eligible Student) | Correct | 18+ or postsecondary attendance |

### State Law Coverage Adequacy

**Assessment:**
- Reference to PRV-POL-003 and "applicable state laws" provides hook for state requirements
- Section 3.4.1 mentions state deletion rights generally
- No specific state law provisions enumerated despite significant variations

**Recommendations:**
1. Note that California provides student data deletion rights independent of parental request
2. Reference specific state consent requirements that may exceed COPPA (e.g., Connecticut)
3. Add note about state-specific verification requirements where applicable
4. Clarify handling when state law provides broader rights than FERPA/COPPA

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Writer / Documentation Standards Specialist

### Clarity and Readability

**Strengths:**
- Rights Holder by Context section (in Scope) clearly addresses the K-12 vs. Higher Ed distinction
- Table format for consent scenarios (Section 3.1.2) aids quick reference
- Response timelines table (Section 3.7) is actionable and clear

**Concerns:**
- Section 3.5.1 has a markdown formatting error with misplaced asterisks
- Some sections (e.g., 3.4.2) have very short numbered steps that could be consolidated
- "Email-plus (for internal operations only)" terminology may not be clear to all readers

### Consistent Terminology

**Observations:**
- "Parents and eligible students" phrasing used consistently
- "Rights request" terminology consistent throughout
- "School" vs. "educational institution" generally consistent (school preferred for brevity)

**Issues Identified:**
- "COPPA Context" and "FERPA Context" headers in Section 3.4.1 use different formatting than other headers
- "Verifiable consent" and "verifiable parental consent" both used

### Format and Structure Compliance

**Strengths:**
- Consistent section numbering
- Effective use of tables for structured information
- Clear separation of process steps

**Recommendations:**
1. Fix markdown error in Section 3.5.1: "**[Company Name]** Response:**" should be "**[Company Name] Response:**"
2. Add explanation of "email-plus" method with FTC citation
3. Standardize to "verifiable parental consent" throughout
4. Consider adding a flowchart for the rights request process

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Analyst / Compliance Auditor

### Cross-Reference Accuracy

| Referenced Document | Exists/Verified | Notes |
|---------------------|-----------------|-------|
| STU-POL-001: Student Data Governance Policy | Yes | Reviewed in this batch |
| STU-POL-005: Data Retention and Destruction Policy | Yes | Reviewed in this batch |
| PRV-POL-001: FERPA Compliance Policy | Not reviewed | External reference |
| PRV-POL-002: COPPA Compliance Policy | Not reviewed | External reference |
| STU-PROC-003: Parent Rights Request Procedure | Not reviewed | Procedure document |
| ANNEX-006: Parent Rights Notice Template | Not reviewed | Template document |

### Template Completeness

**Placeholder Audit:**
- [Company Name]: Used consistently (15+ instances)
- [Number, e.g., 5] business days: Used appropriately for response times
- [Number, e.g., 30] days: Used for deletion timelines
- [Number, e.g., 10] business days: Used for amendment completion
- [Role Title]: Used in Policy Owner field
- [Date]: Used in review date fields

**Formatting Issue Identified:**
- Section 3.5.1: "**[Company Name]** Response:**" - extra asterisks create formatting error

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
- [x] Rights request process clearly defined
- [ ] Version control metadata present
- [ ] Effective date specified
- [ ] Formatting error in Section 3.5.1 corrected
- [x] Policy owner role defined
- [x] Review cycle defined

**Recommendations:**
1. Fix formatting error in Section 3.5.1
2. Add document version number and revision history
3. Verify STU-PROC-003 and ANNEX-006 exist and align with this policy
4. Add workflow diagram for parent rights request handling

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES

---

## Consolidated Verdict

**VERDICT: APPROVED WITH MINOR CHANGES**

### Summary of Required Changes

1. **Fix formatting error** in Section 3.5.1 - correct markdown syntax
2. **Add version control metadata** - version number, revision history, effective date
3. **Clarify "email-plus"** method with brief explanation and FTC citation
4. **Add note about FERPA hearing right** when amendment is denied
5. **Standardize terminology** - use "verifiable parental consent" consistently
6. **Add custody/guardian dispute guidance** for handling conflicting parental directions

### Commendations

- Excellent dual consent model addressing both school-contracted and direct-to-consumer scenarios
- Comprehensive coverage of all major parental rights (access, amendment, deletion, opt-out)
- Clear response timeline commitments
- Appropriate distinction between K-12 and higher education contexts
- Practical verification requirements table
