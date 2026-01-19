# OP-POL-005: School District Onboarding Policy - Consolidated Review

**Policy File:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/operational_policies/OP-POL-005.md`
**Review Date:** 2026-01-18
**Reviewers:** EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- The pre-sale requirements (Section 3.1) accurately reflect EdTech sales cycles, including response to security questionnaires (HECVAT, EDUCAUSE, state-specific)
- DPA (Data Processing Agreement) requirements (Section 3.2.1) comprehensively cover the elements schools expect
- Rostering integration references (Clever, ClassLink, OneRoster) in Section 3.3.4 align with industry-standard data exchange protocols
- The DPA acceptance hierarchy (Section 3.2.2) correctly prioritizes customer DPAs, state-standard DPAs (SDPC), then vendor standard DPA

**Technical Observations:**
- State-specific requirement table (Section 3.2.3) appropriately calls out key states (NY, CA, CO, CT, IL)
- Technical setup requirements (Section 3.3.3) cover essential onboarding activities: provisioning, integration, data import, access configuration
- The data inventory requirement (Section 3.3.2) aligns with state law requirements for documenting data elements
- Reference to ANNEX-004 (Student Data Inventory Template) provides operational support

**Recommendations:**
- Consider adding guidance for Ed-Fi data standard integrations alongside Clever/ClassLink/OneRoster
- Include SIS (Student Information System) integration considerations
- Add guidance on pilot/proof-of-concept programs that may involve limited student data

### Practical Implementation Feasibility

**Strengths:**
- The onboarding checklist (Section 3.7) provides actionable implementation guidance
- Clear workflow from pre-contract through go-live with defined checkpoints
- Internal handoff requirements (Section 3.4.2) ensure continuity between sales and implementation teams
- Failed onboarding procedures (Section 3.8) address real-world scenarios where deals fall through

**Concerns:**
- The requirement for legal review of all customer DPAs (Section 3.2.4) may create bottlenecks for high-volume sales
- Consider adding guidance on expedited review for standard/pre-approved DPAs
- Training requirements (Section 3.4.1) could benefit from minimum duration or content specifications

### Integration with Existing EdTech Operations

**Strengths:**
- Strong cross-references to privacy policies (STU-POL-001, STU-POL-002, PRV-POL-003)
- Integration with vendor risk management (SEC-POL-005)
- CRM documentation requirement (Section 3.7.4) ensures operational tracking
- FERPA annual notification support (Section 3.5.2) helps schools meet their obligations

**EdTech SME Verdict:** APPROVED WITH MINOR CHANGES
- Add Ed-Fi and SIS integration guidance
- Include pilot program onboarding considerations
- Add expedited review path for pre-approved DPAs

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**FERPA Compliance:**
- The policy correctly implements the school official designation framework from 34 CFR 99.31(a)(1)
- Section 3.2.1 DPA requirements cover necessary FERPA protections:
  - Services description (defining the educational service)
  - Permitted uses (educational purposes only)
  - Prohibited uses (no sale, no advertising)
  - Parent rights support
- The FERPA annual notification support (Section 3.5.2) is a valuable addition that helps schools meet their direct notification obligations under 34 CFR 99.7

**State Law Compliance:**
- New York: 8 NYCRR Part 121 (Parents' Bill of Rights) correctly cited
- California: SOPIPA and CSPC references appropriate
- Colorado, Connecticut, Illinois requirements acknowledged
- Reference to PRV-POL-003 and ANNEX-003 for complete state matrix is appropriate

**SDPC (Student Data Privacy Consortium):**
- Correct recognition of SDPC as a standardized DPA option
- National DPA (CA-NDPA) reference is accurate

### Citation Correctness

| Citation | Verification |
|----------|--------------|
| 34 CFR 99.31(a)(1) | CORRECT - FERPA school official exception |
| 8 NYCRR Part 121 | CORRECT - NY Education Law 2-d implementing regulations |
| State laws (Various) | CORRECT - appropriate umbrella reference to state-specific requirements |

**Citation Recommendations:**
- Add specific citation for California SOPIPA (Education Code 49073.1)
- Add Illinois SOPPA citation (105 ILCS 85/)
- Consider adding Connecticut PA 16-189 reference

### State Law Coverage Adequacy

**Well Covered:**
- New York (Parents' Bill of Rights attachment)
- California (SOPIPA attestation, CSPC)
- Colorado (data element inventory)
- Connecticut (security attestations)
- Illinois (SOPPA compliance)

**Observations:**
- The state-specific requirements table is appropriately limited to key states with specific requirements
- Reference to ANNEX-003 (State Privacy Law Matrix) for complete coverage is appropriate
- The DPA acceptance hierarchy correctly prioritizes customer DPAs to accommodate state-specific requirements

**Gaps:**
- Consider adding Texas Student Privacy requirements (Texas Ed Code 32.151)
- Virginia Consumer Data Protection Act implications for student data
- Maryland student data privacy law requirements

**Regulatory SME Verdict:** APPROVED WITH MINOR CHANGES
- Add specific state law citations (SOPIPA Ed Code, IL SOPPA)
- Consider Texas, Virginia, Maryland coverage in state table or ANNEX reference

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Logical flow from pre-sale through go-live mirrors actual business process
- Excellent use of checklists (Section 3.7) for operational reference
- Tables effectively communicate DPA requirements, state-specific needs, and technical setup
- The failed onboarding section (Section 3.8) addresses often-overlooked scenarios

**Areas for Improvement:**
- Section 3.1.2 "Common questionnaire formats" could benefit from brief explanations (what is HECVAT?)
- Consider adding estimated timelines for each onboarding phase
- The distinction between DPA and service agreement could be clarified for readers unfamiliar with EdTech contracting

### Consistent Terminology

**Consistency Check:**
- "DPA" is consistently used for Data Processing Agreement (with definition in Section 5)
- "School" and "district" usage is appropriate and contextual
- "Customer" used consistently for school/district entities
- "Onboarding" consistently defined and used

**Terminology Observations:**
- "Implementation" is used both as a process (verb/noun) and as a team role - clear from context but could be distinguished
- "Go-Live" is hyphenated consistently and defined
- Recommend defining "HECVAT" either inline or in definitions (Higher Education Community Vendor Assessment Toolkit)

### Format and Structure Compliance

**Template Adherence:**
- All required sections present and properly numbered
- Consistent placeholder formatting with [Company Name]
- Logical section progression

**Formatting Strengths:**
- Effective use of checkbox format in Section 3.7 (operational checklists)
- Tables are well-structured with clear headers
- Appropriate mix of narrative, tables, and lists

**Minor Issues:**
- None significant - document is well-formatted

**Technical Editor Verdict:** APPROVED WITH MINOR CHANGES
- Define HECVAT and EDUCAUSE acronyms
- Consider adding phase timeline estimates
- Minor clarification of DPA vs service agreement relationship

---

## Stage 7: QA Validation

### Cross-Reference Accuracy

**Verified Cross-References:**
| Reference | Status | Notes |
|-----------|--------|-------|
| STU-POL-001: Student Data Governance Policy | VERIFY | Core student data policy |
| STU-POL-002: School Official Designation Policy | VERIFY | School official framework |
| PRV-POL-003: State Privacy Laws Policy | VERIFY | State law requirements |
| SEC-POL-005: Vendor and Third-Party Risk Management | VERIFY | Vendor management |
| ANNEX-003: State Privacy Law Matrix | VERIFY | State requirements reference |
| ANNEX-004: Student Data Inventory Template | VERIFY | Data inventory template |
| ANNEX-005: School DPA Template | VERIFY | DPA template |
| OP-PROC-010: School District Onboarding Procedure | VERIFY | Operational procedure |

**Cross-Reference Observations:**
- Heavy reliance on annexes (ANNEX-003, 004, 005) - ensure these are complete
- Procedure reference (OP-PROC-010) should contain detailed operational steps
- Cross-reference to STU-POL-002 Section 3.4 for template language is specific and useful

### Template Completeness

**Checklist:**
- [x] Title and policy ID present
- [x] Objective section (Section 1)
- [x] Scope section (Section 2)
- [x] Policy content (Section 3) - comprehensive with 8 subsections
- [x] Standards Compliance matrix (Section 4)
- [x] Definitions table (Section 5) - includes 6 key terms
- [x] Responsibilities matrix (Section 6) - covers 6 roles
- [x] Related Documents list (Section 7) - extensive
- [x] Policy Review section (Section 8)
- [x] Policy Owner placeholder
- [x] Last Reviewed/Next Review date placeholders

**Completeness Score:** 100% - All template elements present

### Publication Readiness

**Pre-Publication Checklist:**
- [x] Comprehensive onboarding workflow coverage
- [x] State-specific requirements addressed
- [x] DPA requirements clearly specified
- [x] Operational checklists provided
- [x] Failed onboarding scenarios covered
- [x] FERPA notification support included

**Outstanding Items Before Publication:**
1. Fill in all [Company Name] placeholders
2. Fill in Policy Owner, Last Reviewed, and Next Review dates
3. Verify all cross-referenced documents exist, especially:
   - ANNEX-003: State Privacy Law Matrix
   - ANNEX-004: Student Data Inventory Template
   - ANNEX-005: School DPA Template
4. Verify OP-PROC-010 procedure document exists
5. Ensure STU-POL-002 Section 3.4 contains referenced template language

**QA Validation Verdict:** APPROVED WITH MINOR CHANGES
- Critical: Verify all ANNEX documents exist and are complete
- Fill placeholder values before publication
- Define HECVAT acronym

---

## Consolidated Verdict

### VERDICT: APPROVED WITH MINOR CHANGES

**Summary of Required Changes:**

1. **Technical/Operational:**
   - Add Ed-Fi and SIS integration guidance
   - Include pilot/POC program onboarding considerations
   - Add expedited review path for pre-approved DPAs

2. **Regulatory/Legal:**
   - Add specific state law citations:
     - California SOPIPA: Education Code 49073.1
     - Illinois SOPPA: 105 ILCS 85/
   - Consider adding Texas, Virginia, Maryland to state requirements table

3. **Editorial:**
   - Define HECVAT acronym (Higher Education Community Vendor Assessment Toolkit)
   - Define or explain EDUCAUSE reference
   - Consider adding phase timeline estimates

4. **Publication (Critical):**
   - Verify all ANNEX documents exist:
     - ANNEX-003: State Privacy Law Matrix
     - ANNEX-004: Student Data Inventory Template
     - ANNEX-005: School DPA Template
   - Verify OP-PROC-010 procedure document exists
   - Fill all placeholder values

**Risk Assessment:** LOW - The policy provides comprehensive coverage of school district onboarding requirements. The operational checklists and state-specific guidance demonstrate strong understanding of EdTech sales and implementation processes.

**Compliance Confidence:** HIGH
- FERPA school official designation framework properly integrated
- State-specific requirements acknowledged with detailed coverage
- DPA requirements comprehensive
- FERPA notification support for schools included

**Dependency Note:** This policy has significant dependencies on annex documents (ANNEX-003, 004, 005). Ensure these are complete and reviewed before this policy is finalized for publication.
