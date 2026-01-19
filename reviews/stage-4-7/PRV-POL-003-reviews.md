# PRV-POL-003: State Student Privacy Laws Policy - Expert Review Consolidation

**Policy ID:** PRV-POL-003
**Policy Title:** State Student Privacy Laws Policy
**Review Date:** 2026-01-18
**Review Stages:** 4-7 (EdTech SME, Regulatory SME, Technical Editor, QA)

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Strengths:**
- Comprehensive coverage of major state student privacy laws (California SOPIPA, NY Education Law 2-d, Colorado, Connecticut, Illinois SOPPA, and others)
- Accurate representation of the Student Data Privacy Consortium (SDPC) National DPA as a compliance simplification mechanism
- Correct identification of common prohibited practices across states (sale, targeted advertising, profile building)
- Recognition of state-specific DPA addenda requirements demonstrates operational understanding

**Areas for Improvement:**
- Section 3.1.5 "Other Significant State Laws" table is valuable but could include more states (Texas, Florida, Massachusetts, Georgia have notable laws)
- Should address the California Age-Appropriate Design Code Act (AADC) which takes effect in 2024 and significantly impacts EdTech
- Missing discussion of state attorney general enforcement trends and recent enforcement actions
- Should address multi-district/consortium purchasing agreements and how state law compliance flows through

**Technical Accuracy Score:** 8.5/10

### Practical Implementation Feasibility

**Strengths:**
- ANNEX-003 (State Privacy Law Matrix) reference provides practical lookup mechanism for state-specific requirements
- Legislative tracking approach (Section 3.6.1) using industry associations (SIIA, FPF, SDPC) reflects best practices
- Compliance assessment process (Section 3.6.2) is practical and scalable
- Standardized DPA participation reduces operational burden

**Concerns:**
- Managing 50 state variations is operationally challenging; policy should address baseline approach more explicitly
- Breach notification timeline variations (24 hours to 60 days across states) create operational complexity; policy should recommend most conservative approach as default
- State law changes can be rapid (session-by-session); should recommend cadence for ANNEX-003 updates

**Implementation Feasibility Score:** 7.5/10

### Integration with Existing EdTech Operations

**Strengths:**
- Strong cross-referencing to related policies (STU-POL-001, STU-POL-004, STU-POL-005, RES-POL-003, OP-POL-005, SEC-POL-001)
- Integration with school district onboarding process (OP-POL-005) is essential for operationalizing state requirements
- Sales/Customer Success responsibility assignment ensures state requirements are addressed during contracting

**Recommendations:**
- Should address how Customer Success teams track which schools are in which states when districts span state lines
- Consider adding guidance on handling conflicting state requirements (e.g., stricter retention vs. longer retention)
- Integration with contract management systems should be addressed

**Integration Score:** 8/10

### EdTech SME Overall Assessment

The policy provides a solid framework for managing the complex landscape of state student privacy laws. The reliance on ANNEX-003 for state-specific details is appropriate. Operational challenges around managing 50+ jurisdictions could be more explicitly addressed with baseline approach recommendations.

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Strengths:**
- Accurate characterization of California SOPIPA requirements (Cal. Bus. & Prof. Code 22584-22585)
- Correct articulation of NY Education Law 2-d requirements including Parents' Bill of Rights
- Proper identification of encryption requirements specific to NY (TLS for transit, AES for mobile devices at rest)
- Accurate breach notification timeline summary across major states

**Compliance Gaps:**
- Section 3.1.1 SOPIPA: Should note that SOPIPA applies to operators "designed and marketed for K-12 school purposes" - the policy states this but could clarify the "actual knowledge" alternative
- NY Education Law 2-d: Should reference the specific breach notification timeline from 8 NYCRR 121.9 rather than placeholder
- Colorado: Missing reference to the state's Student Data Privacy Council requirements
- Connecticut: Should note amendments effective 2023 regarding additional contractor requirements

### Citation Correctness

**Verified Citations:**
- Cal. Bus. & Prof. Code 22584-22585 (SOPIPA): CORRECT
- NY Educ. Law 2-d; 8 NYCRR Part 121: CORRECT
- C.R.S. 22-16-101 to 22-16-111 (Colorado): CORRECT
- Conn. Gen. Stat. 10-234aa to 10-234dd (Connecticut): CORRECT

**Missing/Incomplete Citations:**
- Illinois SOPPA: Should cite 105 ILCS 85/ (Student Online Personal Protection Act)
- Louisiana: Should cite La. R.S. 17:3914 (Student Privacy Act)
- Maryland: Should cite Md. Code, Educ. 4-131 (Student Data Privacy Act)
- Nevada: Should cite NRS 388.287-388.296
- Oregon: Should cite ORS 336.184 (Student Information Protection Act)
- Virginia: Should cite Va. Code 22.1-289.01
- Washington: Should cite RCW 28A.604.010-.900 (SUPER Act)

**Citation Accuracy Score:** 7.5/10 (main laws cited correctly; supplementary state laws need citations)

### State Law Coverage Adequacy

**Assessment:**
- Coverage of major state laws (CA, NY, CO, CT) is thorough
- "Other Significant State Laws" section acknowledges breadth but lacks depth
- ANNEX-003 reference appropriately defers detail to supporting document
- Missing several states with notable laws (Texas HB 2087, Florida 1014, Massachusetts Student Data Privacy)

**Recommendation:**
- Expand Section 3.1.5 to include at least 5-7 additional states with significant student privacy legislation
- Add note that the list is illustrative, not exhaustive, and refer to ANNEX-003 for complete coverage
- Consider adding a map or regional summary showing law adoption patterns

### Regulatory SME Overall Assessment

The policy demonstrates good understanding of major state student privacy laws. Citation completeness for secondary states needs improvement. The reliance on ANNEX-003 is appropriate but the policy itself should provide fuller citations for referenced laws.

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Strengths:**
- Well-organized state-by-state structure in Section 3.1 facilitates lookup
- Effective use of tables to present state requirements and company compliance measures
- Common requirements section (3.2) provides helpful synthesis across jurisdictions
- DPA requirements section (3.3) is practical and actionable

**Areas for Improvement:**
- Section 3.1.5 table is compact but may be too abbreviated; readers may need to reference ANNEX-003 frequently
- The policy alternates between presenting requirements and compliance measures in tables; consider standardizing
- Section 3.5 breach notification table timeline column could benefit from standardized format (all as "X days" or "X hours")
- Consider adding an executive summary given the policy's complexity

**Readability Score:** 8/10 (Flesch-Kincaid estimate: Grade 13-14, appropriate for policy audience but complex)

### Consistent Terminology

**Terminology Audit:**
- "Student data" - Used consistently, though distinct from FERPA "education records" terminology
- "DPA/Data Processing Agreement" - Used consistently with acronym defined
- "Operator" - Used in SOPIPA context correctly
- "Third-party contractor" - Used in NY context correctly

**Inconsistencies Found:**
- "School/district" vs. "school" vs. "educational institution" - varies by context; acceptable but could be more consistent
- "Student data" vs. "student information" vs. "student personal information" - should standardize
- "K-12" vs. "K-12 schools" vs. "K-12 educational settings" - minor variation
- State law names sometimes include "Act" and sometimes don't

**Terminology Consistency Score:** 7.5/10

### Format and Structure Compliance

**Structure Assessment:**
- Follows standard policy template
- State-by-state organization is logical and facilitates reference
- Tables are consistent within sections but vary across sections
- Cross-references to ANNEX-003 are appropriate

**Format Issues:**
- Missing version number/revision history section
- Missing effective date placeholder
- Inconsistent table column headers across sections
- Section numbering could include state abbreviations for easier navigation (e.g., "3.1.1 California - SOPIPA" could be "3.1.1-CA")
- Consider adding internal hyperlinks to ANNEX-003 sections for digital versions

**Format Compliance Score:** 7.5/10

### Technical Editor Overall Assessment

The document tackles a complex subject matter effectively. The state-by-state organization is appropriate, though the presentation could be more consistent. Terminology standardization and format improvements would enhance usability. The policy's reliance on ANNEX-003 is appropriate but requires that annex to be comprehensive.

---

## Stage 7: QA Validation

### Cross-Reference Accuracy

**Internal Cross-References Verified:**
| Reference | Section | Status |
|-----------|---------|--------|
| STU-POL-001 (Student Data Governance Policy) | 3.1.1, 3.2.1, 3.2.2, 7 | Valid reference; multiple sections |
| STU-POL-004 (Student Data Sharing Policy) | 3.1.1, 3.2.1, 7 | Valid reference |
| STU-POL-005 (Data Retention and Destruction Policy) | 3.1.1, 3.1.3, 7 | Valid reference |
| RES-POL-003 (Breach Notification - Schools) | 3.1.2, 3.1.4, 3.2.2, 3.5, 7 | Valid reference |
| OP-POL-005 (School District Onboarding Policy) | 3.2.2, 7 | Valid reference |
| SEC-POL-001 (Information Security Policy) | 3.1.1-3.1.4, 3.2.2, 3.4, 7 | Valid reference; heavily used |
| RES-POL-001 (Incident Response Plan) | 3.4 | Valid reference |
| ANNEX-003 (State Student Privacy Law Matrix) | 3.1.5, 3.6.3, 7 | Valid reference; critical dependency |
| ANNEX-005 (School DPA Template) | 7 | Valid reference |

**Cross-Reference Issues:**
- Heavy reliance on ANNEX-003 - this annex must be comprehensive and regularly updated
- RES-POL-001 is referenced in Section 3.4 but not listed in Related Documents (Section 7)

### Template Completeness

**Placeholder Audit:**
| Placeholder | Location | Status |
|-------------|----------|--------|
| [Company Name] | Throughout | Consistent |
| [Number, e.g., 24] | Section 3.1.2, 3.5 | Present with example |
| [Role Title, e.g., Student Data Privacy Officer] | Section 8 | Present with example |
| [Date] | Section 8 | Present (2 instances) |

**Template Completeness Score:** 9/10 - Placeholders consistent; RES-POL-001 reference issue noted.

### Publication Readiness

**Checklist:**
- [x] All sections complete
- [ ] No broken cross-references (RES-POL-001 missing from Related Documents)
- [x] Consistent formatting throughout
- [ ] Legal citations complete (secondary state laws need citations)
- [x] Tables render correctly
- [x] Placeholder system functional
- [x] Role assignments clear
- [ ] Version control metadata (recommend adding)
- [ ] Effective date placeholder (recommend adding)
- [ ] ANNEX-003 availability verification needed

**Publication Readiness Score:** 7.5/10

### QA Validation Overall Assessment

The policy has a solid structure but has more issues than the other privacy policies in this set. The missing RES-POL-001 reference in Related Documents should be corrected. Citation completeness for secondary state laws needs attention. The heavy reliance on ANNEX-003 requires that document to be validated as complete and accurate.

---

## Consolidated Review Summary

| Review Stage | Reviewer Persona | Score | Key Finding |
|--------------|------------------|-------|-------------|
| Stage 4 | EdTech Controls SME | 8.0/10 | Good coverage; address CA AADC; operational complexity |
| Stage 5 | FERPA/COPPA Regulatory SME | 7.7/10 | Major laws accurate; secondary citations incomplete |
| Stage 6 | Technical Editor | 7.7/10 | Complex topic handled well; terminology standardization needed |
| Stage 7 | QA Validation | 8.0/10 | Cross-reference gap; ANNEX-003 dependency |

**Overall Score:** 7.85/10

---

## VERDICT: APPROVED WITH MINOR CHANGES

### Required Changes Before Publication:
1. Add RES-POL-001 to Related Documents (Section 7) - it is referenced in Section 3.4
2. Add version number and revision history section
3. Add effective date placeholder
4. Add statutory citations for state laws in Section 3.1.5 table (Illinois, Louisiana, Maryland, Nevada, Oregon, Virginia, Washington)
5. Standardize terminology: use "student data" consistently throughout

### Recommended Enhancements (Non-Blocking):
1. Expand Section 3.1.5 to include additional significant states (Texas, Florida, Massachusetts, Georgia)
2. Add note about California Age-Appropriate Design Code Act (AADC) implications
3. Include guidance on baseline approach for managing 50-state variation
4. Address multi-district/consortium purchasing and state law applicability
5. Standardize breach notification timeline format in Section 3.5 (all as "X hours" or "X days")
6. Consider adding executive summary given policy complexity
7. Verify ANNEX-003 is comprehensive and establish update cadence (recommend quarterly)

---

**Review Completed By:** Expert Review Panel (Stages 4-7)
**Review Date:** 2026-01-18
**Next Action:** Address required changes, verify ANNEX-003 completeness, then proceed to final approval
