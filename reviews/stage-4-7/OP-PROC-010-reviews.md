# OP-PROC-010: School District Onboarding Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/operational_procedures/OP-PROC-010.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive onboarding lifecycle coverage from qualification through go-live to handoff
- Correctly identifies common security questionnaire types (HECVAT for higher ed, state templates)
- Integration references (Section 3.3.3) cover standard EdTech rostering options (Clever, ClassLink, OneRoster)
- DPA approach options (Section 3.2) reflect actual EdTech contracting reality (customer DPA, state standard, company standard)

**Concerns:**
- Section 3.1.1 distinguishes "K-12 or higher education" but HECVAT is only mentioned for higher ed - should include common K-12 questionnaires (e.g., App Vetting, state tools)
- No mention of pilot/trial phases common in EdTech sales cycles
- Section 3.3.3 mentions SSO integration but doesn't specify common protocols (SAML, OAuth, LTI)
- Missing guidance on multi-school or consortium onboarding (common for district-wide deployments)

### Practical Implementation Feasibility

**Strengths:**
- Compliance documentation package (Section 3.1.3) covers all typical school requirements
- Go-live checklist (Section 3.4.1) ensures readiness before launch
- Handoff to Customer Success (Section 3.4.2) addresses operational continuity
- CRM integration mentioned for tracking

**Concerns:**
- Section 3.1.2 security questionnaire response routes to multiple teams but doesn't specify SLA or coordination process
- No template or standardized responses mentioned for common questionnaire items
- Section 3.3.1 kickoff meeting attendees listed generically - should specify required vs. optional attendees
- No estimated timeline for typical onboarding cycle

### Operational Workflow Clarity

**Strengths:**
- Clear "When" triggers for each phase
- Logical progression from pre-contract through implementation to go-live
- Escalation criteria are appropriate
- Post-onboarding documentation requirements are comprehensive

**Concerns:**
- No decision criteria for choosing between DPA approaches (Section 3.2.1)
- Section 3.2.2 Customer-Provided DPA doesn't specify escalation if terms are unacceptable
- Missing guidance on parallel workstreams (e.g., can technical setup begin before DPA execution?)
- No rollback or cancellation procedure if onboarding fails

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Add K-12 questionnaire types
- Add pilot/trial phase handling
- Specify integration protocols
- Add typical timeline guidance

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Correctly positions DPA execution before receiving student data (Section 3.3.4)
- FERPA and COPPA requirements identified in customer qualification (Section 3.1.1)
- Data inventory process (Section 3.3.2) aligns with DPA requirements
- State law compliance reference (ANNEX-003) appropriately positioned in qualification

**Concerns:**
- Section 3.1.1 identifies "COPPA requirements (if K-12)" but COPPA applies based on age of users, not institution type - should say "if under-13 users"
- No explicit checkpoint to verify school official designation requirements are met before data transfer
- Section 3.2.5 DPA execution doesn't mention verifying FERPA required provisions are present
- Data import (Section 3.3.4) should explicitly reference that data transfer can only occur after DPA is fully executed

### Proper Support for Regulatory Requirements

**DPA Requirements:**
- Multiple DPA approaches provide flexibility
- State-specific requirements referenced
- Execution verification included

**School Official Designation:**
- Not explicitly addressed as a separate verification step
- Implicitly addressed through DPA terms but should be explicit

**Data Transfer Safeguards:**
- Secure transmission required (Section 3.3.4)
- Data validation included
- School confirmation before user access

**Documentation:**
- Comprehensive records requirements
- Data inventory maintained
- Training records retained

**Regulatory Recommendations:**
- Correct COPPA applicability statement (age-based, not institution-based)
- Add explicit school official designation verification step
- Add checkpoint to verify DPA covers FERPA minimum requirements
- Strengthen pre-data-transfer verification

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Framework is sound for compliant onboarding
- Minor clarifications needed for FERPA/COPPA checkpoints

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Well-structured progression through onboarding phases
- Clear section headers identify each phase and sub-process
- Checklists (Sections 3.4.1, 3.5.1) provide auditable verification points
- Consistent formatting throughout

**Concerns:**
- Section 3.2 has four DPA sub-sections (3.2.2-3.2.5) but 3.2.1 "DPA Preparation" doesn't clearly connect to them
- Some sections have very short step lists while others are comprehensive (inconsistent depth)
- Section 3.3.3 "Technical Setup" Step 4 "Configure privacy settings" is vague - what settings?
- Handoff documentation (Section 3.4.2) could benefit from a template or checklist

### Step-by-Step Flow Logic

**Strengths:**
- Clear phase progression: Pre-Contract > Contracting > Implementation > Go-Live > Post-Onboarding
- Each major phase has logical sub-components
- Go-live has explicit readiness verification

**Concerns:**
- Section 3.2.1 determines DPA approach but then jumps to specific approach sections - decision criteria unclear
- Section 3.3 Implementation begins with kickoff but doesn't specify what triggers kickoff readiness
- Section 3.3.4 Data Import doesn't explicitly require DPA verification - should be step 0
- No explicit checkpoints between phases (when is "Pre-Contract" complete and "Contracting" begins?)

### Consistent Terminology

**Findings:**
- "Customer" vs. "school" vs. "district" used somewhat interchangeably (consider standardizing)
- "DPA" used consistently (though not expanded)
- "CRM" used without expansion
- "[Company Name]" placeholder used consistently
- "Customer Success" team title used consistently
- "Implementation team" referenced but not defined

**Terminology Recommendations:**
- Expand DPA and CRM on first use
- Standardize customer terminology (suggest "customer" for general, "school/district" when specific)
- Define implementation team composition

### Editorial Recommendations

1. Add decision criteria for DPA approach selection in Section 3.2.1
2. Expand acronyms (DPA, CRM, SSO, SIS)
3. Standardize customer terminology
4. Add explicit phase transition criteria
5. Add DPA verification as first step in data import
6. Add handoff documentation template or checklist

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| OP-POL-005 | School District Onboarding Policy | To be verified at publication |
| STU-POL-002 | School Official Designation Policy | To be verified at publication |
| PRV-POL-003 | State Privacy Laws Policy | To be verified at publication |
| ANNEX-003 | State Privacy Law Matrix | To be verified at publication |
| ANNEX-004 | Student Data Inventory Template | To be verified at publication |
| ANNEX-005 | School DPA Template | To be verified at publication |

**Cross-Reference Notes:**
- Multiple policy and annex references provide comprehensive governance framework
- Three annex dependencies (003, 004, 005) - all must be available at publication
- References follow naming convention consistently

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Company Name] | Placeholder | Used consistently throughout |
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- Minimal placeholders outside company name (excellent)
- All procedure sections complete
- Checklists are comprehensive
- No orphaned or incomplete sections

### Publication Readiness

**Document Structure:**
- Markdown formatting valid
- Header hierarchy correct
- Checklists use proper checkbox format
- Tables properly formatted

**Content Completeness:**
- Full onboarding lifecycle covered
- Multiple DPA scenarios addressed
- Technical setup adequately detailed
- Post-onboarding handoff included

**Dependency Check:**
- ANNEX-003 (State Privacy Law Matrix) - critical, must exist
- ANNEX-004 (Data Inventory Template) - referenced in procedure, must exist
- ANNEX-005 (School DPA Template) - referenced in procedure, must exist
- CRM system assumed - verify exists and can track required fields
- Contract management system referenced - verify exists

**Outstanding Items Before Publication:**
- [ ] Complete company name placeholder
- [ ] Verify all referenced policies exist
- [ ] Verify all annexes (003, 004, 005) exist and are complete
- [ ] Confirm CRM and contract management system capabilities
- [ ] Validate integration options (Clever, ClassLink, OneRoster) are supported
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. K-12 questionnaire types not specified (EdTech SME)
2. Pilot/trial phase handling missing (EdTech SME)
3. COPPA applicability statement incorrect (age vs. institution) (Regulatory SME)
4. School official designation verification not explicit (Regulatory SME)
5. DPA approach selection criteria missing (Technical Editor)
6. Acronyms not expanded (Technical Editor)
7. Phase transition criteria not explicit (Technical Editor)
8. Three annex dependencies must be verified (QA)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Verify/create ANNEX-003, 004, 005 | Legal/Compliance | High |
| Correct COPPA applicability statement | Legal/Compliance | High |
| Add school official verification step | Legal/Compliance | Medium |
| Add DPA approach selection criteria | Document Owner | Medium |
| Expand acronyms on first use | Document Owner | Medium |
| Add K-12 questionnaire types | Sales/Security | Low |
| Add pilot/trial phase handling | Sales/Product | Low |
| Add phase transition criteria | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The School District Onboarding Procedure is comprehensive and well-structured, covering the complete customer onboarding lifecycle from initial qualification through go-live and handoff. The procedure appropriately addresses multiple DPA scenarios, compliance documentation requirements, and technical implementation steps. The integration of state law compliance and data inventory processes demonstrates attention to regulatory requirements. The primary concerns are the incorrect COPPA applicability statement, missing school official designation verification, and the critical dependency on three annexes that must exist at publication. With these corrections and dependencies resolved, this procedure will effectively guide compliant customer onboarding.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
