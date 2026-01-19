# PRV-PROC-003: State Privacy Laws Compliance Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/privacy_procedures/PRV-PROC-003.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Correctly identifies the major state student privacy laws (SOPIPA, NY Ed Law 2-d, Colorado, Connecticut, Illinois SOPPA)
- State law matrix reference (ANNEX-003) is essential for multi-state operations
- Standardized DPA approaches (SDPC, California NDPA) reflect actual EdTech contracting practices
- Prohibited practices section (3.3.1) accurately captures common state restrictions

**Concerns:**
- Section 3.1.1 state table is incomplete - missing important states like Virginia (VSDPA), Washington, Louisiana, and Maryland
- No mention of data localization requirements some states may have
- Section 3.2.2 references "California K-12 DPA" but California actually uses the California NDPA through SDPC - terminology should be clarified
- No guidance on handling conflicting requirements between states (common in multi-state districts)

### Practical Implementation Feasibility

**Strengths:**
- State-specific DPA addenda approach (Section 3.2.1) is practical for managing variations
- SDPC portal reference (Section 3.2.3) is the standard EdTech approach
- Monitoring process (Section 3.6) addresses the rapidly changing state law landscape
- Breach notification timeline table (Section 3.5.1) provides actionable guidance

**Concerns:**
- Section 3.4.1 NY encryption requirements specify "TLS 1.2+ for data in transit" and "AES-256 for data at rest on mobile devices" but 8 NYCRR 121 has broader encryption requirements beyond mobile devices
- Legislative monitoring (Section 3.6.1) relies on external subscriptions without specifying which sources are authoritative
- No workflow for handling mid-contract state law changes

### Operational Workflow Clarity

**Strengths:**
- Clear "When" triggers align with sales and onboarding processes
- State determination at customer onboarding is appropriately positioned
- Escalation triggers are specific and actionable

**Concerns:**
- Section 3.3.2 lists five required practices without prioritization or implementation sequence
- No guidance on how to handle customers operating in states with no specific student privacy law
- Documentation requirements could benefit from specific templates or forms

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Expand state coverage in summary table
- Clarify California DPA terminology
- Add conflict resolution guidance for multi-state requirements
- Correct NY encryption scope

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Correctly identifies that state laws layer on top of FERPA requirements
- California SOPIPA prohibitions (no targeted ads, no profiling, no sale) accurately stated
- NY Education Law 2-d Parents' Bill of Rights requirement correctly addressed
- Breach notification matrix approach recognizes varying state requirements
- Reference to 8 NYCRR 121.3 and 121.9 is accurate for NY requirements

**Concerns:**
- Section 3.1.1 Colorado description says "data inventory" but Colorado SB 16-158 specifically requires disclosure of data elements being collected - "data inventory" is imprecise
- Connecticut Student Data Privacy Act (Section 3.1.1) description is sparse and missing key requirements around data security plans
- Illinois SOPPA has specific requirements around data breach notification to state superintendent that is not mentioned
- Section 3.4.1 NY breach notification should reference specific timeline requirements under 8 NYCRR 121.9 (currently says "immediately upon discovery" which is not precise)

### Proper Support for Regulatory Requirements

**State-Specific Compliance:**
- NY Parents' Bill of Rights attachment requirement properly addressed
- California SOPIPA deletion rights mentioned
- Encryption requirements for NY correctly identified (though scope issue noted above)

**Prohibited Practices:**
- No sale of student data - universal requirement correctly stated
- Targeted advertising prohibition - correctly identified as most-states requirement
- Profiling prohibition - correctly linked to CA and IL

**Breach Notification:**
- Multi-state notification approach is appropriate
- AG notification thresholds correctly identified for CA
- NY Chief Privacy Officer notification correctly referenced

**Transparency:**
- Privacy policy requirement universal
- Data inventory on request properly addressed

**Regulatory Recommendations:**
- Correct Colorado requirement description
- Expand Connecticut requirements
- Add Illinois superintendent notification requirement
- Specify NY breach notification timeline per regulation
- Consider adding Virginia CDPA/VSDPA requirements (increasingly important)

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Framework is sound but state-specific details need refinement
- No critical compliance gaps, but accuracy improvements needed

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Well-organized progression from identification to implementation to monitoring
- Tables effectively summarize multi-state requirements
- Consistent formatting throughout
- Action-oriented language ("Identify," "Verify," "Document")

**Concerns:**
- Section 3.1.1 table is dense and may be difficult to use quickly - consider making key requirements scannable
- Section 3.3.2 title "Implementing Required Practices" is generic - could be more specific
- Some sections reference "see Section X" but don't specify what information is there

### Step-by-Step Flow Logic

**Strengths:**
- Logical flow from identification through implementation to monitoring
- Onboarding trigger (Section 3.1.1) correctly positions state identification at start of customer relationship
- Annual/quarterly review cycles are specified for ongoing compliance

**Concerns:**
- Section 3.2 has four sub-sections for different DPA approaches but no decision tree for choosing between them
- Section 3.5 Breach Notification is embedded within general state compliance but might be better as a prominent cross-reference to RES-PROC-004
- Section 3.6.1 "Tracking Legislative Updates" Step 3 "Implement changes" is too high-level - should reference change management procedure

### Consistent Terminology

**Findings:**
- "DPA" used consistently (though initial definition still missing from this document)
- "State law matrix" referenced consistently
- State abbreviations used inconsistently (sometimes full name, sometimes abbreviation)
- "SOPIPA" and "SOPPA" are different laws (CA vs IL) - correctly distinguished
- "SDPC" acronym not expanded (Student Data Privacy Consortium)

**Terminology Recommendations:**
- Expand SDPC on first use
- Standardize state references (recommend full names on first use, abbreviations after)
- Add note distinguishing SOPIPA (CA) from SOPPA (IL) given similar names

### Editorial Recommendations

1. Add decision flowchart or criteria for DPA approach selection
2. Standardize state name/abbreviation usage
3. Expand SDPC acronym
4. Add explicit cross-reference to breach notification procedure
5. Add note clarifying SOPIPA vs. SOPPA

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| PRV-POL-003 | State Student Privacy Laws Policy | To be verified at publication |
| RES-POL-003 | Breach Notification (Schools) Policy | To be verified at publication |
| ANNEX-003 | State Student Privacy Law Matrix | To be verified at publication |
| ANNEX-005 | School DPA Template | To be verified at publication |

**Cross-Reference Notes:**
- ANNEX-003 is critical supporting document referenced throughout
- ANNEX-005 DPA template referenced for standard DPA approach
- Internal references follow naming convention
- No orphaned references identified

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Location] | Placeholder | Section 5 - State law matrix location |
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- All procedure sections present and complete
- Fewer placeholders than other procedures (good)
- Heavy reliance on ANNEX-003 means that annex must be complete and accurate

### Publication Readiness

**Document Structure:**
- Markdown formatting valid
- Header hierarchy correct
- Tables properly structured
- Cross-references properly formatted

**Content Completeness:**
- State identification procedures complete
- DPA preparation approaches covered
- Common requirements addressed
- Monitoring process included

**Dependency Check:**
- ANNEX-003 (State Privacy Law Matrix) is critical - must be published simultaneously
- ANNEX-005 (School DPA Template) referenced - should be available
- Breach notification procedure (RES-POL-003) referenced - should exist

**Outstanding Items Before Publication:**
- [ ] Complete placeholder for state law matrix location
- [ ] Verify ANNEX-003 is complete and current
- [ ] Verify ANNEX-005 template is available
- [ ] Cross-check state law accuracy with legal counsel
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. State table incomplete - missing Virginia, Washington, Louisiana, Maryland (EdTech SME)
2. California DPA terminology inconsistency (EdTech SME)
3. NY encryption requirements scope too narrow (EdTech SME)
4. Colorado requirement description imprecise (Regulatory SME)
5. Connecticut requirements incomplete (Regulatory SME)
6. Illinois superintendent notification missing (Regulatory SME)
7. NY breach timeline not specified per regulation (Regulatory SME)
8. DPA approach decision criteria missing (Technical Editor)
9. SDPC acronym not expanded (Technical Editor)
10. ANNEX-003 completeness is critical dependency (QA)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Expand state coverage table | Legal/Compliance | High |
| Verify and expand ANNEX-003 | Legal/Compliance | High |
| Correct state requirement descriptions | Legal/Compliance | High |
| Add DPA approach selection criteria | Document Owner | Medium |
| Expand acronyms (SDPC) | Document Owner | Low |
| Standardize state name references | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The State Privacy Laws Compliance Procedure provides a solid framework for managing multi-state student privacy law compliance. The structure is appropriate, and the approach of using a state law matrix (ANNEX-003) as a reference is practical. However, several state-specific details need correction or expansion, and the state coverage should be broadened. The ANNEX-003 dependency is critical - that document must be accurate and comprehensive for this procedure to function effectively. With the identified corrections, this procedure will serve as effective operational guidance for state law compliance.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
