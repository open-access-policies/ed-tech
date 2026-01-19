# Expert Review: STU-PROC-003 - Parent Rights Request Procedure

**Document Under Review:** `/Users/seantodd/personal-projects/open-access-policies/ed-tech/student_data_procedures/STU-PROC-003.md`
**Review Date:** 2026-01-18
**Review Version:** 1.0

---

## Stage 4: EdTech Controls SME Review

### Technical Accuracy for EdTech Context

**Assessment: SATISFACTORY**

The procedure accurately addresses the EdTech vendor's unique position:

1. **Dual-Channel Intake (Section 3.1):** Correctly distinguishes between school-forwarded requests and direct parent requests, which is critical for EdTech vendors who may receive both.

2. **FERPA Response Flow (Section 3.2.1, Steps 5-6):** Properly routes school-forwarded requests back through the school (FERPA's designated channel) while handling direct relationships appropriately.

3. **Request Type Classification:** Comprehensive coverage of access, amendment, deletion, opt-out, and consent withdrawal scenarios.

**Recommendations:**
- Add explicit guidance for handling requests that arrive through incorrect channels (e.g., parent contacts vendor directly when school-forwarded process applies).
- Consider adding workflow for "eligible student" (18+ or postsecondary) requests, which FERPA treats differently from parent requests.

### Practical Implementation Feasibility

**Assessment: SATISFACTORY WITH CONCERNS**

1. **Identity Verification (Section 3.2.1, Step 1):** "Knowledge-based verification" for direct requests needs more specificity - what questions are appropriate? Consider providing examples.

2. **Compilation Burden (Section 3.2.1, Step 2):** "Query all systems" may be challenging at scale. Consider adding guidance for implementing data subject access request automation.

3. **Timeline Placeholders:** Multiple **[Number, e.g., X]** placeholders need organization-specific decisions. These are appropriately flagged but represent operational decisions that must be made.

**Concern:** The 45-day FERPA timeline (Section 3.2.1, Step 7) is accurate, but the procedure should clarify that this is a maximum, and state laws may require faster response.

### Operational Workflow Clarity

**Assessment: GOOD**

Clear workflows for each request type. The escalation section (Section 4) appropriately identifies triggers for Privacy Officer involvement.

**Gap:** The procedure does not address batch requests (e.g., a school requesting access for multiple students simultaneously).

---

## Stage 5: FERPA/COPPA Regulatory SME Review

### Legal Compliance Accuracy

**Assessment: SATISFACTORY**

1. **Access Rights (34 CFR 99.10):** The procedure correctly implements the parent right to inspect and review education records. The 45-day timeline aligns with 34 CFR 99.10(b).

2. **Amendment Rights (34 CFR 99.20-21):** Section 3.3 correctly:
   - Limits amendments to factually incorrect information
   - Excludes grades/evaluative content from amendment
   - Notes school handles appeals (FERPA hearing right)

3. **COPPA Considerations:** Section 3.4.1 correctly identifies that direct parent deletion requests are valid for COPPA (under 13) or home-use products, appropriately distinguishing from school-contracted services.

4. **Consent Withdrawal (Section 3.6):** Correctly notes prospective effect and that prior lawful processing is not affected.

**Compliance Gaps:**

1. **Eligible Student Rights:** The procedure title and body focus on "parents" but FERPA rights transfer to students at age 18 or upon entering postsecondary education. Section 3.1.1 should include eligible student verification.

2. **FERPA Recordkeeping:** The procedure should explicitly require documenting each disclosure of records (for the FERPA disclosure log maintained by schools).

3. **Expedited COPPA Response:** COPPA requires response "as soon as reasonably practicable" - the procedure should note this may be faster than FERPA's 45 days for under-13 data.

### Proper Support for Regulatory Requirements

**Assessment: SATISFACTORY**

1. **Documentation:** Records retention (Section 5) appropriately maintains request logs, correspondence, and deletion confirmations.

2. **Amendment Records:** Correctly notes "Permanent" retention for amendment records, aligning with FERPA's requirement to maintain amendment requests with the record.

3. **School Coordination:** Consistently routes school-related requests through school channels.

**Recommendation:** Add reference to state-specific timelines (e.g., California CCPA/CPRA 45-day response, Colorado CPA 45-day response) that may apply to EdTech vendors.

---

## Stage 6: Technical Editor Review

### Clarity and Readability

**Assessment: GOOD**

1. **Structure:** Clear section organization by request type enables quick reference.

2. **Intake Process:** Section 3.1 provides effective triage workflow.

3. **Escalation Guidance:** Section 4 clearly identifies when to escalate and how.

**Issues:**
- The title "Parent Rights Request Procedure" should be updated to "Parent and Eligible Student Rights Request Procedure" to reflect FERPA's full scope.
- Section 3.4.1 Step 4 ("If data essential, terminate access") could be misread - clarify this is optional consequence, not mandatory.

### Step-by-Step Flow Logic

**Assessment: SATISFACTORY**

Flow is generally clear with good "When" trigger definitions. Each request type section follows consistent structure.

**Gaps:**
- Section 3.2.1 Step 6 (direct delivery) should explicitly reference when direct delivery applies (clarify what "direct relationship" means in EdTech context).
- Section 3.5 (opt-out) and Section 3.6 (consent withdrawal) overlap conceptually - consider clarifying the distinction for readers.

### Consistent Terminology

**Assessment: SATISFACTORY**

- "Parent" - used consistently (but should include "eligible student")
- "School" vs. "School/district" - minor inconsistency
- "Requestor" - spelled consistently throughout
- "Education records" - used correctly

**Terminology Clarification Needed:**
- "Direct relationship" (Section 3.2.1) - needs definition
- "Home-use products" (Section 3.4.1) - needs definition or cross-reference

---

## Stage 7: QA Validation

### Cross-Reference Accuracy to Policies

**Assessment: SATISFACTORY**

| Reference | Verified |
|-----------|----------|
| STU-POL-003: Parental Consent and Rights Policy | Primary parent policy - appropriate |
| STU-POL-005: Data Retention and Destruction Policy | Referenced for deletion handling - appropriate |
| PRV-POL-001: FERPA Compliance Policy | Privacy policy reference - verify exists |
| PRV-POL-002: COPPA Compliance Policy | Privacy policy reference - verify exists |

**Note:** References to PRV-POL-001 and PRV-POL-002 suggest existence of separate privacy policies. Verify these exist in the policy set.

### Template Completeness

**Assessment: SATISFACTORY WITH GAPS**

1. **Placeholder Consistency:**
   - **[Number, e.g., 5]** - Multiple timeline placeholders appropriately flagged
   - **[System]** - Used for storage locations
   - **[Date]**, **[Author]** - Standard for revision history

2. **Timeline Decisions Required:**
   - Initial response timeline (suggested 5 business days)
   - Amendment completion timeline (suggested 10 business days)
   - Deletion completion timeline (suggested 30 days)
   - Opt-out implementation timeline (suggested 5 business days)
   - Consent withdrawal implementation timeline (suggested 5 business days)

3. **Missing Elements:**
   - No Definitions section
   - No sample response templates or letters
   - No verification questionnaire for identity verification

### Publication Readiness

**Assessment: READY WITH MINOR REVISIONS**

**Pre-Publication Checklist:**
- [x] Purpose clearly stated
- [x] Scope appropriately defined
- [x] Procedures detailed with clear steps
- [x] Records/retention defined
- [x] Escalation procedures defined
- [ ] Eligible student rights need inclusion
- [ ] Timeline placeholders require organizational decisions
- [ ] Cross-references to PRV-POL-001/002 need verification

---

## Consolidated Findings

### Strengths
1. Comprehensive coverage of all major request types (access, amendment, deletion, opt-out, consent withdrawal)
2. Appropriate dual-channel handling for school-forwarded vs. direct requests
3. Clear escalation triggers and process
4. Strong documentation requirements

### Areas for Improvement
1. Add eligible student (18+/postsecondary) handling throughout
2. Update title to include eligible students
3. Clarify "direct relationship" and "home-use products" definitions
4. Add expedited COPPA timeline note
5. Clarify distinction between opt-out and consent withdrawal
6. Add sample verification questions for identity confirmation

### Risk Assessment
- **Regulatory Risk:** MEDIUM - Eligible student gap should be addressed
- **Operational Risk:** LOW - Clear workflows with appropriate escalation
- **Completeness Risk:** MEDIUM - Timeline and definition gaps need resolution

---

## VERDICT: APPROVED WITH MINOR CHANGES

The procedure provides comprehensive rights request handling but requires the following changes before publication:

**Required Changes:**
1. Update title and scope to include "eligible students"
2. Add eligible student verification step to intake (Section 3.1.1)
3. Add note regarding expedited COPPA timelines for under-13 data

**Recommended Changes:**
1. Add Definitions section (direct relationship, home-use products, eligible student)
2. Clarify opt-out vs. consent withdrawal distinction
3. Add sample identity verification questions
4. Verify PRV-POL-001 and PRV-POL-002 references

The required changes address regulatory completeness; recommended changes improve operational clarity.
