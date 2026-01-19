# Accessibility Testing and Remediation Procedure (ENG-PROC-008)

## 1. Purpose

This procedure provides step-by-step instructions for testing accessibility compliance and remediating accessibility issues, ensuring products meet WCAG 2.1 AA standards per ENG-POL-005.

## 2. Scope

This procedure applies to QA, Engineering, Design, and Product teams responsible for accessibility compliance.

## 3. Procedure

### 3.1 Automated Accessibility Testing

#### 3.1.1 Running Automated Scans

**When:** Part of development workflow and CI/CD pipeline.

**Steps:**

1. **Configure automated tools**
   - axe-core integrated in testing framework
   - Lighthouse accessibility audits
   - CI/CD pipeline includes accessibility checks

2. **Run scans**
   - On every pull request
   - On staging before release
   - On production periodically

3. **Review results**
   - Identify violations by severity
   - Critical/Serious: block release
   - Moderate/Minor: track for remediation

4. **Document findings**
   - Log issues in tracking system
   - Link to affected components

#### 3.1.2 Interpreting Scan Results

**When:** Automated scan completes.

**Steps:**

1. **Categorize issues**
   | Severity | Examples | Action |
   |----------|----------|--------|
   | Critical | Missing alt text, no keyboard access | Fix before release |
   | Serious | Poor contrast, missing labels | Fix before release |
   | Moderate | Heading hierarchy issues | Track and fix |
   | Minor | Best practice violations | Track and fix |

2. **Verify findings**
   - Automated tools have false positives
   - Manually verify flagged issues

3. **Create tickets**
   - One ticket per issue
   - Include component, issue, WCAG criterion

### 3.2 Manual Accessibility Testing

#### 3.2.1 Keyboard Testing

**When:** Testing new features or pages.

**Steps:**

1. **Navigate using keyboard only**
   - Tab through all interactive elements
   - Verify logical tab order
   - Verify focus is visible
   - Verify no keyboard traps

2. **Test all functionality**
   - Can all features be used with keyboard?
   - Do keyboard shortcuts work?
   - Can modals/dropdowns be dismissed?

3. **Document issues**
   - Elements not reachable
   - Focus not visible
   - Keyboard traps
   - Illogical tab order

#### 3.2.2 Screen Reader Testing

**When:** Testing new features or major changes.

**Steps:**

1. **Select screen readers**
   - NVDA (Windows)
   - VoiceOver (Mac/iOS)
   - At least 2 for coverage

2. **Test with each screen reader**
   - Navigate through page
   - Verify all content is announced
   - Verify images have alt text
   - Verify forms are labeled
   - Verify dynamic content is announced

3. **Test key user flows**
   - Sign in/sign up
   - Core feature workflows
   - Error handling

4. **Document issues**
   - Missing announcements
   - Confusing reading order
   - Unlabeled elements
   - Poor ARIA usage

#### 3.2.3 Visual Testing

**When:** Testing visual design elements.

**Steps:**

1. **Check color contrast**
   - Use contrast checker tool
   - Text: 4.5:1 minimum (3:1 for large text)
   - UI components: 3:1 minimum

2. **Check color independence**
   - Information not conveyed by color alone
   - Links distinguishable without color

3. **Check text resizing**
   - Zoom to 200%
   - Verify content still usable
   - No horizontal scrolling for text

4. **Check motion**
   - Animations can be paused/stopped
   - Respects prefers-reduced-motion

5. **Document issues**
   - Contrast failures
   - Color-only information
   - Zoom/resize issues

### 3.3 Issue Remediation

#### 3.3.1 Prioritizing Issues

**When:** Accessibility issues have been identified.

**Steps:**

1. **Assess impact**
   | Factor | High Impact | Low Impact |
   |--------|-------------|------------|
   | Users affected | Core users blocked | Edge case |
   | Feature importance | Critical feature | Secondary feature |
   | WCAG level | A criterion | AAA criterion |
   | Workaround | No workaround | Workaround exists |

2. **Assign priority**
   - P0: Critical blocker - fix immediately
   - P1: Serious issue - fix this sprint
   - P2: Moderate issue - fix this quarter
   - P3: Minor issue - backlog

3. **Schedule remediation**
   - Add to sprint planning
   - Track in accessibility backlog

#### 3.3.2 Fixing Issues

**When:** Remediating accessibility issues.

**Steps:**

1. **Understand the issue**
   - Which WCAG criterion is violated?
   - What is the user impact?
   - What is the correct implementation?

2. **Implement fix**
   - Follow WCAG techniques
   - Reference accessibility resources

3. **Test the fix**
   - Verify fix resolves issue
   - Verify no regression

4. **Code review**
   - Reviewer verifies accessibility
   - Approval required before merge

5. **Close ticket**
   - Document resolution
   - Link to PR/commit

#### 3.3.3 Documenting Remediation

**When:** Issue has been fixed.

**Steps:**

1. **Update issue ticket**
   - Resolution description
   - Fix version/release
   - Verification performed

2. **Update VPAT** (if needed)
   - If issue was documented in VPAT
   - Update conformance status

3. **Update accessibility roadmap**
   - Mark item complete
   - Update projected conformance

### 3.4 Third-Party Audit

#### 3.4.1 Conducting Annual Audit

**When:** Annually, per policy.

**Steps:**

1. **Select audit scope**
   - Representative sample of functionality
   - Key user flows
   - New features since last audit

2. **Engage auditor**
   - Qualified accessibility auditor
   - Experience with educational products

3. **Provide access**
   - Test environment
   - Test accounts
   - Documentation

4. **Receive audit report**
   - Review findings
   - Clarify any questions

5. **Create remediation plan**
   - Prioritize findings
   - Set timeline for fixes
   - Assign owners

6. **Track remediation**
   - Regular progress updates
   - Verify fixes

### 3.5 VPAT Maintenance

#### 3.5.1 Updating VPAT

**When:** Annually and after major releases.

**Steps:**

1. **Gather current state**
   - Known accessibility issues
   - Recent remediation
   - Audit findings

2. **Update each criterion**
   - Supports / Partially Supports / Does Not Support / Not Applicable
   - Remarks explaining status

3. **Document exceptions**
   - Known issues
   - Planned remediation

4. **Review and approve**
   - Product/Engineering review
   - Compliance review

5. **Publish updated VPAT**
   - Post on website
   - Provide to requesting schools

### 3.6 Accommodation Requests

#### 3.6.1 Processing Accommodation Requests

**When:** User or school requests accessibility accommodation.

**Steps:**

1. **Receive request**
   - Document need
   - Identify specific barrier

2. **Assess options**
   - Can barrier be removed?
   - Is workaround available?
   - Can alternative format be provided?

3. **Provide accommodation**
   - Implement solution
   - Communicate to requestor

4. **Track for product improvement**
   - Add to accessibility backlog
   - Consider in future development

5. **Document accommodation**
   - Record request and resolution
   - Timeline met?

## 4. Escalation

Escalate to Product/Engineering leadership when:
- Critical accessibility blocker in production
- Customer complaint or legal concern
- Audit reveals significant gaps
- Accommodation cannot be provided

## 5. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Automated scan results | 2 years | CI/CD logs |
| Manual test results | 3 years | QA system |
| Audit reports | 5 years | Compliance files |
| VPAT versions | Permanent | Document repository |
| Accommodation records | 5 years | Support system |

## 6. References

- ENG-POL-005: Accessibility Standards Policy
- WCAG 2.1 Guidelines
- Section 508 Standards

## 7. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
