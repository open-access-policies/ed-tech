# STU-POL-001: Student Data Governance Policy - Consolidated Reviews

**Policy Title:** Student Data Governance Policy
**Policy ID:** STU-POL-001
**Review Date:** 2026-01-18

---

## Stage 4: EdTech Controls SME Review

**Reviewer Persona:** EdTech Security and Operations Subject Matter Expert

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive data classification framework (Restricted, Confidential, Internal, Public) aligns with industry best practices for student data handling
- Data inventory template with source, purpose, retention period, and sensitivity level captures essential metadata for EdTech operations
- Clear distinction between K-12 and Higher Education applicability notes addresses the operational reality of serving both markets

**Areas of Concern:**
- Section 3.1.3 references a Student Data Inventory template (ANNEX-004) but does not specify the technical format or integration requirements with existing data management systems
- The policy does not address real-time data synchronization scenarios common in EdTech (e.g., SIS integrations, rostering protocols like OneRoster)
- No mention of data lineage tracking or automated classification tools that would be essential for organizations at scale

### Practical Implementation Feasibility

**Strengths:**
- Role-based responsibility matrix (Section 6) clearly delineates accountability across functional areas
- Data minimization requirements (Section 3.4) include a practical approval workflow with four documented steps
- Review frequency tied to specific triggers (law changes, new products, feedback, incidents) is operationally sound

**Concerns:**
- The placeholder "[Frequency, e.g., annually]" for data inventory review should have a minimum recommended frequency
- Approval workflow for new data collection (Section 3.4) may create bottlenecks without defined SLAs or escalation paths
- No guidance on handling data classification conflicts or edge cases

### Integration with Existing EdTech Operations

**Observations:**
- Cross-references to related policies (STU-POL-002 through STU-POL-006) create a coherent policy framework
- The policy integrates well with SOC 2 control mappings (Section 4), facilitating audit readiness
- Compatibility with the Student Privacy Pledge is explicitly addressed

**Recommendations:**
1. Add guidance for API-based data collection and classification
2. Include provisions for learning analytics and adaptive learning systems that may create derived data
3. Specify handling requirements for AI/ML training data derived from student interactions

**Stage 4 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 5: FERPA/COPPA Regulatory SME Review

**Reviewer Persona:** Education Privacy Regulatory Attorney / Compliance Specialist

### Legal Compliance Accuracy

**FERPA Analysis:**
- Definition of education records (Section 3.1.1) accurately reflects 34 CFR 99.3
- Exclusions from education records (sole possession records, law enforcement unit records, etc.) are correctly stated per FERPA
- The policy correctly identifies that "eligible students" have direct rights under FERPA
- Directory information handling (Section 3.5) appropriately goes beyond minimum FERPA requirements by maintaining protections even for designated directory information

**COPPA Analysis:**
- Personal information definition (Section 3.1.2) accurately reflects 16 CFR 312.2
- The inclusion of persistent identifiers, geolocation, and combined information aligns with FTC interpretation
- School consent model reference is appropriate but could benefit from explicit citation to FTC guidance on COPPA and schools

**Concerns:**
- The policy does not explicitly address the FERPA health information exception and its interaction with HIPAA
- No mention of the audit/evaluation exception (34 CFR 99.31(a)(3)) which may be relevant for some EdTech uses
- State student privacy laws are referenced generically; specific high-impact state laws (California SOPIPA, Colorado SB 16-158, NY 2-d) could be enumerated

### Citation Correctness

| Citation | Accuracy | Notes |
|----------|----------|-------|
| 34 CFR Part 99 | Correct | Proper FERPA regulatory citation |
| 16 CFR Part 312 | Correct | Proper COPPA regulatory citation |
| 34 CFR 99.31(a)(1) | Correct | School official exception |
| 16 CFR 312.8 | Correct | Data retention under COPPA |
| 16 CFR 312.5 | Correct | Parental consent requirements |
| 16 CFR 312.7 | Correct | Data minimization |

### State Law Coverage Adequacy

**Assessment:**
- Reference to PRV-POL-003 (State Privacy Laws Policy) provides a hook for state-specific requirements
- The policy framework is flexible enough to accommodate varying state requirements
- Missing explicit mention of key state laws that impose stricter requirements than FERPA/COPPA

**Recommendations:**
1. Add footnote or appendix listing key state student privacy laws requiring specific attention
2. Clarify that state laws may impose stricter requirements and supersede this policy where applicable
3. Address HIPAA intersection for health records maintained by schools but processed by EdTech platforms

**Stage 5 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 6: Technical Editor Review

**Reviewer Persona:** Technical Writer / Documentation Standards Specialist

### Clarity and Readability

**Strengths:**
- Clear hierarchical structure with numbered sections enables easy navigation
- Table-based presentation of data classifications (Section 3.3) and compliance mappings (Section 4) aids comprehension
- Definitions section (Section 5) provides essential terminology with proper legal citations
- Scope section clearly delineates applicability across data types, formats, and personnel

**Concerns:**
- Some sentences in Section 3.1.1 run long and could be broken down for improved readability
- The phrase "party acting for the agency or institution" appears in definitions without explanation of what this means in practice
- Section 3.5.2 lists directory information elements without clear distinction from similar elements in Section 3.1.1

### Consistent Terminology

**Observations:**
- "Student data" and "education records" are used consistently and distinctly throughout
- "Workforce members" is consistently used rather than alternating with "employees" or "staff"
- "Personal information" is correctly reserved for COPPA context while "PII" is used more broadly

**Issues Identified:**
- "DPA" is used before its first definition (appears in Section 3.2.1, defined contextually)
- "School official" is used before the related policy (STU-POL-002) is referenced

### Format and Structure Compliance

**Strengths:**
- Consistent use of markdown formatting (headers, tables, bold for emphasis)
- Placeholder notation [Company Name], [Date], etc. is consistently applied
- Related documents section provides clear cross-references with policy IDs

**Recommendations:**
1. Add acronym expansion on first use: "Data Processing Agreement (DPA)"
2. Consider adding a brief executive summary at the top for senior leadership audience
3. Ensure all placeholder values use consistent formatting: **[Value, e.g., example]**

**Stage 6 Assessment:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

**Reviewer Persona:** Quality Assurance Analyst / Compliance Auditor

### Cross-Reference Accuracy

| Referenced Document | Exists/Verified | Notes |
|---------------------|-----------------|-------|
| STU-POL-002: School Official Designation Policy | Yes | Reviewed in this batch |
| STU-POL-003: Parental Consent and Rights Policy | Yes | Reviewed in this batch |
| STU-POL-004: Student Data Sharing Policy | Yes | Reviewed in this batch |
| STU-POL-005: Data Retention and Destruction Policy | Yes | Reviewed in this batch |
| STU-POL-006: De-identification Policy | Yes | Reviewed in this batch |
| PRV-POL-001: FERPA Compliance Policy | Not reviewed | External reference |
| PRV-POL-002: COPPA Compliance Policy | Not reviewed | External reference |
| PRV-POL-003: State Privacy Laws Policy | Not reviewed | External reference |
| STU-PROC-001: Student Data Inventory Procedure | Not reviewed | Procedure document |
| ANNEX-004: Student Data Inventory Template | Not reviewed | Template document |

### Template Completeness

**Placeholder Audit:**
- [Company Name]: Used consistently throughout (20+ instances)
- [Frequency, e.g., annually]: Present in Section 3.1.3
- [Example values] in data inventory table: Appropriate examples provided
- [Role Title]: Used in Policy Owner field
- [Date]: Used in Last Reviewed and Next Review fields

**Missing Elements:**
- No version number or revision history section
- No document control information (approval signatures, effective date)
- No change log or amendment history

### Publication Readiness

**Checklist:**
- [x] All sections complete with substantive content
- [x] Cross-references use consistent policy ID format
- [x] Tables render correctly in markdown
- [x] Regulatory citations formatted consistently
- [ ] Version control metadata present
- [ ] Effective date specified
- [x] Policy owner role defined
- [x] Review cycle defined

**Recommendations:**
1. Add document version number (e.g., v1.0)
2. Add revision history table
3. Add effective date placeholder
4. Consider adding document approval workflow information

**Stage 7 Assessment:** APPROVED WITH MINOR CHANGES

---

## Consolidated Verdict

**VERDICT: APPROVED WITH MINOR CHANGES**

### Summary of Required Changes

1. **Add acronym definitions on first use** (DPA, PII, IEP)
2. **Add version control metadata** (version number, revision history, effective date)
3. **Specify minimum frequency** for data inventory review rather than leaving as open placeholder
4. **Add brief mention of key state laws** (SOPIPA, NY 2-d) in scope or compliance section
5. **Clarify HIPAA intersection** for health records maintained by schools

### Commendations

- Comprehensive coverage of FERPA and COPPA requirements
- Clear role-based responsibility assignments
- Strong data minimization framework
- Appropriate integration with broader policy ecosystem (cross-references)
- Thoughtful treatment of directory information exceeding regulatory minimums
