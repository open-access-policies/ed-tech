# Age-Appropriate Design Review Procedure (ENG-PROC-007)

## 1. Purpose

This procedure provides step-by-step instructions for reviewing product features for age-appropriate design, ensuring compliance with ENG-POL-004, COPPA, and child safety best practices.

## 2. Scope

This procedure applies to Product, Design, Engineering, and QA teams developing features used by children and students.

## 3. Procedure

### 3.1 Pre-Development Review

#### 3.1.1 Feature Assessment

**When:** New feature is proposed that may be used by children.

**Steps:**

1. **Determine target users**
   - Will children under 13 use this feature?
   - Will teens (13-17) use this feature?
   - Is feature K-12 or mixed-age?

2. **Identify data collection**
   - What personal information will be collected?
   - Is collection necessary for the feature?
   - Can feature work with less data?

3. **Assess privacy impact**
   - Does feature share data with third parties?
   - Does feature enable public posting?
   - Does feature enable contact with strangers?

4. **Document assessment**
   - Complete age-appropriate design checklist
   - Flag concerns for review

#### 3.1.2 Design Review Meeting

**When:** Feature assessment identifies potential concerns.

**Steps:**

1. **Schedule review**
   - Include Product, Design, Privacy, Engineering

2. **Present feature design**
   - Describe feature functionality
   - Describe data collection and use
   - Describe user interactions

3. **Apply age-appropriate principles**
   - Privacy by default?
   - Data minimization?
   - No dark patterns?
   - Age-appropriate interface?

4. **Identify required changes**
   - Document changes needed
   - Assign responsibility

5. **Obtain approval to proceed**
   - Privacy Officer sign-off for high-risk features
   - Document approval

### 3.2 Design Requirements

#### 3.2.1 Privacy Settings Review

**When:** Designing feature privacy settings.

**Steps:**

1. **Set defaults for minors**
   | Setting | Minor Default |
   |---------|---------------|
   | Profile visibility | Private |
   | Location sharing | Off |
   | Contact from strangers | Blocked |
   | Search indexing | Off |
   | Personalization | Minimal |

2. **Ensure opt-in for privacy-reducing features**
   - Parent/school consent required for changes
   - Not buried in settings

3. **Make settings understandable**
   - Age-appropriate language
   - Clear consequences explained

4. **Document settings design**
   - Record default settings
   - Justification for any non-private defaults

#### 3.2.2 Data Collection Review

**When:** Designing data collection for feature.

**Steps:**

1. **List data to be collected**
   - Each data element
   - Purpose for collection

2. **Apply COPPA minimization**
   - Is each element necessary?
   - Can feature work without?

3. **Remove unnecessary collection**
   - Eliminate non-essential data
   - Don't condition on extra collection

4. **Document collection justification**
   - Business need for each element
   - Retained for compliance

#### 3.2.3 Interface Design Review

**When:** Designing UI for features used by children.

**Steps:**

1. **Check for dark patterns**
   - No deceptive design
   - No pressure tactics
   - No hidden collection
   - Clear opt-out processes

2. **Check age-appropriateness**
   - Language appropriate for age
   - Visual design appropriate
   - Not exploiting children

3. **Verify safety features**
   - Reporting mechanisms
   - Blocking capabilities
   - Parental/teacher controls

4. **Document design decisions**
   - Age-appropriate rationale
   - Safety feature placement

### 3.3 Implementation Review

#### 3.3.1 Code Review for Age Compliance

**When:** Code implementing age-related features.

**Steps:**

1. **Verify default settings**
   - Defaults match design
   - Privacy-protective defaults for minors

2. **Verify data collection**
   - Only approved data collected
   - Collection respects age

3. **Verify age-gating**
   - Age restrictions enforced
   - Features blocked for young children

4. **Verify consent flow**
   - Parent/school consent checked
   - Consent scope respected

5. **Document review**
   - Code review findings
   - Approval to merge

### 3.4 Testing

#### 3.4.1 Age-Appropriate Testing

**When:** Testing features used by children.

**Steps:**

1. **Test as child user**
   - Create test account as under-13 user
   - Verify privacy defaults
   - Verify feature restrictions

2. **Test as teen user**
   - Create test account as 13-17 user
   - Verify appropriate defaults
   - Verify age-specific features

3. **Test parental controls**
   - Verify parent dashboard works
   - Verify controls cannot be bypassed

4. **Test consent flows**
   - Verify school consent recognized
   - Verify parent consent flow (if applicable)

5. **Document test results**
   - Pass/fail for each test
   - Issues found and resolution

### 3.5 Launch Review

#### 3.5.1 Pre-Launch Checklist

**When:** Feature ready for launch.

**Steps:**

1. **Verify all requirements met**
   - [ ] Privacy defaults implemented
   - [ ] Data minimization achieved
   - [ ] No dark patterns
   - [ ] Age-appropriate interface
   - [ ] Safety features in place
   - [ ] Consent flows working
   - [ ] Testing complete

2. **Privacy Officer approval**
   - For features used by under-13
   - For high-risk features

3. **Document launch approval**
   - All approvals recorded
   - Checklist signed off

4. **Monitor post-launch**
   - Watch for issues
   - Address feedback promptly

### 3.6 Periodic Review

#### 3.6.1 Annual Feature Review

**When:** Annually for all features used by children.

**Steps:**

1. **Inventory features**
   - List features used by children
   - Identify data collection

2. **Review against current standards**
   - New laws or guidance?
   - Industry best practices changed?

3. **Identify improvements needed**
   - Document gaps
   - Prioritize remediation

4. **Implement improvements**
   - Address identified issues
   - Update features as needed

5. **Document review**
   - Findings and actions
   - Date of review

## 4. Escalation

Escalate to Student Data Privacy Officer when:
- Feature collects sensitive data from children
- Potential COPPA violation identified
- Parent/school complaint
- Regulatory inquiry

## 5. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Design review records | 3 years | Product documentation |
| Testing results | 3 years | QA system |
| Launch approvals | 3 years | Product documentation |
| Annual reviews | 5 years | Compliance files |

## 6. References

- ENG-POL-004: Age-Appropriate Design Policy
- PRV-POL-002: COPPA Compliance Policy
- ENG-POL-001: Secure Software Development Policy

## 7. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
