# Expert Review: STU-PROC-001 - Student Data Governance Procedure

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/student_data_procedures/STU-PROC-001.md`
**Review Date:** 2026-01-18
**Review Version:** 1.0

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Assessment: SATISFACTORY**

The procedure accurately addresses the core EdTech operational context:

1. **Education Record Determination (Section 3.1.1, Step 2):** The three-part test for determining if data is an education record is technically accurate and aligns with FERPA definitions. The exclusion list (sole possession notes, law enforcement, employment, alumni) is correct.

2. **Data Categories:** The four-category classification system (Education Record, Directory Information, De-identified Data, Aggregated Data) appropriately covers the spectrum of student data types handled by EdTech platforms.

3. **Legitimate Educational Interest Framework (Section 3.3):** The verification process correctly ties access to contracted educational services and job function scope.

**Recommendations:**
- Consider adding guidance for "derived data" (e.g., learning analytics, behavioral insights) which is increasingly common in EdTech but not explicitly addressed.
- The system-generated data classification path could benefit from additional specificity regarding AI/ML model outputs.

### Practical Implementation Feasibility

**Assessment: SATISFACTORY WITH MINOR CONCERNS**

1. **Inventory Management:** The ANNEX-004 template approach is practical, though the procedure should clarify how to handle data elements that span multiple categories.

2. **Approval Workflow:** Routing new classifications through the Student Data Privacy Officer is appropriate but may create bottlenecks at scale. Consider adding delegation authority for routine classifications.

3. **Annual Review Cadence:** The annual inventory review is appropriate but may be insufficient for rapidly iterating EdTech products. Consider triggering reviews on significant feature releases.

### Operational Workflow Clarity

**Assessment: GOOD**

The procedure provides clear "When" triggers and step-by-step instructions. The governance committee activities (Section 3.4) provide appropriate oversight structure.

**Minor Gap:** The handoff between classification decision and access control implementation (Section 3.1.2, Step 6) would benefit from more explicit procedural linkage.

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Assessment: SATISFACTORY**

1. **FERPA Education Record Definition:** Section 3.1.1 correctly implements the FERPA definition at 34 CFR 99.3, including the two-prong test (directly related to student + maintained by school/agent).

2. **FERPA Exclusions:** The listed exclusions (sole possession notes, law enforcement records, employment records, alumni records) align with 34 CFR 99.3 exclusions.

3. **Legitimate Educational Interest:** The verification framework (Section 3.3) appropriately addresses the school official criteria under 34 CFR 99.31(a)(1).

4. **Directory Information:** Section 3.1.1 correctly notes that Directory Information designation is a school determination, not a vendor decision.

**Compliance Gaps:**

1. **COPPA Coverage:** While the procedure references COPPA applicability in Section 3.1.1 Step 4, it does not provide specific guidance for classifying data from children under 13. Consider adding specific workflow for age-based classification.

2. **State Law Variations:** The procedure references state laws but does not provide a mechanism for tracking state-specific classification requirements (e.g., California SOPIPA, New York Education Law 2-d).

### Proper Support for Regulatory Requirements

**Assessment: SATISFACTORY**

1. **Recordkeeping:** The Records table (Section 4) establishes appropriate retention periods that meet FERPA audit trail requirements.

2. **School Transparency:** Section 3.2.2 Step 5 appropriately provides for school-specific data inventories.

3. **Periodic Review:** Annual review cycles align with best practices for regulatory compliance maintenance.

**Recommendation:** Add explicit reference to FERPA's "reasonable methods" standard for access verification (34 CFR 99.31(c)).

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Assessment: GOOD**

1. **Structure:** The document follows a logical hierarchy from classification through inventory to governance.

2. **Language:** Technical terms are used appropriately without excessive jargon. The procedure is accessible to non-legal staff.

3. **Formatting:** Consistent use of headers, numbered steps, and tables enhances scannability.

**Minor Issues:**
- Section 3.1.1 Step 3 bullet "Aggregated Data: Verify aggregation thresholds met" - should specify where thresholds are defined.
- "**[Company Name]**" placeholders are clear but should be consolidated with a single definition note at document start.

### Step-by-Step Flow Logic

**Assessment: SATISFACTORY**

The procedural flow is logical:
1. Classification triggers are clearly defined ("When" statements)
2. Decision trees (e.g., education record determination) use clear yes/no logic
3. Outputs of each step feed into subsequent steps

**Minor Gap:** The transition from Section 3.1.1 (classifying new data) to Section 3.2.1 (adding to inventory) could include an explicit "proceed to" reference.

### Consistent Terminology

**Assessment: SATISFACTORY**

Terminology is consistent throughout:
- "Education Record" (capitalized, as proper term)
- "Student Data Privacy Officer" (consistent role title)
- "Data inventory" vs. "master inventory" - slight inconsistency in Section 3.2.1; recommend standardizing to "data inventory"

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

**Assessment: SATISFACTORY**

| Reference | Verified |
|-----------|----------|
| STU-POL-001: Student Data Governance Policy | Primary parent policy - appropriate |
| STU-POL-006: De-identification Policy | Referenced for de-identification verification - appropriate |
| ANNEX-004: Student Data Inventory Template | Referenced for inventory - verify template exists |

**Note:** The procedure correctly positions itself as implementing STU-POL-001. All cross-references are contextually appropriate.

### Template Completeness

**Assessment: SATISFACTORY WITH MINOR GAPS**

1. **Placeholder Consistency:**
   - **[Company Name]** - used consistently
   - **[System]** - used for storage locations; appropriate placeholder
   - **[Location]** - used for governance meeting minutes; should be standardized to **[System]** for consistency
   - **[Date]**, **[Author]** - standard for revision history

2. **Required Sections:** All standard sections present (Purpose, Scope, Procedure, Records, References, Revision History).

3. **Missing Element:** No "Definitions" section - consider adding for terms like "Education Record," "Legitimate Educational Interest," and "Data Owner."

### Publication Readiness

**Assessment: READY WITH MINOR REVISIONS**

**Pre-Publication Checklist:**
- [x] Purpose clearly stated
- [x] Scope appropriately defined
- [x] Procedures detailed with clear steps
- [x] Records/retention defined
- [x] Cross-references validated
- [ ] Placeholders require completion before deployment
- [ ] Definitions section recommended but not blocking

---

## Consolidated Findings

### Strengths
1. Comprehensive coverage of data governance lifecycle (classification, inventory, access, oversight)
2. Clear alignment with FERPA requirements for education records
3. Practical workflow design with defined triggers and approval paths
4. Appropriate governance structure with Privacy Officer oversight

### Areas for Improvement
1. Add COPPA-specific workflow for under-13 classification decisions
2. Include state law tracking mechanism
3. Add Definitions section for key terms
4. Clarify derived data/analytics data classification
5. Standardize "data inventory" terminology throughout

### Risk Assessment
- **Regulatory Risk:** LOW - Core FERPA requirements are addressed
- **Operational Risk:** LOW - Procedures are practical and implementable
- **Completeness Risk:** MEDIUM - COPPA and state law gaps should be addressed

---

## VERDICT: APPROVED WITH MINOR CHANGES

The procedure is technically sound and suitable for operational use. The following minor changes are recommended before final publication:

1. Add explicit COPPA under-13 classification guidance
2. Add Definitions section
3. Standardize "data inventory" terminology
4. Change **[Location]** to **[System]** for consistency in Records table
5. Add cross-reference guidance between classification completion and inventory addition

These changes can be addressed during final editing without requiring re-review.
