# ENG-POL-004: Age-Appropriate Design Policy - Consolidated Review

**Policy File:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/engineering_policies/ENG-POL-004.md`
**Review Date:** 2026-01-18
**Reviewers:** EdTech Controls SME, FERPA/COPPA Regulatory SME, Technical Editor, QA Validation

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- The age tier classification (Section 3.1.1) accurately reflects the regulatory landscape: under-13 (COPPA), 13-15 (teens), 16-17 (older teens), 18+ (adults)
- Age verification methods (Section 3.1.2) correctly prioritize authoritative school roster data over self-reported ages
- The neutral age verification requirement prevents dark patterns that encourage false age claims
- Privacy by default settings (Section 3.2.1) appropriately differentiate between minor and adult defaults

**Technical Observations:**
- The advertising restrictions (Section 3.4) correctly distinguish between behavioral and contextual advertising
- SOPIPA prohibition on advertising to students in school-contracted services is accurately captured
- Social feature restrictions (Section 3.6) appropriately escalate with age
- AI/algorithmic content moderation requirements (Section 3.8.2) address emerging concerns about AI in education

**Recommendations:**
- Consider adding specific guidance on age verification for mixed-age household situations (e.g., parent and student using same device)
- The push notification timing restriction (Section 3.9.1) could benefit from specific school hour definitions or time zone considerations
- Add guidance on handling students who age across tiers during the school year

### Practical Implementation Feasibility

**Strengths:**
- Default settings approach minimizes implementation burden while maximizing protection
- Parental and school dashboards (Section 3.7) are feasible for most EdTech platforms
- The prohibition on dark patterns (Section 3.5.2) provides clear implementation guidance
- Content moderation requirements are tiered appropriately by risk

**Concerns:**
- Requirement for "human oversight of AI interactions with minors" (Section 3.8.2) may be challenging at scale for AI-powered tutoring systems
- Consider adding guidance on acceptable AI oversight ratios or sampling approaches
- Real-time caption requirements for live events may need feasibility caveats for smaller organizations

### Integration with Existing EdTech Operations

**Strengths:**
- Clear cross-references to COPPA Compliance Policy (PRV-POL-002)
- Integration with secure development (ENG-POL-001) and accessibility (ENG-POL-005)
- Role responsibilities clearly defined across Product, Design, Engineering, and QA
- Reference to ENG-PROC-007 (Age-Appropriate Design Review Procedure) provides operational linkage

**EdTech SME Verdict:** APPROVED WITH MINOR CHANGES
- Add guidance for age transitions during school year
- Clarify AI oversight scalability requirements
- Add mixed-age household device considerations

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**COPPA Compliance (16 CFR Part 312):**
- Section 3.3.1 correctly captures COPPA's key requirements:
  - Collection limited to what's necessary (16 CFR 312.4)
  - No conditioning participation on unnecessary collection (16 CFR 312.7)
  - No persistent identifiers for behavioral advertising (16 CFR 312.5)
  - Geolocation restrictions align with COPPA guidance
- Parent-managed accounts for under-13 users supports verifiable parental consent framework

**SOPIPA Compliance:**
- Section 3.4.3 correctly prohibits advertising to students in school-contracted services
- The no-profile-building restriction aligns with SOPIPA requirements

**UK AADC Reference:**
- The reference to UK Age Appropriate Design Code principles (Section 4) is appropriate as industry best practice
- While not legally binding in US, many states are adopting similar requirements

**State Law Considerations:**
- California Age-Appropriate Design Code Act (effective 2024) alignment should be verified
- Connecticut's CTDPA has specific provisions for children's data
- Colorado Privacy Act includes provisions for minors

### Citation Correctness

| Citation | Verification |
|----------|--------------|
| 16 CFR Part 312 | CORRECT - COPPA regulations |
| SOPIPA | CORRECT - California Student Online Personal Information Protection Act |
| UK AADC | CORRECT - UK Age Appropriate Design Code (referenced as principles, not requirement) |
| FTC guidance (dark patterns) | CORRECT - FTC has issued guidance on dark patterns affecting children |

**Citation Recommendations:**
- Add specific COPPA rule section references (e.g., 16 CFR 312.4 for notice requirements)
- Consider adding California Age-Appropriate Design Code Act (Cal. Civ. Code 1798.99.28 et seq.)

### State Law Coverage Adequacy

**Well Covered:**
- California SOPIPA requirements
- COPPA federal requirements
- Industry best practices (UK AADC)

**Gaps:**
- California AADC (effective 2024) should be explicitly addressed
- State laws with specific age-appropriate design requirements (e.g., Maryland's Age-Appropriate Design Code)
- Consider adding reference to FTC's anticipated updates to COPPA rules

**Regulatory SME Verdict:** APPROVED WITH MINOR CHANGES
- Add California AADC citation and alignment confirmation
- Include specific COPPA rule section references
- Consider FTC enforcement trends in dark patterns

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Excellent use of comparative tables (e.g., Section 3.2.1 comparing minor vs adult defaults)
- Age-tier structure provides clear decision framework
- "SHALL" and "SHALL NOT" language provides clear obligations
- Section 3.5.2 Dark Patterns prohibition uses concrete examples

**Areas for Improvement:**
- Section 3.8.2 phrase "AI-generated or recommended content" could benefit from examples
- The term "high-risk features" (Section 3.2.2) could use a brief definition or examples
- Consider adding a quick-reference chart summarizing requirements by age tier

### Consistent Terminology

**Consistency Check:**
- "Minors" is used consistently for users under 18
- "Children under 13" and "under-13" used consistently for COPPA scope
- "Behavioral advertising" vs "targeted advertising" - both used in Section 3.4.1; clarify distinction or consolidate

**Terminology Recommendations:**
- Standardize "under-13" format (hyphenated) throughout
- Section 3.4.1 uses both "behavioral advertising" and "targeted advertising" - clarify these are related but distinct concepts, or consolidate
- Consider defining "sensitive categories" (Section 3.3.2) either in definitions or inline

### Format and Structure Compliance

**Template Adherence:**
- All required sections present and properly numbered
- Consistent use of [Company Name] placeholder
- Appropriate heading hierarchy

**Formatting Strengths:**
- Effective use of bold for emphasis
- Tables well-formatted with clear headers
- Bullet lists consistently formatted

**Minor Issues:**
- Section 3.9.2 mixing "SHALL NOT" and "SHOULD" - ensure this distinction is intentional and clear

**Technical Editor Verdict:** APPROVED WITH MINOR CHANGES
- Clarify behavioral vs targeted advertising terminology
- Add examples for "high-risk features"
- Define "sensitive categories" in definitions section

---

## Stage 7: QA Validation

### Cross-Reference Accuracy

**Verified Cross-References:**
| Reference | Status | Notes |
|-----------|--------|-------|
| STU-POL-001: Student Data Governance Policy | VERIFY | Core student data policy |
| PRV-POL-002: COPPA Compliance Policy | VERIFY | COPPA-specific policy |
| ENG-POL-001: Secure Software Development Policy | VERIFY | Development standards |
| ENG-POL-005: Accessibility Standards Policy | VERIFY | Reviewed in this batch |
| ENG-PROC-007: Age-Appropriate Design Review Procedure | VERIFY | Procedure document |

**Cross-Reference Observations:**
- Cross-reference to ENG-POL-005 (Accessibility) is appropriate as age-appropriate design intersects with accessibility
- Policy ID numbering is consistent (ENG-POL-004 and ENG-POL-005 are sequential)

### Template Completeness

**Checklist:**
- [x] Title and policy ID present
- [x] Objective section (Section 1)
- [x] Scope section (Section 2)
- [x] Policy content (Section 3) - comprehensive with 9 subsections
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
- [x] Comprehensive coverage of age tiers
- [x] Clear implementation guidance
- [x] Appropriate regulatory citations
- [x] Well-structured tables and lists
- [x] Consistent placeholder usage

**Outstanding Items Before Publication:**
1. Fill in all [Company Name] placeholders
2. Fill in Policy Owner, Last Reviewed, and Next Review dates
3. Verify all cross-referenced documents exist in final policy set
4. Confirm California AADC compliance alignment

**QA Validation Verdict:** APPROVED WITH MINOR CHANGES
- Verify all cross-referenced documents exist
- Add "sensitive categories" to definitions
- Ensure regulatory alignment with California AADC is confirmed

---

## Consolidated Verdict

### VERDICT: APPROVED WITH MINOR CHANGES

**Summary of Required Changes:**

1. **Technical/Operational:**
   - Add guidance for age transitions during school year
   - Clarify AI oversight scalability expectations
   - Add mixed-age household device considerations
   - Define school hours for notification timing or allow configuration

2. **Regulatory/Legal:**
   - Add California AADC (Cal. Civ. Code 1798.99.28) citation
   - Include specific COPPA rule section references
   - Consider Maryland AADC and other emerging state laws

3. **Editorial:**
   - Clarify distinction between behavioral and targeted advertising
   - Add definition for "sensitive categories" to Section 5
   - Provide examples for "high-risk features"

4. **Publication:**
   - Fill all placeholder values before final publication
   - Verify all cross-referenced documents exist
   - Confirm regulatory alignment with 2024-2025 state law changes

**Risk Assessment:** LOW - Policy provides comprehensive coverage of age-appropriate design requirements. Changes are refinements to an already strong framework that addresses both current regulations and emerging best practices.

**Special Note:** This policy should be flagged for review when FTC issues updated COPPA rules (anticipated) and when additional states adopt age-appropriate design requirements.
