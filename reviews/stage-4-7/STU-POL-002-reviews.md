# STU-POL-002: School Official Designation Policy - Consolidated Reviews

**Policy Title:** School Official Designation Policy
**Policy ID:** STU-POL-002
**Review Date:** 2026-01-18

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Security and Operations Subject Matter Expert

### Technical Accuracy for EdTech Context

**Strengths:**
- The four-criteria framework for school official status (Section 3.1) accurately reflects the operational requirements EdTech companies must meet
- Direct control provisions (Section 3.3) translate abstract legal requirements into concrete operational controls (data access decisions, feature configuration, audit rights, termination rights, amendment authority)
- Subcontractor management requirements (Section 3.6) address the reality of modern SaaS architecture with cloud dependencies

**Areas of Concern:**
- Section 3.2.2 (Direct Control Provisions) mentions "School may audit [Company Name] compliance" but does not specify technical mechanisms (e.g., audit logs, on-demand reports, API access)
- No mention of automated compliance monitoring or control attestation capabilities
- Data export formats (Section 3.5.1) should reference industry standards (CSV, JSON, OneRoster, Ed-Fi)

### Practical Implementation Feasibility

**Strengths:**
- Template language for annual notifications (Section 3.4.2) reduces burden on both vendor and schools
- Clear contract termination workflow (Section 3.5) with defined timeframes
- Subcontractor flow-down requirements are operationally realistic

**Concerns:**
- The 60-day data deletion window post-termination may be challenging for complex data architectures with distributed backups
- "Material subcontractors" notification requirement lacks definition of materiality threshold
- Audit rights survival period of 2 years may conflict with shorter data retention periods

### Integration with Existing EdTech Operations

**Observations:**
- Policy integrates well with DPA template (ANNEX-005) and onboarding policy (OP-POL-005)
- Verification mechanisms (Section 3.7.2) align with common school procurement processes (security questionnaires, SOC 2 reports)
- The policy anticipates school-facing communications and provides supporting materials

**Recommendations:**
1. Add technical specifications for audit access (log formats, query capabilities)
2. Define "material subcontractor" with objective criteria (data access volume, sensitivity, or similar)
3. Include guidance on handling school official status during corporate acquisitions or mergers

**Stage 4 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Regulatory Attorney / Compliance Specialist

### Legal Compliance Accuracy

**FERPA School Official Exception Analysis:**
- The four criteria in Section 3.1 accurately reflect 34 CFR 99.31(a)(1)(i)(B)(1)-(4)
- Direct control requirements (Section 3.3) appropriately operationalize the regulatory standard
- Annual notification requirement correctly identifies the school's obligation to include contractors in their FERPA notice

**Critical Observations:**
- The policy correctly positions the company as acting under school direction rather than independently
- Use limitation provisions (Section 3.2.3) appropriately prohibit secondary uses and commercial use unrelated to contracted services
- Re-disclosure limitations are appropriately cross-referenced to STU-POL-004

**Concerns:**
- The policy could more explicitly state that school official status is contract-by-contract, not blanket authorization
- Should clarify that school official status does not override state student privacy laws that may impose additional requirements
- The template notification language (Section 3.4.2) should note that schools must customize it to their specific FERPA notification

### Citation Correctness

| Citation | Accuracy | Notes |
|----------|----------|-------|
| 34 CFR 99.31(a)(1) | Correct | School official exception |
| 34 CFR 99.31(a)(1)(i)(B) | Correct | Specific criteria for school officials |
| 34 CFR 99.31(a)(1)(i)(B)(1) | Correct | Institutional services criterion |
| 34 CFR 99.31(a)(1)(i)(B)(2) | Correct | Direct control criterion |
| 34 CFR 99.31(a)(1)(i)(B)(3) | Correct | Use limitation criterion |
| 34 CFR 99.31(a)(1)(i)(B)(4) | Correct | Annual notification criterion |
| 34 CFR 99.33 | Correct | Re-disclosure limitations |

All citations verified as accurate.

### State Law Coverage Adequacy

**Assessment:**
- Section 3.2.4 references compliance with "applicable state laws" alongside FERPA and COPPA
- No specific enumeration of state laws that may impose requirements beyond FERPA
- Some states (California, New York, Colorado) have vendor-specific requirements not addressed here

**Recommendations:**
1. Add note that state student privacy laws may impose additional requirements beyond school official status
2. Reference NY Education Law 2-d specifically, which has extensive third-party contractor requirements
3. Consider cross-reference to PRV-POL-003 for state-specific compliance

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Writer / Documentation Standards Specialist

### Clarity and Readability

**Strengths:**
- Clear table format for the four school official criteria (Section 3.1) with requirement-implementation mapping
- Direct control mechanisms presented as actionable table (Section 3.3.1)
- Contract termination process uses clear timeline and action steps

**Concerns:**
- Section 3.2 is titled "Data Processing Agreement Requirements" but some readers may not know what a DPA is until later context
- Some paragraphs in Section 3.3.2 are single sentences that could be consolidated
- The relationship between "school official" and "direct control" concepts could be explained more accessibly for non-legal readers

### Consistent Terminology

**Observations:**
- "School official" terminology used consistently throughout
- "DPA" and "Data Processing Agreement" both used; should standardize to one with the other as first-use expansion
- "Education records" used consistently with FERPA terminology

**Issues Identified:**
- "Contract" and "agreement" used interchangeably (Section 3.5 header vs. 3.2 header)
- "Termination rights" and "contract termination" could cause confusion about who is terminating

### Format and Structure Compliance

**Strengths:**
- Consistent section numbering and hierarchy
- Tables used effectively for structured information
- Placeholder format consistent with template standards

**Recommendations:**
1. Add parenthetical "(DPA)" after first use of "Data Processing Agreement"
2. Standardize on either "contract" or "agreement" for consistency
3. Consider adding a brief glossary note explaining key legal concepts for operational readers

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Analyst / Compliance Auditor

### Cross-Reference Accuracy

| Referenced Document | Exists/Verified | Notes |
|---------------------|-----------------|-------|
| STU-POL-001: Student Data Governance Policy | Yes | Reviewed in this batch |
| STU-POL-004: Student Data Sharing Policy | Yes | Reviewed in this batch |
| PRV-POL-001: FERPA Compliance Policy | Not reviewed | External reference |
| OP-POL-005: School District Onboarding Policy | Not reviewed | External reference |
| ANNEX-005: School DPA Template | Not reviewed | Template document |

### Template Completeness

**Placeholder Audit:**
- [Company Name]: Used consistently throughout (15+ instances)
- [Number, e.g., 60] days for data deletion: Appropriate example provided
- [Number, e.g., 2] years for audit rights survival: Appropriate example provided
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
- [x] Template language for school notifications included
- [ ] Version control metadata present
- [ ] Effective date specified
- [x] Policy owner role defined
- [x] Review cycle defined with appropriate triggers

**Recommendations:**
1. Add document version number
2. Add revision history section
3. Verify ANNEX-005 (School DPA Template) exists and aligns with this policy's requirements
4. Consider adding sample audit request/response workflow

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES

---

## Consolidated Verdict

**VERDICT: APPROVED WITH MINOR CHANGES**

### Summary of Required Changes

1. **Expand acronyms on first use** - DPA should be written out with acronym in parentheses on first occurrence
2. **Add version control metadata** - version number, revision history, effective date
3. **Define "material subcontractor"** - add objective criteria for materiality determination
4. **Add state law note** - mention that state laws may impose additional requirements beyond FERPA
5. **Standardize terminology** - choose between "contract" and "agreement" for consistency

### Commendations

- Excellent translation of FERPA school official requirements into operational controls
- Comprehensive subcontractor management framework
- Practical template language for school annual notifications
- Clear contract termination and data destruction workflow
- Strong integration with related policies and procedures
