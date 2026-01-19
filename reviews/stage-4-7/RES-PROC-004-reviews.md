# RES-PROC-004: School Breach Notification Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/resilience_procedures/RES-PROC-004.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Correctly positions the EdTech vendor as supporting schools in their parent notification obligations (Section 3.5)
- Severity assessment criteria (Section 3.2.1) are appropriate for student data context
- Multi-state notification requirement recognition (Section 3.3, 3.4) reflects EdTech operational reality
- Ransomware explicitly mentioned as a breach trigger (Section 3.1.1) - increasingly relevant

**Concerns:**
- Section 3.1.1 "Loss of device/media with student data" should clarify whether encrypted device loss constitutes a breach (most state laws have encryption safe harbor)
- No specific guidance on third-party/subprocessor breaches and notification chain
- Missing guidance on coordinating notification when multiple EdTech vendors are affected by same incident
- No mention of student-facing notifications (age-appropriate for older students who may have accounts)

### Practical Implementation Feasibility

**Strengths:**
- Notification timeline placeholders (24 hours initial, 48 hours update, 30 days final) are reasonable defaults
- Template references for parent notification support (Section 3.5.1) are practical
- Clear escalation criteria for significant breaches (Section 4)
- 7-year retention for breach records is appropriate

**Concerns:**
- Section 3.3.2 "Sending Initial Notification" Step 4 says "Within [Number, e.g., 24] hours of discovery" but discovery timing can be ambiguous - should clarify
- No guidance on "discovery" definition for timeline calculation
- Section 3.4.1 AG notification thresholds table only covers 4 states - many EdTech companies operate in all 50
- Missing communication templates or references for consistent messaging

### Operational Workflow Clarity

**Strengths:**
- Clear "When" triggers for each procedure section
- Multi-channel notification approach (email + phone for urgent)
- School support section (Section 3.5) appropriately separates vendor role from school role
- Documentation requirements are comprehensive

**Concerns:**
- Section 3.1.1 requires notification to Student Data Privacy Officer "immediately" but doesn't define immediate
- No on-call or after-hours escalation procedure specified
- Section 3.3.4 Final Report at 30 days may conflict with ongoing investigations - need flexibility provision
- Missing coordination procedure between Security, Legal, Privacy, Customer Success teams mentioned in scope

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Clarify encrypted device breach status
- Add subprocessor breach guidance
- Expand state coverage or reference to matrix
- Add discovery definition

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Correctly recognizes that schools are the primary FERPA-obligated parties for parent notification
- NY Education Law 2-d breach notification requirements accurately referenced (8 NYCRR 121.9)
- Separation of vendor notification to school vs. school notification to parents is correct model
- FTC notification for COPPA violations appropriately mentioned (Section 3.4.3)

**Concerns:**
- Section 3.2.1 asks whether "education records" are involved but FERPA breach notification provisions are limited - should clarify that state laws drive most notification requirements
- No mention of FERPA's lack of a general breach notification requirement (important context)
- Section 3.4.1 NY timeline says "Per Education Law 2-d" but specific timeline from 8 NYCRR 121.9 should be stated
- Missing reference to COPPA breach notification considerations (unauthorized access to children's personal information)

### Proper Support for Regulatory Requirements

**School Notification:**
- Vendor-to-school notification appropriately positioned as primary obligation
- DPA-designated contacts correctly identified as recipients
- Tiered notification approach (initial, update, final) is appropriate

**Regulatory Notification:**
- State AG notification requirements recognized
- NY Chief Privacy Officer notification correctly addressed
- FTC notification for COPPA mentioned

**Parent Notification Support:**
- Correctly frames vendor role as supporting schools
- Authorization requirement for direct parent notification is appropriate
- School approval of messaging is correct approach

**Documentation:**
- Comprehensive documentation requirements
- 7-year retention appropriate for litigation hold purposes

**Regulatory Recommendations:**
- Add note clarifying that state laws (not FERPA) primarily drive breach notification
- Specify NY 8 NYCRR 121.9 timeline requirements
- Expand COPPA breach notification considerations
- Add reference to state law matrix (ANNEX-003) for complete state requirements

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Framework correctly positions vendor obligations
- Minor clarifications needed for regulatory context

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Clear progression through breach lifecycle (identification > assessment > notification > support > documentation)
- Severity assessment table (Section 3.2.1) provides quick reference
- Timeline placeholders are clearly marked
- Action-oriented language throughout

**Concerns:**
- Section 3.1.1 "Classify as potential student data breach if:" lists five conditions but doesn't indicate if one or all must be present
- Section 3.3.1 "Preparing Initial Notification" Step 3 "Prepare for questions" has action items that seem post-notification not pre-notification
- Some sections are very detailed while others are sparse (e.g., 3.4.3 "Other Regulatory Notifications" is very brief)
- Multiple timeline placeholders with same format "[Number, e.g., X]" - consider using unique identifiers

### Step-by-Step Flow Logic

**Strengths:**
- Logical flow from identification through notification to follow-up
- Clear escalation to incident response procedure (RES-POL-001)
- Parallel paths for school and regulatory notification appropriately separated
- Post-notification activities included

**Concerns:**
- Section 3.1.1 Step 4 "Escalate per RES-POL-001" references policy not procedure - should reference incident response procedure
- Section 3.2.1 Step 5 "Document assessment" doesn't specify where/how to document
- Section 3.3.3 "Sending Updated Notification" Step 2 says only "Review and approve" without specifying who
- No explicit decision point for determining if breach is confirmed vs. suspected

### Consistent Terminology

**Findings:**
- "Breach" vs. "incident" - both used but incident seems to be the broader term (correct)
- "Student data" and "education records" both used - should clarify relationship
- "DPA" used without expansion
- "[Company Name]" placeholder used consistently
- "Student Data Privacy Officer" used consistently
- "CPO" abbreviation used for Chief Privacy Officer in NY section

**Terminology Recommendations:**
- Clarify distinction between "student data breach" and "education records breach"
- Expand DPA on first use
- Expand CPO on first use or spell out
- Clarify "incident" vs. "breach" terminology

### Editorial Recommendations

1. Clarify whether breach classification conditions are OR or AND
2. Reposition FAQ preparation to post-notification preparation
3. Expand brief sections (3.4.3) or explicitly reference comprehensive guidance
4. Differentiate timeline placeholders with unique identifiers
5. Specify approval authority for updated notifications
6. Expand acronyms (DPA, CPO)

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| RES-POL-003 | Breach Notification (Schools) Policy | To be verified at publication |
| RES-POL-001 | Incident Response Policy | To be verified at publication |
| PRV-POL-003 | State Privacy Laws Policy | To be verified at publication |
| ANNEX-003 | State Privacy Law Matrix | To be verified at publication |

**Cross-Reference Notes:**
- Policy references establish appropriate governance framework
- ANNEX-003 dependency for state-specific requirements
- No orphaned references

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Number, e.g., 24] | Placeholder | Section 3.3.2 - initial notification timeline |
| [Number, e.g., 48] | Placeholder | Section 3.3.3 - update notification timeline |
| [Number, e.g., 30] | Placeholder | Section 3.3.4 - final report timeline |
| [Number, e.g., 7] | Placeholder | Section 3.7.1 - retention period |
| [Company Name] | Placeholder | Section 3.5.2 |
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- Multiple timeline placeholders need completion before publication
- All procedure sections present
- Escalation criteria comprehensive
- Records table complete

### Publication Readiness

**Document Structure:**
- Markdown formatting valid
- Header hierarchy correct
- Tables properly formatted
- Lists use consistent formatting

**Content Completeness:**
- Full breach notification lifecycle covered
- Multi-stakeholder notification addressed (schools, regulators, parents)
- Documentation requirements comprehensive
- Post-incident follow-up included

**Operational Dependencies:**
- Incident response procedure (RES-POL-001) must exist
- ANNEX-003 state law matrix required for state-specific guidance
- DPA-designated contacts database assumed
- Communication channels (email, phone) for schools assumed

**Outstanding Items Before Publication:**
- [ ] Complete all timeline placeholders
- [ ] Complete company name placeholder
- [ ] Verify RES-POL-001 Incident Response Policy/Procedure exists
- [ ] Verify ANNEX-003 State Privacy Law Matrix is complete
- [ ] Confirm school contact database is accessible
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. Encrypted device breach status unclear (EdTech SME)
2. Subprocessor breach guidance missing (EdTech SME)
3. State AG notification table incomplete (EdTech SME)
4. FERPA vs. state law notification context needed (Regulatory SME)
5. NY specific timeline not stated (Regulatory SME)
6. Breach classification conditions need clarification (AND/OR) (Technical Editor)
7. Acronyms not expanded (Technical Editor)
8. Multiple timeline placeholders need completion (QA)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Complete all timeline placeholders | Legal/Compliance | High |
| Clarify encrypted device breach treatment | Legal/Compliance | High |
| Add subprocessor breach notification guidance | Legal/Compliance | Medium |
| Add FERPA context note | Legal/Compliance | Medium |
| Specify NY 8 NYCRR 121.9 timeline | Legal/Compliance | Medium |
| Clarify breach classification logic | Document Owner | Medium |
| Expand acronyms | Document Owner | Low |
| Reference ANNEX-003 for complete state coverage | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The School Breach Notification Procedure provides a comprehensive framework for managing breach notifications in the EdTech context. The procedure correctly positions the vendor role in supporting schools' parent notification obligations while addressing direct vendor obligations to schools and regulators. The multi-tiered notification approach (initial, update, final) is appropriate, and the severity assessment criteria are practical. The primary concerns relate to timeline placeholder completion, encrypted device breach treatment clarification, and the need for subprocessor breach guidance. The state AG notification table should either be expanded or explicitly reference ANNEX-003 for complete coverage. With these enhancements, the procedure will effectively guide breach response and notification activities.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
