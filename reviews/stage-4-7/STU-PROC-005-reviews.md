# Expert Review: STU-PROC-005 - Data Retention and Destruction Procedure

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/student_data_procedures/STU-PROC-005.md`
**Review Date:** 2026-01-18
**Review Version:** 1.0

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Assessment: EXCELLENT**

The procedure demonstrates strong technical understanding of data lifecycle management:

1. **Automated Retention (Section 3.1.1, Step 2):** Appropriately addresses log data deletion, backup expiration, and system retention policies - critical for EdTech platforms with significant data volumes.

2. **Electronic Destruction Methods (Section 3.3.1):** Comprehensive table covering:
   - Database records (SQL DELETE with verification)
   - File storage (secure delete API)
   - Cloud storage (provider deletion + key destruction)
   - Local SSD (cryptographic erasure)
   - Local HDD (NIST 800-88 secure overwrite)

3. **Backup Handling (Section 3.3.1, Step 5):** Realistically addresses the challenge of backup deletion by allowing for backup expiration per retention schedule with exclusion from restores - a practical approach.

4. **Subcontractor Destruction (Section 3.6):** Appropriately extends destruction requirements to subcontractors with written directive and confirmation workflow.

**Recommendations:**
- Add guidance for cloud-native architectures where data may be distributed across multiple services (e.g., analytics, search, caching layers).
- Consider adding verification timing for asynchronous deletion systems.

### Practical Implementation Feasibility

**Assessment: EXCELLENT**

1. **Legal Hold Management (Section 3.1.2):** Practical workflow including suspension of deletion, backup rotation suspension, and hold tracking.

2. **Contract Termination Workflow (Section 3.2):** Comprehensive pre- and post-termination handling with export window and verification.

3. **Physical Media Destruction (Section 3.3.2):** Includes DIN 66399 P-4+ standard for paper - appropriate for FERPA-protected information.

**Minor Enhancement:** Section 3.2.1 export format options (CSV, JSON) could include more modern formats like Parquet for large datasets.

### Operational Workflow Clarity

**Assessment: EXCELLENT**

Clear separation between:
- Routine retention (ongoing)
- Legal holds (exception handling)
- Contract termination (event-driven)
- Deletion requests (on-demand)
- Destruction verification (quality assurance)

The destruction certificate workflow (Section 3.5.2) provides appropriate accountability.

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Assessment: SATISFACTORY**

1. **School Direction:** The procedure correctly positions schools as directing retention and deletion for education records, aligning with FERPA's school control requirements.

2. **Legal Hold Compliance:** Section 3.1.2 appropriately addresses legal preservation requirements that may override standard retention schedules.

3. **Data Export (Section 3.2.1):** The export-before-destruction workflow supports schools' obligations to maintain student records.

4. **Exception Handling (Section 3.4.1, Step 2):** Correctly identifies exceptions:
   - Legal holds
   - Contractual retention requirements
   - Legal requirements

**Compliance Gaps:**

1. **COPPA Deletion Timeline:** The procedure does not explicitly address COPPA's requirement to delete personal information "as soon as possible" when consent is not obtained or is revoked. The placeholder timeline (**[Number, e.g., 30]** days) may be too long for COPPA contexts.

2. **State Law Timelines:** Some state student privacy laws (e.g., California SOPIPA) have specific deletion timelines upon school/parent request that may be shorter than the procedure's suggested 30 days.

3. **Backup Deletion:** While the procedure addresses backup handling, FERPA and COPPA do not distinguish between production and backup data. The "mark for exclusion from restores" approach may not satisfy all interpretations of deletion requirements.

### Proper Support for Regulatory Requirements

**Assessment: SATISFACTORY**

1. **Documentation:** Comprehensive record-keeping supports regulatory audit requirements.

2. **Destruction Certificate:** ANNEX-007 template provides school-ready documentation.

3. **Verification:** Multi-step verification process (Section 3.5) demonstrates due diligence.

**Recommendation:** Add explicit guidance on communicating backup retention to schools when they request deletion, so schools can make informed decisions about acceptable timelines.

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Assessment: EXCELLENT**

1. **Structure:** Logical flow from routine retention through specialized scenarios to verification.

2. **Tables:** Effective use of tables for destruction methods (Sections 3.3.1 and 3.3.2).

3. **Technical Accessibility:** Technical methods (cryptographic erasure, degaussing) are mentioned but not over-explained, keeping the procedure accessible.

**Minor Issues:**
- Section 3.3.1, Step 5 uses "mark for exclusion from restores" which may be unclear to non-technical readers - consider adding brief explanation.
- NIST 800-88 reference could include title ("Guidelines for Media Sanitization") for clarity.

### Step-by-Step Flow Logic

**Assessment: EXCELLENT**

Workflows are well-structured:
1. Contract termination: notify → export → retain → destroy → verify → certify → close
2. Deletion request: receive → check exceptions → identify → execute → verify → confirm → document

**Enhancement:** Consider adding estimated timeframes for each major phase of contract termination process.

### Consistent Terminology

**Assessment: SATISFACTORY**

- "Destruction" - used consistently (vs. "deletion" which is used for digital removal)
- "Deletion" - used for electronic data removal
- "Legal hold" - used consistently
- "Subcontractor" - consistent with STU-PROC-004

**Clarification Needed:**
- "Cryptographic erasure" (Section 3.3.1) - brief explanation would be helpful
- "DIN 66399 P-4+" (Section 3.3.2) - consider footnote explaining this is a German standard for shredding security levels

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

**Assessment: SATISFACTORY**

| Reference | Verified |
|-----------|----------|
| STU-POL-005: Data Retention and Destruction Policy | Primary parent policy - appropriate |
| STU-PROC-003: Parent Rights Request Procedure | Referenced for deletion request intake - appropriate |
| SEC-POL-006: Media Handling and Destruction Policy | Security policy reference - verify exists |
| ANNEX-007: Certificate of Destruction Template | Referenced for certification - verify template exists |

**Note:** Cross-references are appropriate and contextually accurate.

### Template Completeness

**Assessment: EXCELLENT**

1. **Placeholder Consistency:**
   - **[Number, e.g., 60]** - Timeline placeholders appropriately flagged with suggestions
   - **[Number, e.g., 30]** - Deletion timeline placeholder
   - **[System]** - Used for storage locations
   - **[Date]**, **[Author]** - Standard for revision history

2. **Required Sections:** All standard sections present and complete.

3. **Technical Standards Referenced:**
   - NIST 800-88 (media sanitization)
   - DIN 66399 P-4+ (paper shredding)

**Minor Gap:** Consider adding ANNEX reference for data export format specifications.

### Publication Readiness

**Assessment: READY WITH MINOR REVISIONS**

**Pre-Publication Checklist:**
- [x] Purpose clearly stated
- [x] Scope appropriately defined (specific teams identified)
- [x] Procedures detailed with clear steps
- [x] Records/retention defined
- [x] Technical methods specified
- [ ] COPPA deletion timeline needs clarification
- [ ] Backup handling communication to schools
- [ ] Verify SEC-POL-006 and ANNEX-007 references exist

---

## Consolidated Findings

### Strengths
1. Comprehensive coverage of all destruction scenarios (routine, legal hold, termination, request-based)
2. Strong technical accuracy for electronic and physical destruction methods
3. Practical backup handling approach that acknowledges operational realities
4. Robust verification and certification workflows
5. Appropriate subcontractor destruction requirements

### Areas for Improvement
1. Add explicit COPPA expedited deletion guidance for under-13 data
2. Clarify backup retention communication to schools
3. Add brief explanations for technical terms (cryptographic erasure, DIN 66399)
4. Consider state law timeline variations
5. Verify ANNEX-007 template exists

### Risk Assessment
- **Regulatory Risk:** MEDIUM - COPPA and state law timeline gaps should be addressed
- **Operational Risk:** LOW - Clear technical workflows with appropriate verification
- **Completeness Risk:** LOW - Minor definitional and timeline improvements

---

## VERDICT: APPROVED WITH MINOR CHANGES

The procedure is technically excellent and operationally sound. The following changes are recommended before publication:

**Required Changes:**
1. Add note that COPPA deletion requests may require expedited processing (shorter than 30-day placeholder)
2. Add guidance on communicating backup retention timelines to schools when they request deletion

**Recommended Changes:**
1. Add brief explanations for technical terms (cryptographic erasure, DIN 66399 P-4+)
2. Include full title for NIST 800-88 reference
3. Consider state-specific deletion timeline note
4. Verify ANNEX-007 template exists

The required changes address regulatory concerns; recommended changes improve clarity and completeness.
