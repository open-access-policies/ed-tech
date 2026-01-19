# ENG-PROC-007: Age-Appropriate Design Review Procedure - Expert Reviews

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/engineering_procedures/ENG-PROC-007.md`
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Correctly addresses the K-12 EdTech reality of mixed-age user populations
- Privacy defaults table (Section 3.2.1) reflects industry best practices (profile private, location off, contact from strangers blocked)
- Dark patterns checklist (Section 3.2.3) addresses growing regulatory concern in children's online services
- Annual feature review (Section 3.6) acknowledges the evolving regulatory and best practice landscape

**Concerns:**
- Section 3.1.1 distinguishes "under 13" and "13-17" but does not address the unique considerations for very young users (e.g., pre-K, early elementary)
- No mention of classroom/teacher context vs. individual student context for feature design
- Section 3.2.1 "Personalization: Minimal" is vague - should clarify what types of personalization are appropriate vs. problematic
- Missing guidance on AI/ML features and automated decision-making involving children's data (increasingly relevant in EdTech)

### Practical Implementation Feasibility

**Strengths:**
- Pre-development review (Section 3.1) appropriately gates feature development
- Design requirements checklist (Section 3.2) provides specific, verifiable criteria
- Pre-launch checklist (Section 3.5.1) ensures comprehensive verification before release
- Testing procedures (Section 3.4) include specific test scenarios for different age groups

**Concerns:**
- Section 3.1.2 Design Review Meeting requires "include Product, Design, Privacy, Engineering" - this may be heavyweight for minor features
- No threshold or criteria for determining what constitutes a feature that needs age-appropriate review vs. routine development
- Section 3.3.1 "Code Review for Age Compliance" adds review burden but doesn't specify who is qualified to perform this review
- No guidance on retrofitting existing features that may not have gone through this process

### Operational Workflow Clarity

**Strengths:**
- Clear "When" triggers identify review initiation points
- Multi-stage review process (pre-development > design > implementation > testing > launch) is comprehensive
- Escalation criteria are specific to age-related risks

**Concerns:**
- No estimated timeline for the full review process
- Section 3.3.1 code review could create bottleneck if Privacy Officer required for all changes
- Missing procedure for handling urgent feature releases or hotfixes
- No guidance on integrating with existing sprint/agile processes

**SME Recommendation:** APPROVED WITH MINOR CHANGES
- Add threshold criteria for when full review is required
- Add guidance on very young user considerations
- Clarify personalization restrictions
- Add AI/ML feature guidance

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Correctly addresses COPPA data minimization requirement (Section 3.2.2)
- "Conditioning participation on extra collection" prohibition is accurate COPPA principle
- Under-13 Privacy Officer approval requirement (Section 3.5.1) provides appropriate oversight
- Parental/school consent verification in code review (Section 3.3.1) addresses COPPA consent flow requirements

**Concerns:**
- No explicit reference to COPPA's prohibition on retaining children's personal information longer than reasonably necessary
- Section 3.2.1 defaults table doesn't address data retention or automatic deletion settings
- Limited mention of FERPA's legitimate educational interest standard for feature data access
- No guidance on features that might involve de-identified or aggregate data (which have different COPPA/FERPA treatment)

### Proper Support for Regulatory Requirements

**Data Collection:**
- Necessity analysis (Section 3.2.2) aligns with COPPA minimization
- Collection justification documentation requirement is appropriate
- No explicit reference to COPPA's "reasonably necessary" standard

**Privacy by Design:**
- Privacy-protective defaults properly addressed
- Opt-in requirement for privacy-reducing features is correct approach
- Parent/school consent requirement for setting changes is appropriate

**Child Safety:**
- Reporting mechanisms requirement addresses child safety
- Blocking capabilities included
- Parental/teacher controls addressed
- Contact from strangers blocked by default is appropriate

**Notice and Transparency:**
- Age-appropriate language requirement is good practice
- Clear consequences explanation aligns with transparency principles

**Regulatory Recommendations:**
- Add data retention considerations to defaults
- Reference COPPA's "reasonably necessary" collection standard explicitly
- Add de-identified/aggregate data guidance
- Consider adding reference to FERPA's legitimate educational interest for data features

**Regulatory SME Recommendation:** APPROVED WITH MINOR CHANGES
- Strong age-appropriate design framework
- Minor additions for data retention and regulatory terminology alignment

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Clear progression through software development lifecycle
- Effective use of tables for settings and criteria
- Pre-launch checklist format with checkboxes is clear and auditable
- Consistent section structure throughout

**Concerns:**
- Section 3.1.1 questions are all rhetorical (e.g., "Will children under 13 use this feature?") - would be clearer as a checklist
- Section 3.2.3 "Check for dark patterns" list items all begin with "No" which creates repetitive reading
- Section 3.4.1 testing scenarios are helpful but could use acceptance criteria
- Some overlap between Section 3.1 (Pre-Development) and Section 3.2 (Design Requirements) on data collection assessment

### Step-by-Step Flow Logic

**Strengths:**
- Logical progression: assess > design > implement > test > launch > review
- Each phase has clear entry and exit criteria
- Approval gates are positioned appropriately

**Concerns:**
- Section 3.1.2 Step 5 "Obtain approval to proceed" comes after "Identify required changes" but those changes haven't been made yet - flow is slightly confusing
- No explicit gate between implementation (3.3) and testing (3.4)
- Section 3.6.1 Annual Feature Review could trigger changes but doesn't link back to the pre-development process for those changes
- Missing explicit "stop/no-go" criteria beyond Privacy Officer involvement

### Consistent Terminology

**Findings:**
- "Minors" vs. "children" used somewhat interchangeably (both acceptable but consider standardizing)
- "Under 13" and "13-17" age brackets consistently used
- "Privacy Officer" used consistently
- "Dark patterns" term used without definition (widely understood but could add brief explanation)
- "Age-appropriate" defined through context rather than explicit definition

**Terminology Recommendations:**
- Consider standardizing on "children" vs. "minors" or define both
- Add brief dark patterns definition or reference
- Explicitly define what "age-appropriate" means in this context

### Editorial Recommendations

1. Reformat Section 3.1.1 questions as a checklist
2. Reframe Section 3.2.3 dark pattern items positively or as verification statements
3. Add acceptance criteria to testing scenarios
4. Add brief dark patterns definition
5. Clarify approval flow in Section 3.1.2

**Technical Editor Recommendation:** APPROVED WITH MINOR CHANGES

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

| Reference | Target Document | Verified |
|-----------|-----------------|----------|
| ENG-POL-004 | Age-Appropriate Design Policy | To be verified at publication |
| PRV-POL-002 | COPPA Compliance Policy | To be verified at publication |
| ENG-POL-001 | Secure Software Development Policy | To be verified at publication |

**Cross-Reference Notes:**
- Three policy references establish appropriate governance context
- Reference to Secure Software Development Policy appropriately links age design to overall SDLC
- All references follow naming convention

### Template Completeness

| Placeholder | Status | Notes |
|-------------|--------|-------|
| [Date] | Placeholder | Revision History |
| [Author] | Placeholder | Revision History |

**Completeness Assessment:**
- Minimal placeholders (good)
- All procedure sections present
- Pre-launch checklist is comprehensive
- No incomplete procedures or missing steps

### Publication Readiness

**Document Structure:**
- Markdown formatting valid throughout
- Header hierarchy correct
- Tables properly formatted
- Checkbox format in Section 3.5.1 renders correctly

**Content Completeness:**
- Full SDLC coverage from feature proposal through post-launch review
- Multiple review gates at appropriate stages
- Testing procedures specific to age considerations
- Annual review cycle included

**Process Integration:**
- Procedure integrates with product development workflow
- QA team explicitly included in scope
- Design team involvement specified
- Engineering code review process referenced

**Outstanding Items Before Publication:**
- [ ] Complete placeholder values
- [ ] Verify referenced policies exist
- [ ] Confirm Privacy Officer role and availability for reviews
- [ ] Validate integration with existing SDLC process
- [ ] Set version and publication date

**QA Validation Recommendation:** APPROVED WITH MINOR CHANGES

---

## Consolidated Review Summary

### Findings by Severity

**Critical Issues:** None identified

**Major Issues:** None identified

**Minor Issues:**
1. No threshold for determining when full age-appropriate review required (EdTech SME)
2. Missing very young user (pre-K) considerations (EdTech SME)
3. AI/ML feature guidance missing (EdTech SME)
4. Data retention not addressed in defaults (Regulatory SME)
5. Section 3.1.1 questions could be reformatted as checklist (Technical Editor)
6. Dark patterns items negative framing is repetitive (Technical Editor)
7. Minor terminology standardization needed (Technical Editor)

### Recommended Actions

| Action | Owner | Priority |
|--------|-------|----------|
| Add feature review threshold criteria | Product/Privacy | Medium |
| Add data retention considerations | Privacy Team | Medium |
| Add AI/ML feature guidance | Engineering/Privacy | Medium |
| Reformat Section 3.1.1 as checklist | Document Owner | Low |
| Add dark patterns definition | Document Owner | Low |
| Standardize child/minor terminology | Document Owner | Low |

---

## FINAL VERDICT: APPROVED WITH MINOR CHANGES

The Age-Appropriate Design Review Procedure provides a comprehensive framework for ensuring products used by children meet privacy and safety standards. The procedure effectively integrates age-appropriate considerations throughout the software development lifecycle, from feature proposal through annual review. The privacy defaults table and dark patterns checklist provide actionable guidance for development teams. The multi-stage review process with appropriate approval gates ensures oversight without being unnecessarily burdensome. Minor enhancements around review thresholds, data retention, and AI/ML features will strengthen the procedure for emerging EdTech challenges.

**Reviewers:**
- EdTech Controls SME: Approved with Minor Changes
- FERPA/COPPA Regulatory SME: Approved with Minor Changes
- Technical Editor: Approved with Minor Changes
- QA Validation: Approved with Minor Changes
