# De-identification Procedure (STU-PROC-006)

## 1. Purpose

This procedure provides step-by-step instructions for de-identifying student data in compliance with STU-POL-006, including identifier removal, risk assessment, and verification.

## 2. Scope

This procedure applies to Data Science, Analytics, Engineering, and any workforce members who de-identify student data.

## 3. Procedure

### 3.1 De-identification Request

#### 3.1.1 Requesting De-identification

**When:** Student data needs to be de-identified for research, analytics, or product improvement.

**Steps:**

1. **Document request**
   - Requestor name and role
   - Data set to be de-identified
   - Purpose of de-identification
   - Intended use of de-identified data
   - Target audience (internal, external, public)

2. **Submit for approval**
   - Route to Student Data Privacy Officer
   - Include justification and intended use

3. **Obtain approval**
   - Privacy Officer reviews purpose and scope
   - Approval documented before proceeding

### 3.2 De-identification Execution

#### 3.2.1 Removing Direct Identifiers

**When:** Executing approved de-identification.

**Steps:**

1. **Inventory direct identifiers in dataset**
   - Student name
   - Parent/guardian names
   - Email addresses
   - Phone numbers
   - Home addresses
   - Student ID numbers
   - Social Security numbers
   - Device identifiers
   - IP addresses
   - Biometric data
   - Photos/videos with faces

2. **Remove each direct identifier**
   | Identifier | Action |
   |------------|--------|
   | Names | Delete column entirely |
   | Email | Delete column entirely |
   | Phone | Delete column entirely |
   | Address | Delete or generalize to state/region |
   | Student ID | Delete or replace with random token |
   | SSN | Delete column entirely |
   | Device ID | Delete or hash with random salt |
   | IP address | Delete or truncate to /24 |
   | Photos | Delete or blur faces beyond recognition |

3. **Document removals**
   - List all fields removed or transformed
   - Note transformation method

#### 3.2.2 Treating Indirect Identifiers

**When:** Dataset contains indirect identifiers that could enable re-identification.

**Steps:**

1. **Identify indirect identifiers**
   - Date of birth
   - Grade level
   - School name
   - Zip code
   - Gender
   - Race/ethnicity
   - Disability status
   - Enrollment dates
   - Activity timestamps

2. **Apply generalization**
   | Identifier | Generalization |
   |------------|----------------|
   | Date of birth | Year only, or age range (e.g., 10-12) |
   | School name | District or region |
   | Zip code | First 3 digits or state |
   | Dates | Month/year or quarter |
   | Rare categories | Combine with "Other" |

3. **Assess remaining risk**
   - See Section 3.3 for risk assessment

#### 3.2.3 Applying Aggregation

**When:** Releasing aggregate statistics.

**Steps:**

1. **Calculate statistics**
   - Counts, means, percentages, etc.

2. **Apply suppression thresholds**
   | Metric | Minimum Cell Size |
   |--------|------------------|
   | Counts | ≥ **[Number, e.g., 10]** |
   | Averages | Based on ≥ **[Number, e.g., 10]** students |
   | Percentages | Denominator ≥ **[Number, e.g., 10]** |
   | Cross-tabs | All cells ≥ **[Number, e.g., 5]** |

3. **Suppress small cells**
   - Replace with "*" or "N/A"
   - Apply complementary suppression (prevent inference)

4. **Document suppression**
   - Note suppression rules applied
   - Count of suppressions

### 3.3 Re-identification Risk Assessment

#### 3.3.1 Assessing Risk

**When:** Before classifying data as de-identified.

**Steps:**

1. **Identify quasi-identifiers**
   - Combinations of remaining attributes
   - E.g., age + gender + grade + school district

2. **Assess population uniqueness**
   - How many students match each combination?
   - Small populations = higher risk
   - Rare attributes = higher risk

3. **Consider external data**
   - What publicly available data could be linked?
   - School directories, news articles, social media

4. **Evaluate adversary capability**
   - Who might try to re-identify?
   - What resources do they have?
   - What is their motivation?

5. **Calculate/estimate risk**
   - High risk: unique or near-unique records exist
   - Medium risk: small groups could be identified
   - Low risk: no reasonable path to re-identification

6. **Document assessment**
   - Factors considered
   - Risk level determined
   - Rationale

#### 3.3.2 Addressing Elevated Risk

**When:** Risk assessment indicates medium or high risk.

**Steps:**

1. **Apply additional protections**
   - Further generalization
   - Higher aggregation thresholds
   - Sampling (if representative sample is acceptable)
   - Differential privacy (for sophisticated use cases)

2. **Re-assess risk**
   - Repeat risk assessment
   - Continue until risk is acceptable

3. **Consider not releasing**
   - If risk cannot be reduced sufficiently
   - Document decision not to release

### 3.4 Verification

#### 3.4.1 Verifying De-identification

**When:** Before data is classified as de-identified.

**Steps:**

1. **Review output dataset**
   - Scan for residual identifiers
   - Check for identifier patterns (email format, phone format)
   - Review text fields for embedded identifiers

2. **Verify transformations**
   - Confirm all direct identifiers removed
   - Confirm generalizations applied correctly
   - Confirm aggregation thresholds met

3. **Validate risk assessment**
   - Review risk assessment completeness
   - Confirm acceptable risk level

4. **Obtain verification sign-off**
   - Second reviewer confirms de-identification
   - Document verification

5. **Classify as de-identified**
   - Update data classification
   - Document de-identification completion

### 3.5 Using De-identified Data

#### 3.5.1 Internal Use

**When:** Using de-identified data for internal purposes.

**Steps:**

1. **Confirm de-identification verified**
   - Check de-identification log
   - Confirm approval for intended use

2. **Use per documented purpose**
   - Analytics, research, product improvement
   - Do not attempt re-identification

3. **Apply appropriate security**
   - Even de-identified data should be protected
   - Access limited to those with business need

#### 3.5.2 External Sharing

**When:** Sharing de-identified data externally.

**Steps:**

1. **Verify de-identification is sufficient**
   - Consider broader distribution risk
   - Apply stricter thresholds for public release

2. **Prepare data use agreement**
   - Prohibition on re-identification
   - Prohibition on linking to external data
   - Data destruction requirements
   - Notification if re-identification occurs

3. **Execute agreement**
   - Obtain recipient signatures
   - File agreement

4. **Transfer data**
   - Secure transfer method
   - Document transfer

5. **Monitor** (for research partnerships)
   - Periodic check-ins
   - Verify appropriate use

### 3.6 Documentation

#### 3.6.1 De-identification Log

**When:** Each de-identification event.

**Steps:**

1. **Record in log**
   - Date of de-identification
   - Original data source
   - Data categories included
   - Purpose
   - Method applied
   - Risk assessment results
   - Verification performed
   - Intended use/recipients

2. **Retain documentation**
   - Keep for **[Number, e.g., 3]** years or duration of use
   - Make available for audit

## 4. Special Considerations

### 4.1 Small Schools

For data from small schools (< 100 students):
- Apply stricter thresholds
- Consider if de-identification is achievable
- May need to decline release

### 4.2 Longitudinal Data

For time-series data:
- Temporal patterns can enable re-identification
- Limit time granularity
- Consider additional aggregation

### 4.3 Text Data

For free-text fields (comments, essays):
- Scan for embedded identifiers
- Remove or redact names, locations, dates
- Consider excluding text fields

## 5. Records

| Record | Retention | Location |
|--------|-----------|----------|
| De-identification log | 3 years or duration of use | **[System]** |
| Risk assessments | 3 years | **[System]** |
| Verification records | 3 years | **[System]** |
| Data use agreements | Agreement + 3 years | Contract system |

## 6. References

- STU-POL-006: De-identification Policy
- STU-POL-001: Student Data Governance Policy
- FERPA guidance on de-identification

## 7. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
