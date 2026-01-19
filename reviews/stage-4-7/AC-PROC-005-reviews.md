# AC-PROC-005: Student Data Access Request Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/access_control_procedures/AC-PROC-005.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Correctly addresses "legitimate educational interest" as the access justification standard (Section 3.2.1), aligning with FERPA requirements
- School-specific data segregation implied in access provisioning (Section 3.3.1 Step 3 "Limit to approved schools/data")
- Emergency access procedure (Section 3.6) addresses real operational needs in EdTech support scenarios
- Audit logging requirements (Section 3.7) support school FERPA compliance obligations

**Concerns:**
- No mention of tenant isolation verification in multi-tenant EdTech SaaS environments
- Section 3.1.1 "Access level (read, write, admin)" is too simplistic for modern EdTech - should include analytics, export, bulk operations
- No guidance on handling access to production vs. sandbox/test data (common EdTech distinction)
- Missing procedures for accessing data for debugging customer issues (common support scenario)

### Practical Implementation Feasibility

**Strengths:**
- Quarterly access review cycle (Section 3.4.1) is practical and achievable
- Role change review (Section 3.4.2) addresses a common access control gap
- 1 business day termination access removal (Section 3.5.1) is achievable with proper tooling
- Elevated access approval chain (Section 3.2.2) appropriately involves Privacy Officer

**Concerns:**
- Section 3.3.1 Step 4 "Notify requestor" lacks detail on what information to communicate
- No service level agreement (SLA) for access request processing time
- Section 3.6.1 emergency access requires "verbal approval" but lacks guidance on verification or after-hours scenarios
- No mention of automation capabilities for common access patterns

### Operational Workflow Clarity

**Strengths:**
- Clear "When" triggers for each procedure
- Logical flow from request through approval to provisioning
- Termination procedures cover both employees and contractors
- Escalation criteria are specific

**Concerns:**
- No workflow for self-service access requests (if applicable)
- Section 3.4.1 "Generate access report" assumes a specific system capability without specifying requirements
- No integration points specified with HR systems for termination notifications
- Missing procedure for temporary access extensions

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Add tenant isolation verification
- Expand access levels to include analytics and export capabilities
- Add SLA for request processing
- Add debug/support access guidance

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- "Legitimate educational interest" standard correctly applied as the access determination criterion
- School-based access limitation supports FERPA's school official requirements
- Audit logging requirements (Section 3.7.1) align with FERPA accountability principles
- Log availability to schools for their FERPA compliance is correctly addressed

**Concerns:**
- Section 3.2.1 Step 2 asks "Would school authorize this access?" - this is the right question but lacks guidance on how to determine the answer
- No explicit requirement that access be limited to data necessary for the specific contracted service
- Section 3.6.1 emergency access should explicitly require documentation of the educational purpose
- Missing requirement to consider whether access constitutes a FERPA "disclosure" requiring logging

### Proper Support for Regulatory Requirements

**Access Limitations:**
- Legitimate educational interest basis correctly established
- School-specific access limitations support FERPA requirements
- Minimum necessary principle implied but could be more explicit

**Audit Trail:**
- Section 3.7.1 logging requirements appropriately comprehensive (user, timestamp, data, action, school context)
- Log protection requirement (tamper-resistant) is appropriate
- School access to logs supports school FERPA compliance

**Documentation:**
- Access request documentation retained appropriately
- Approval chain documented
- Review records maintained

**Termination:**
- Timely access removal requirements are appropriate
- Contractor termination separately addressed

**Regulatory Recommendations:**
- Add explicit minimum necessary principle statement
- Clarify that each access instance should be evaluated for disclosure logging requirement
- Strengthen emergency access educational purpose documentation
- Add requirement to document how "legitimate educational interest" is determined

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Framework supports FERPA compliance
- Minor enhancements to strengthen educational purpose documentation

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Clean, consistent structure throughout
- Short, actionable steps in each procedure
- Tables used sparingly but effectively
- Clear escalation section

**Concerns:**
- Section 3.1.1 "Identify access needed" could benefit from examples
- Some steps are compound (e.g., Section 3.4.1 Step 4 "Remove/reduce access as identified; Notify affected personnel")
- Section title "Student Data Access Request Procedure" could be interpreted as the procedure for students to access their data (vs. procedure for employees to access student data)

### Step-by-Step Flow Logic

**Strengths:**
- Logical progression from request through provisioning to review and termination
- Standard and elevated access paths are clearly distinguished
- Review and termination procedures appropriately positioned after provisioning

**Concerns:**
- No explicit approval timeout - what happens if manager doesn't respond?
- Section 3.4.2 Role Change Review is triggered by role change but doesn't specify who is responsible for initiating
- Section 3.5.2 Contractor termination lacks the same specificity as employee termination (no 1 business day requirement)
- Missing explicit handoff between approval (3.2) and provisioning (3.3)

### Consistent Terminology

**Findings:**
- "Student data" used consistently
- "Workforce member" consistent with policy framework terminology
- "Legitimate educational interest" - FERPA-accurate terminology
- "Privacy Officer" vs. "Student Data Privacy Officer" - both used, should standardize
- "Access team" referenced in Section 3.4.2 but not defined elsewhere

**Terminology Recommendations:**
- Standardize Privacy Officer title throughout
- Define or clarify "access team" reference
- Consider clarifying title to distinguish from student access requests

### Editorial Recommendations

1. Clarify procedure title to avoid ambiguity with student access rights
2. Standardize Privacy Officer title
3. Define "access team" or use consistent role terminology
4. Separate compound steps
5. Add approval timeout guidance

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| AC-POL-003 | Student Data Access Controls Policy | To be verified at publication |
| AC-POL-001 | Logical Access Control Policy | To be verified at publication |
| STU-POL-001 | Student Data Governance Policy | To be verified at publication |

**Cross-Reference Notes:**
- Three policy references establish appropriate policy foundation
- All references follow naming convention
- No external regulatory references (appropriate - regulations covered in policies)

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- Minimal placeholders (good)
- All procedure sections present and complete
- Records table has specific systems named (Access system, SIEM, Compliance files)
- No incomplete steps or orphaned sections

### Publication Readiness

**Document Structure:**
- Markdown formatting valid
- Header hierarchy correct (H1 > H2 > H3 > H4)
- Consistent numbered list formatting
- No formatting errors

**Content Completeness:**
- Full lifecycle coverage (request > approve > provision > review > terminate)
- Emergency access appropriately addressed
- Audit logging requirements comprehensive
- Escalation criteria defined

**Integration Points:**
- References HR system for termination notification - assumes integration exists
- References SIEM for access logs - assumes system exists
- References "access system" generically - may need specific system name

**Outstanding Items Before Publication:**
- [ ] Complete placeholder values
- [ ] Verify referenced policies exist
- [ ] Confirm access system and SIEM are operational
- [ ] Validate HR integration for termination notification
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. Access levels too simplistic for modern EdTech (EdTech SME)
2. No tenant isolation verification (EdTech SME)
3. No SLA for request processing (EdTech SME)
4. Minimum necessary principle should be more explicit (Regulatory SME)
5. Emergency access educational purpose documentation needed (Regulatory SME)
6. Privacy Officer title inconsistent (Technical Editor)
7. Contractor termination timeline less specific than employee (Technical Editor)
8. Procedure title could be clarified (Technical Editor)
9. "Access team" undefined (Technical Editor)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Expand access levels to include analytics, export, bulk operations | Document Owner | Medium |
| Add tenant isolation verification requirement | Security/Engineering | Medium |
| Add explicit minimum necessary principle | Document Owner | Medium |
| Standardize Privacy Officer title | Document Owner | Low |
| Add contractor termination timeline | Document Owner | Low |
| Define or clarify "access team" | Document Owner | Low |
| Consider title clarification | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The Student Data Access Request Procedure provides a solid foundation for managing workforce access to student data. The procedure correctly applies FERPA's "legitimate educational interest" standard and includes appropriate safeguards including elevated access approval, periodic reviews, and audit logging. The lifecycle coverage (request, approve, provision, review, terminate) is comprehensive. Minor enhancements around access level granularity, tenant isolation, and terminology consistency will strengthen the procedure. The emergency access provisions appropriately balance operational needs with privacy protection.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
