# ENG-PROC-008: Accessibility Testing and Remediation Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/engineering_procedures/ENG-PROC-008.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Correctly identifies WCAG 2.1 AA as the target standard, which is the predominant requirement in K-12 and higher education procurement
- Tool references (axe-core, Lighthouse) are industry-standard and appropriate for web-based EdTech products
- Screen reader testing requirements (Section 3.2.2) correctly identify NVDA and VoiceOver as priority readers
- VPAT maintenance (Section 3.5) addresses a critical EdTech sales requirement

**Concerns:**
- No mention of mobile accessibility testing (critical for K-12 EdTech where tablet and phone use is common)
- Section 508 referenced but not explained - relationship to WCAG should be clarified for teams
- No specific guidance for interactive learning content (simulations, drag-and-drop activities, educational games) which have unique accessibility challenges
- Missing guidance on accessibility of embedded third-party content (common in EdTech - videos, LTI tools)

### Practical Implementation Feasibility

**Strengths:**
- CI/CD integration approach (Section 3.1.1) enables automated ongoing testing
- Severity categorization (Section 3.1.2) provides clear prioritization for release decisions
- Priority assignment framework (Section 3.3.1) balances user impact with development resources
- Accommodation request process (Section 3.6) addresses customer-facing accessibility needs

**Concerns:**
- "Test as child user" (Section 3.4.1 - from referenced procedure) isn't mentioned here but age-appropriate accessibility testing should be considered
- Section 3.2.2 requires testing with "at least 2 screen readers" but doesn't specify coverage across platforms (Mac + Windows)
- No guidance on testing frequency for production monitoring
- Third-party audit annually (Section 3.4) is appropriate but no guidance on budget or scope determination

### Operational Workflow Clarity

**Strengths:**
- Clear integration points with development workflow (PR, staging, production)
- Issue categorization and priority frameworks are actionable
- VPAT update triggers are specific (annually and after major releases)
- Accommodation request process has clear steps

**Concerns:**
- Section 3.2.1 keyboard testing doesn't specify who is qualified to perform this testing
- No SLA for accommodation request response
- Missing handoff process between automated testing results and manual testing
- No guidance on regression testing after fixes

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Add mobile accessibility testing requirements
- Add interactive content testing guidance
- Add third-party content accessibility requirements
- Specify accommodation request SLA

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Section 508 reference is appropriate for EdTech serving federal agencies or receiving federal funding
- WCAG 2.1 AA is the appropriate standard for educational technology
- Accommodation request process supports equal access requirements

**Note:** This procedure primarily addresses disability/accessibility law rather than FERPA/COPPA. The regulatory review will focus on the intersection points.

**Concerns:**
- No mention of ensuring accessibility features don't compromise student data privacy (e.g., screen reader access to student information)
- Accommodation requests may involve students with disabilities - FERPA applies to documentation of these accommodations
- Student accommodation records may be education records - retention and access considerations not addressed

### Proper Support for Regulatory Requirements

**Accessibility Law Compliance:**
- WCAG 2.1 AA target is appropriate for ADA/Section 508 compliance
- VPAT documentation supports procurement requirements
- Annual audit cycle supports ongoing compliance verification

**Privacy Intersection Points:**
- Accommodation records retention (5 years per Section 5) is reasonable but should consider FERPA if student-specific
- Support system storage for accommodation records should have appropriate access controls
- Third-party auditor access to test environments may involve student data - access controls should apply

**Documentation:**
- Audit report retention (5 years) is appropriate
- VPAT permanent retention is appropriate for procurement documentation

**Regulatory Recommendations:**
- Add note about FERPA considerations for student-specific accommodation records
- Ensure test environments for accessibility audits use anonymized or synthetic data
- Add access controls for accommodation request records

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Primary accessibility focus is appropriate
- Minor additions for privacy intersection points

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Well-organized progression through testing types (automated > manual > remediation)
- Tables effectively summarize severity levels and impact factors
- Specific tool references add clarity
- Action-oriented steps throughout

**Concerns:**
- Section 3.1.1 assumes reader knows what axe-core and Lighthouse are - brief explanation or link helpful
- Section 3.2.2 "Test as child user" appears to be cut-and-paste error from age-appropriate procedure - should be "Test as screen reader user"
- Some technical terms used without explanation (ARIA, VPAT, NVDA)
- Section 3.3.3 "Documenting Remediation" overlaps with 3.3.2 Step 5 "Close ticket"

### Step-by-Step Flow Logic

**Strengths:**
- Logical flow from detection through remediation to documentation
- Clear distinction between automated and manual testing
- Remediation prioritization framework is practical
- VPAT maintenance positioned appropriately after remediation

**Concerns:**
- Section 3.1.2 "Interpreting Scan Results" Step 3 "Create tickets" seems like it should come before prioritization, not after
- No explicit gate between identifying issues and beginning remediation
- Third-party audit (Section 3.4) doesn't clearly connect back to remediation process
- Accommodation requests (Section 3.6) seems disconnected from testing/remediation flow

### Consistent Terminology

**Findings:**
- "Accessibility" used consistently
- "WCAG" used without initial expansion
- "VPAT" used without expansion (Voluntary Product Accessibility Template)
- "ARIA" used without explanation (Accessible Rich Internet Applications)
- "axe-core" correctly lowercase, "Lighthouse" correctly capitalized
- Severity levels (Critical, Serious, Moderate, Minor) used consistently

**Terminology Recommendations:**
- Expand WCAG, VPAT, ARIA, NVDA on first use
- Add brief tool descriptions or links
- Consider adding glossary reference

### Editorial Recommendations

1. Expand acronyms on first use (WCAG, VPAT, ARIA, NVDA)
2. Add brief descriptions for testing tools
3. Correct "Test as child user" to "Test as screen reader user" in Section 3.2.2 if applicable
4. Reorder Section 3.1.2 to put ticket creation before prioritization
5. Add explicit remediation start gate
6. Consider removing overlap between 3.3.2 and 3.3.3

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| ENG-POL-005 | Accessibility Standards Policy | To be verified at publication |
| WCAG 2.1 Guidelines | External standard | Valid external reference |
| Section 508 Standards | External standard | Valid external reference |

**Cross-Reference Notes:**
- Policy reference follows naming convention
- External standards are valid and current
- Limited internal references (appropriate for specialized procedure)

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- Minimal placeholders (excellent)
- All procedure sections present
- Records retention has specific systems identified
- Testing tools specifically named

### Publication Readiness

**Document Structure:**
- Markdown formatting valid
- Header hierarchy correct
- Tables properly formatted with consistent columns
- Lists properly numbered

**Content Completeness:**
- Full testing cycle covered (automated, manual, audit)
- Remediation workflow complete
- VPAT maintenance addressed
- Accommodation process included

**Tool Dependencies:**
- axe-core and Lighthouse require implementation in testing framework
- CI/CD pipeline integration assumed
- Screen reader access required for manual testing
- Issue tracking system referenced but not specified

**Outstanding Items Before Publication:**
- [ ] Complete placeholder values
- [ ] Verify ENG-POL-005 Accessibility Standards Policy exists
- [ ] Confirm axe-core and Lighthouse are configured in CI/CD
- [ ] Validate screen reader testing capability exists
- [ ] Verify VPAT template is available
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. Mobile accessibility testing not addressed (EdTech SME)
2. Interactive learning content testing guidance missing (EdTech SME)
3. Third-party embedded content not addressed (EdTech SME)
4. FERPA considerations for accommodation records (Regulatory SME)
5. Test environment data privacy for audits (Regulatory SME)
6. Acronyms not expanded (Technical Editor)
7. Possible copy error "Test as child user" (Technical Editor)
8. Section ordering could be improved in 3.1.2 (Technical Editor)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Add mobile accessibility testing requirements | QA/Engineering | High |
| Add interactive content testing guidance | QA/Product | Medium |
| Add third-party content accessibility requirements | Engineering | Medium |
| Expand all acronyms on first use | Document Owner | Medium |
| Add FERPA note for accommodation records | Privacy/Legal | Low |
| Verify and correct "Test as child user" reference | Document Owner | Low |
| Reorder ticket creation before prioritization | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The Accessibility Testing and Remediation Procedure provides a solid framework for ensuring EdTech products meet WCAG 2.1 AA accessibility standards. The procedure effectively integrates automated and manual testing approaches, provides clear remediation prioritization, and addresses the critical VPAT documentation requirement for EdTech sales. The accommodation request process demonstrates commitment to user accessibility needs. The primary gaps relate to mobile accessibility and interactive content testing, which are significant for modern EdTech products. With the identified enhancements, this procedure will comprehensively support accessibility compliance in the EdTech context.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
