# AC-POL-003: Student Data Access Controls Policy - Consolidated Review

**Policy File:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/access_control_policies/AC-POL-003.md`
**Review Date:** 2026-01-18
**Reviewers:** EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- The role-based access control (RBAC) model in Section 3.2 accurately reflects typical EdTech organizational structures
- The school-specific roles (Section 3.2.2) correctly map to educational hierarchies: district administrators, school administrators, teachers, counselors, parents, and students
- Multi-tenancy controls (Section 3.3) appropriately address the school/district data segregation requirements common in EdTech SaaS platforms
- The inclusion of rostering integration considerations aligns with industry-standard data flows (Clever, ClassLink, OneRoster)

**Technical Observations:**
- The authentication requirements (Section 3.4) appropriately differentiate between workforce, school user, and student authentication needs
- SSO integration with school identity providers is correctly identified as the preferred approach
- The age-appropriate authentication methods for students (Section 3.4.3) correctly address COPPA constraints around email for young children

**Recommendations:**
- Consider adding specific guidance on LTI (Learning Tools Interoperability) authentication contexts, which are common in EdTech integrations
- The session timeout placeholder (Section 3.4.1) should be set to industry-standard values (15-30 minutes recommended)

### Practical Implementation Feasibility

**Strengths:**
- The access request process (Section 3.5.1) is realistic and includes appropriate approval chains
- Emergency access procedures (Section 3.5.3) balance security with operational necessity
- Staging environment guidance (Section 3.8.2) provides practical guidance for development teams

**Concerns:**
- The requirement for synthetic data in development environments (Section 3.8.1) may be challenging for smaller EdTech companies without robust data generation capabilities
- Consider adding guidance on acceptable anonymization techniques for staging data

### Integration with Existing EdTech Operations

**Strengths:**
- Cross-references to related policies (AC-POL-001, AC-POL-002, SEC-POL-001) provide clear integration points
- The subcontractor access requirements (Section 3.9) align with typical EdTech vendor management practices
- School audit access provisions (Section 3.6.3) support schools' FERPA record-keeping obligations

**EdTech SME Verdict:** APPROVED WITH MINOR CHANGES
- Add LTI authentication guidance
- Specify recommended session timeout values
- Include anonymization technique guidance for staging environments

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**FERPA Compliance:**
- Section 3.1.1 correctly implements the "legitimate educational interest" standard from 34 CFR 99.31(a)(1)
- The definition of legitimate educational interest (Section 5) accurately reflects FERPA requirements
- The policy correctly positions the company as operating under the school official exception
- Access termination procedures (Section 3.7) support schools' ability to maintain records of disclosures

**COPPA Compliance:**
- Section 3.4.3 appropriately addresses COPPA's restrictions on collecting email from children under 13
- Parent-managed accounts for children under 13 aligns with COPPA's verifiable parental consent requirements
- The reference to 16 CFR 312.8 confidentiality requirements is accurate

**State Law Considerations:**
- The policy appropriately references state law security requirements in Section 4
- Consider adding specific reference to California's SOPIPA and state student privacy laws that impose access control requirements

### Citation Correctness

| Citation | Verification |
|----------|--------------|
| 34 CFR 99.31(a)(1) | CORRECT - This is the school official exception under FERPA |
| 16 CFR 312.8 | CORRECT - COPPA confidentiality and security requirements |
| CIS Controls (RBAC) | CORRECT - CIS Controls include access control recommendations |

**Observations:**
- The citation format is consistent and accurate
- Consider adding specific citations for SOC 2 Trust Service Criteria (CC6.1, CC6.2, CC6.3)

### State Law Coverage Adequacy

**Covered:**
- General state law security requirements referenced
- Multi-state applicability acknowledged

**Gaps:**
- No specific mention of New York Education Law 2-d access control requirements
- Illinois SOPPA access control provisions not explicitly addressed
- California CSPC (California Student Connected Schools Privacy Commission) requirements not mentioned

**Regulatory SME Verdict:** APPROVED WITH MINOR CHANGES
- Add SOPIPA reference for California schools
- Consider adding New York and Illinois specific access control citations
- Expand SOC 2 citation specificity in compliance matrix

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Clear hierarchical structure with numbered sections
- Effective use of tables for role definitions and compliance mapping
- Bullet points enhance scannability for operational reference
- The objective statement (Section 1) clearly articulates the policy's purpose

**Areas for Improvement:**
- Section 3.3.1 could benefit from a brief explanation of "logical separation" for non-technical readers
- The phrase "school-scoping on all queries" (Section 3.3.2) may require clarification for broader audiences

### Consistent Terminology

**Consistency Check:**
- "Student data" is used consistently throughout
- "School official" terminology aligns with FERPA definitions
- "Workforce members" is used consistently for internal personnel
- Minor inconsistency: "workforce" vs "employee" - recommend standardizing to "workforce member" throughout

**Terminology Recommendations:**
- Section 3.7.1 uses "employee termination" but should use "workforce member termination" for consistency
- Ensure "legitimate educational interest" is italicized or formatted consistently when used as a defined term

### Format and Structure Compliance

**Template Adherence:**
- All required sections present (Objective, Scope, Policy, Standards Compliance, Definitions, Responsibilities, Related Documents, Policy Review)
- Placeholder formatting [Company Name] is consistent
- Date and role placeholders properly formatted

**Formatting Issues:**
- None identified - document follows standard policy template

**Technical Editor Verdict:** APPROVED WITH MINOR CHANGES
- Replace "employee" with "workforce member" in Section 3.7.1
- Add brief clarification of "logical separation" in Section 3.3.1
- Consider adding glossary reference for technical terms

---

## Stage 7: QA Validation

### Cross-Reference Accuracy

**Verified Cross-References:**
| Reference | Status | Notes |
|-----------|--------|-------|
| STU-POL-001: Student Data Governance Policy | VERIFY | Should exist in policy set |
| STU-POL-002: School Official Designation Policy | VERIFY | Should exist in policy set |
| AC-POL-001: Logical Access Control Policy | VERIFY | Should exist in policy set |
| AC-POL-002: User Access Management Policy | VERIFY | Should exist in policy set |
| SEC-POL-001: Information Security Policy | VERIFY | Should exist in policy set |
| AC-PROC-005: Student Data Access Request Procedure | VERIFY | Procedure document |
| STU-POL-005 (Section 3.7.3) | VERIFY | Data deletion reference |

**Cross-Reference Observations:**
- All cross-references use consistent naming conventions
- Policy IDs follow established pattern (XXX-POL-NNN)
- Procedure reference (AC-PROC-005) follows procedure naming convention

### Template Completeness

**Checklist:**
- [x] Title and policy ID present
- [x] Objective section (Section 1)
- [x] Scope section (Section 2)
- [x] Policy content (Section 3)
- [x] Standards Compliance matrix (Section 4)
- [x] Definitions table (Section 5)
- [x] Responsibilities matrix (Section 6)
- [x] Related Documents list (Section 7)
- [x] Policy Review section (Section 8)
- [x] Policy Owner placeholder
- [x] Last Reviewed/Next Review date placeholders

**Completeness Score:** 100% - All template elements present

### Publication Readiness

**Pre-Publication Checklist:**
- [x] No broken internal links
- [x] Consistent heading hierarchy
- [x] Tables render correctly
- [x] Placeholder brackets used consistently
- [x] No orphaned content

**Outstanding Items Before Publication:**
1. Fill in all [Company Name] placeholders
2. Set session timeout value in Section 3.4.1
3. Set account disable timeline in Section 3.7.1
4. Fill in Policy Owner, Last Reviewed, and Next Review dates
5. Verify all cross-referenced documents exist in final policy set

**QA Validation Verdict:** APPROVED WITH MINOR CHANGES
- Ensure all placeholders are filled before publication
- Verify cross-referenced documents exist
- Minor terminology standardization needed

---

## Consolidated Verdict

### VERDICT: APPROVED WITH MINOR CHANGES

**Summary of Required Changes:**

1. **Technical/Operational:**
   - Add LTI authentication guidance
   - Specify session timeout values (recommend 15-30 minutes)
   - Add anonymization guidance for staging environments

2. **Regulatory/Legal:**
   - Add SOPIPA citation for California coverage
   - Consider adding NY Education Law 2-d and IL SOPPA references
   - Expand SOC 2 citation specificity

3. **Editorial:**
   - Standardize "workforce member" terminology throughout
   - Clarify "logical separation" for non-technical readers

4. **Publication:**
   - Fill all placeholder values before final publication
   - Verify all cross-referenced documents exist

**Risk Assessment:** LOW - No fundamental compliance gaps identified. Changes are enhancements to an already solid policy framework.
