# RES-POL-003: Breach Notification (Schools) Policy - Consolidated Review

**Policy File:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/resilience_policies/RES-POL-003.md`
**Review Date:** 2026-01-18
**Reviewers:** EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- The breach definition (Section 3.1) appropriately covers EdTech-relevant scenarios including ransomware affecting student data systems
- Notification timelines (Section 3.2) include placeholder values that can be customized based on DPA requirements and state laws
- The distinction between vendor notification to schools and school notification to parents (Section 3.5.2) correctly reflects the FERPA responsibility model
- State-specific timeline table (Section 3.2.2) addresses key states with student data breach notification requirements

**Technical Observations:**
- The notification content requirements (Section 3.3) cover essential information schools need for their own response
- Cross-functional team composition (Section 3.7.2) appropriately includes Student Data Privacy Officer role
- Testing and preparedness requirements (Section 3.9) ensure operational readiness
- Contact maintenance (Section 3.9.2) addresses a common failure point in breach notification

**Recommendations:**
- Consider adding guidance on breach scenarios specific to rostering integrations (Clever, ClassLink breaches)
- Add considerations for breaches affecting third-party sub-processors
- Include guidance on notification when breach occurs at a shared infrastructure provider (cloud service provider)

### Practical Implementation Feasibility

**Strengths:**
- The notification process table (Section 3.4.2) provides clear role assignments and timelines
- Multiple communication channels (Section 3.4.3) ensure notification can reach schools effectively
- Documentation requirements (Section 3.4.4) support regulatory compliance and legal defensibility
- Post-breach activities (Section 3.8) include appropriate follow-up steps

**Concerns:**
- The "within hours" timeline for drafting notifications (Section 3.4.2) may be challenging for complex incidents
- Consider adding guidance on when preliminary vs. detailed notifications are appropriate
- Response time commitments should be tested through tabletop exercises before commitment

### Integration with Existing EdTech Operations

**Strengths:**
- Clear integration with RES-POL-001 (Incident Response Policy)
- Cross-reference to state privacy law matrix (ANNEX-003) for detailed state requirements
- Reference to RES-PROC-004 (School Breach Notification Procedure) provides operational detail
- Customer Success involvement ensures relationship management during crisis

**EdTech SME Verdict:** APPROVED WITH MINOR CHANGES
- Add rostering provider breach scenario guidance
- Include cloud service provider breach considerations
- Clarify preliminary vs. detailed notification timing

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**FERPA Compliance:**
- Section 3.5.2 correctly identifies that under FERPA, schools (not vendors) are responsible for parent notification
- The vendor's role in supporting school notifications is appropriately framed
- Reference to 34 CFR 99.33(a)(2) in Section 4 is accurate for breach-related FERPA provisions
- The policy correctly recognizes school's obligation to maintain record of disclosure

**COPPA Compliance:**
- Section 3.6.2 appropriately addresses FTC notification considerations for breaches involving children under 13
- Reference to 16 CFR 312.8 security requirements is accurate
- Consideration for FTC inquiry preparation is appropriate given enforcement trends

**State Law Compliance:**
- New York: 8 NYCRR 121.9 correctly cited for breach notification requirements
- State Attorney General notification thresholds are accurately represented
- The acknowledgment that DPA terms may specify different timelines (Section 3.2.1 note) is important

### Citation Correctness

| Citation | Verification |
|----------|--------------|
| 34 CFR 99.33(a)(2) | CORRECT - FERPA requirements for re-disclosure and breach |
| 16 CFR 312.8 | CORRECT - COPPA confidentiality and security |
| 8 NYCRR 121.9 | CORRECT - NY breach notification for educational agencies |
| SOC 2 CC7.4-CC7.5 | CORRECT - Incident response criteria |

**Citation Recommendations:**
- Consider adding general state breach notification law framework citation (state-specific)
- Add reference to FTC COPPA enforcement actions/guidance
- Include California Civil Code 1798.82 reference for CA breach notification

### State Law Coverage Adequacy

**Well Covered:**
- New York (8 NYCRR 121.9 with specific requirements)
- California (AG notification threshold)
- Colorado (30-day timeline, AG notification)
- Connecticut (60-day timeline, AG notification)
- Texas (60-day timeline, AG notification threshold)

**Analysis:**
- The state-specific timeline table (Section 3.2.2) covers major states with student-specific requirements
- Reference to ANNEX-003 for complete requirements is appropriate
- The policy correctly distinguishes between vendor and school notification obligations by state

**Gaps:**
- Consider adding Florida student data breach requirements
- Virginia Consumer Data Protection Act breach provisions
- Massachusetts 201 CMR 17.00 data breach requirements (stringent)

**Regulatory SME Verdict:** APPROVED WITH MINOR CHANGES
- Add California Civil Code 1798.82 citation
- Consider adding Massachusetts, Florida, Virginia to state table
- Reference FTC COPPA enforcement guidance

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Clear distinction between security incident, suspected breach, and confirmed breach (Section 3.1.2)
- Notification content sections (3.3.1, 3.3.2, 3.3.3) provide clear checklists for initial, updated, and final reports
- The "who notifies" column in state tables clarifies vendor vs. school responsibilities
- Section 3.5 (Supporting Schools) demonstrates appropriate service orientation

**Areas for Improvement:**
- Section 3.2.1 timeline table uses placeholders extensively - consider providing recommended values as guidance
- The phrase "promptly; within timeframe specified in 8 NYCRR 121.9" (Section 3.2.2) could be more specific
- Consider adding a visual timeline or flowchart for the notification process

### Consistent Terminology

**Consistency Check:**
- "Breach" consistently defined and used
- "Security incident" distinguished from "breach" appropriately
- "Notification" used consistently for external communications
- "Student data" used consistently throughout

**Terminology Observations:**
- Good distinction between "initial notification," "updated notification," and "final report"
- "Substitute notification" is defined but could use an example
- Consider clarifying "regulatory notification" vs "school notification" more explicitly in definitions

### Format and Structure Compliance

**Template Adherence:**
- All required sections present and properly numbered
- Consistent placeholder formatting
- Appropriate heading hierarchy

**Formatting Strengths:**
- Effective tables for timelines, notification responsibilities, and state requirements
- Clear numbered steps in notification process
- Logical progression from incident classification through post-breach activities

**Minor Issues:**
- Section 3.8.4 documentation retention placeholder format could be more specific about what "legal requirements" might specify

**Technical Editor Verdict:** APPROVED WITH MINOR CHANGES
- Add recommended timeline values in Section 3.2.1
- Provide substitute notification example
- Consider adding notification process flowchart

---

## Stage 7: QA Validation

### Cross-Reference Accuracy

**Verified Cross-References:**
| Reference | Status | Notes |
|-----------|--------|-------|
| RES-POL-001: Incident Response Policy | VERIFY | Core incident response |
| RES-POL-002: Business Continuity Policy | VERIFY | Continuity framework |
| STU-POL-001: Student Data Governance Policy | VERIFY | Student data foundation |
| PRV-POL-003: State Privacy Laws Policy | VERIFY | State requirements |
| SEC-POL-001: Information Security Policy | VERIFY | Security framework |
| ANNEX-003: State Privacy Law Matrix | VERIFY | State-specific requirements |
| RES-PROC-004: School Breach Notification Procedure | VERIFY | Operational procedure |

**Cross-Reference Observations:**
- Strong integration with incident response framework (RES-POL-001)
- Appropriate dependency on ANNEX-003 for state-specific details
- Procedure document (RES-PROC-004) should contain detailed operational steps

### Template Completeness

**Checklist:**
- [x] Title and policy ID present
- [x] Objective section (Section 1)
- [x] Scope section (Section 2)
- [x] Policy content (Section 3) - comprehensive with 9 subsections
- [x] Standards Compliance matrix (Section 4)
- [x] Definitions table (Section 5) - includes 5 key terms
- [x] Responsibilities matrix (Section 6) - covers 6 roles
- [x] Related Documents list (Section 7)
- [x] Policy Review section (Section 8)
- [x] Policy Owner placeholder
- [x] Last Reviewed/Next Review date placeholders

**Completeness Score:** 100% - All template elements present

### Publication Readiness

**Pre-Publication Checklist:**
- [x] Breach definition comprehensive
- [x] Notification timelines specified (with placeholders)
- [x] Content requirements for each notification type
- [x] Process steps clearly defined
- [x] School support provisions included
- [x] State-specific requirements addressed
- [x] Testing/preparedness requirements included

**Outstanding Items Before Publication:**
1. Fill in all [Company Name] placeholders
2. Set notification timeline values in Section 3.2.1:
   - Initial notification: recommend 24-48 hours
   - Updated notification: recommend 48-72 hours
   - Final report: recommend 30 days
3. Set documentation retention period in Section 3.8.4 (recommend 7 years)
4. Fill in Policy Owner, Last Reviewed, and Next Review dates
5. Verify all cross-referenced documents exist, especially:
   - RES-POL-001: Incident Response Policy
   - ANNEX-003: State Privacy Law Matrix
   - RES-PROC-004: School Breach Notification Procedure
6. Verify approval role in Section 3.4.2

**QA Validation Verdict:** APPROVED WITH MINOR CHANGES
- Fill placeholder values with recommended industry-standard timelines
- Verify cross-referenced documents exist
- Ensure RES-POL-001 integration is complete

---

## Consolidated Verdict

### VERDICT: APPROVED WITH MINOR CHANGES

**Summary of Required Changes:**

1. **Technical/Operational:**
   - Add rostering provider breach scenario guidance (Clever, ClassLink incidents)
   - Include cloud service provider breach considerations
   - Clarify preliminary vs. detailed notification timing expectations
   - Test notification timelines through tabletop exercises

2. **Regulatory/Legal:**
   - Add California Civil Code 1798.82 citation
   - Consider adding Massachusetts, Florida, Virginia to state requirements table
   - Reference FTC COPPA enforcement guidance on breach response

3. **Editorial:**
   - Provide recommended timeline values in Section 3.2.1 (24h/48h/30d)
   - Add substitute notification example
   - Consider adding notification process flowchart for clarity

4. **Publication (Required):**
   - Fill all placeholder values:
     - Initial notification: 24 hours
     - Updated notification: 48 hours
     - Final report: 30 days
     - Documentation retention: 7 years
   - Verify cross-referenced documents exist:
     - RES-POL-001 (Incident Response)
     - ANNEX-003 (State Privacy Law Matrix)
     - RES-PROC-004 (Procedure)
   - Fill Policy Owner and review dates

**Risk Assessment:** LOW - The policy provides comprehensive breach notification framework that addresses FERPA, COPPA, state law, and contractual requirements. The clear delineation between vendor and school responsibilities is particularly valuable.

**Compliance Confidence:** HIGH
- FERPA responsibility model correctly implemented
- COPPA considerations for under-13 breaches included
- State-specific requirements comprehensively addressed
- SOC 2 incident response criteria integrated

**Critical Dependency:** This policy must be tested alongside RES-POL-001 (Incident Response Policy) to ensure seamless integration during actual incidents. Annual tabletop exercises (Section 3.9.1) should include school notification scenarios.

**Regulatory Note:** Breach notification laws continue to evolve. This policy should be flagged for review when new state student data breach notification requirements are enacted or when FTC updates COPPA guidance.
