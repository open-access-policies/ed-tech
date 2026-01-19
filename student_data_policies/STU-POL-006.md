# De-identification Policy (STU-POL-006)

## 1. Objective

This policy establishes **[Company Name]**'s standards and procedures for de-identifying student data. Properly de-identified data is not subject to FERPA, COPPA, or state student privacy laws and may be used for research, product improvement, and analytics without the restrictions applicable to personally identifiable information.

## 2. Scope

This policy applies to:
- All student data considered for de-identification
- All de-identification methods and techniques used by **[Company Name]**
- All workforce members who perform or approve de-identification
- All uses of de-identified student data

## 3. Policy

**[Company Name]** maintains rigorous standards for de-identification to ensure that de-identified data cannot reasonably be used to identify individual students. Only data meeting these standards is treated as de-identified.

### 3.1 De-identification Standards

**3.1.1 FERPA Standard**

Under FERPA, education records are de-identified when:
- All personally identifiable information (PII) has been removed
- The recipient cannot reasonably identify the student from remaining information
- **[Company Name]** has made a reasonable determination that re-identification is not possible

**FERPA PII includes:**
- Student's name and names of family members
- Student's or family's address
- Personal identifiers (SSN, student ID)
- Indirect identifiers (date of birth, place of birth, mother's maiden name)
- Other information that, alone or in combination, would allow identification
- Information requested by a person who **[Company Name]** reasonably believes knows the identity of the student

**3.1.2 COPPA Standard**

For children under 13, de-identification requires:
- Removal of all personal information as defined in 16 CFR 312.2
- No reasonable possibility of re-identification

**3.1.3 Aggregation Thresholds**

When releasing aggregate statistics:

| Metric | Minimum Threshold |
|--------|-------------------|
| **Count/frequency** | Suppress if cell size < **[Number, e.g., 10]** |
| **Averages/means** | Suppress if based on < **[Number, e.g., 10]** students |
| **Percentages** | Suppress if denominator < **[Number, e.g., 10]** |
| **Cross-tabulations** | Suppress if any cell < **[Number, e.g., 5]** |

Small cell suppression prevents identification through inference.

### 3.2 De-identification Methods

**3.2.1 Direct Identifier Removal**

Remove or mask all direct identifiers:

| Identifier Type | De-identification Method |
|-----------------|-------------------------|
| **Name** | Remove entirely |
| **Email address** | Remove entirely |
| **Home address** | Remove or generalize to region |
| **Phone number** | Remove entirely |
| **Social Security Number** | Remove entirely |
| **Student ID** | Remove or replace with random token |
| **Device identifiers** | Remove or hash with salt |
| **IP address** | Remove or truncate to /24 network |
| **Photos/videos** | Remove or blur faces |
| **Biometric data** | Remove entirely |

**3.2.2 Indirect Identifier Treatment**

Treat indirect identifiers that could enable re-identification:

| Identifier Type | Treatment Method |
|-----------------|------------------|
| **Date of birth** | Generalize to year or age range |
| **Grade level** | May retain if combined with other protections |
| **School name** | Remove or generalize to district/region |
| **Zip code** | Generalize to first 3 digits or region |
| **Rare characteristics** | Generalize or suppress |
| **Dates (enrollment, activity)** | Generalize to month/year |

**3.2.3 Quasi-Identifier Analysis**

Before releasing de-identified data, assess re-identification risk from quasi-identifiers:
- Combinations of age, gender, location, grade level
- Rare attributes that could uniquely identify students
- Contextual information that could enable linkage

**Risk Assessment Factors:**
- Size of the population (school, district, state)
- Uniqueness of attribute combinations
- Availability of external data for linkage
- Motivation and capability of potential adversaries

**3.2.4 Tokenization and Pseudonymization**

When longitudinal analysis requires linking records:

**Tokenization:**
- Replace identifiers with random tokens
- Maintain mapping only if necessary for contracted services
- Destroy mapping when no longer needed

**Pseudonymization:**
- Replace identifiers with consistent pseudonyms
- Pseudonymized data is NOT de-identified under FERPA
- Retains all privacy protections applicable to PII

**Note:** Pseudonymized data that can be re-linked to individuals is NOT de-identified.

### 3.3 De-identification Process

**3.3.1 Request and Approval**

Before de-identifying student data:
1. Document purpose for de-identification
2. Specify intended use of de-identified data
3. Obtain approval from Student Data Privacy Officer
4. Document de-identification method to be applied

**3.3.2 Execution**

De-identification is performed by:
1. Authorized personnel with de-identification training
2. Following documented procedures for the data type
3. Using approved tools and methods
4. Maintaining audit trail of transformations

**3.3.3 Verification**

Before data is classified as de-identified:
1. Review output for residual identifiers
2. Verify aggregation thresholds are met
3. Assess re-identification risk
4. Document verification in de-identification log

**3.3.4 Re-identification Risk Assessment**

For each de-identification:
- Evaluate risk of re-identification given:
  - Available external data sources
  - Population uniqueness
  - Data recipient capabilities
- Document risk assessment findings
- Apply additional protections if risk is elevated

### 3.4 Uses of De-identified Data

**3.4.1 Permitted Uses**

Properly de-identified data may be used for:
- Internal research and analytics
- Product improvement and feature development
- Aggregate reporting and benchmarking
- Academic research (with appropriate agreements)
- Published research and white papers

**3.4.2 Restrictions**

Even de-identified data is subject to:
- Purpose documented at time of de-identification
- Prohibition on re-identification attempts
- Appropriate security controls
- Ethical use standards

**3.4.3 External Sharing**

When sharing de-identified data externally:
- Verify data meets de-identification standards
- Include prohibition on re-identification in agreements
- Document recipient and purpose
- Consider additional aggregation for public release

### 3.5 Re-identification Prohibition

**3.5.1 Internal Prohibition**

**[Company Name]** workforce members shall NOT:
- Attempt to re-identify de-identified student data
- Link de-identified data to other sources to identify students
- Use de-identified data in ways that could reveal student identities

**3.5.2 External Agreements**

When sharing de-identified data, agreements include:
- Prohibition on re-identification attempts
- Prohibition on linking to external data for identification
- Requirement to notify **[Company Name]** if re-identification occurs
- Consequences for violation (termination of agreement, data return)

**3.5.3 Incident Response**

If re-identification occurs or is suspected:
1. Immediately report to Student Data Privacy Officer
2. Assess scope and impact
3. Determine if data should be reclassified as PII
4. Take remedial action (additional de-identification, data destruction)
5. Document incident and lessons learned

### 3.6 Documentation and Audit

**3.6.1 De-identification Log**

Maintain records for each de-identification:
- Original data source and categories
- Purpose of de-identification
- Method applied
- Verification performed
- Date and personnel involved
- Intended use and recipients

**3.6.2 Retention of Records**

De-identification documentation retained for:
- **[Number, e.g., 3]** years after de-identification
- Duration of use of de-identified data (whichever is longer)

**3.6.3 Audit Capability**

**[Company Name]** maintains ability to:
- Demonstrate de-identification methods used
- Verify compliance with standards
- Respond to school or regulatory inquiries

### 3.7 Special Considerations

**3.7.1 Small Populations**

For data from small schools or unique programs:
- Apply stricter aggregation thresholds
- Consider whether de-identification is achievable
- May need to forgo release if re-identification risk is too high

**3.7.2 Longitudinal Data**

For data tracked over time:
- Additional risk from temporal patterns
- Consider differential privacy techniques
- Limit granularity of time-series data

**3.7.3 Sensitive Data Elements**

For particularly sensitive data (disability status, disciplinary records):
- Apply enhanced de-identification measures
- Higher aggregation thresholds
- Consider whether inclusion is necessary

## 4. Standards Compliance

| Requirement | Citation | [Company Name] Control |
|-------------|----------|------------------------|
| PII removal for de-identification | 34 CFR 99.31(b)(1) | This policy Section 3.1 |
| Reasonable determination standard | FERPA guidance | This policy Section 3.3.4 |
| COPPA de-identification | 16 CFR 312.2 | This policy Section 3.1.2 |
| Statistical disclosure controls | NCES guidance | This policy Section 3.1.3 |
| No sale of de-identified data | SOPIPA, state laws | STU-POL-004 (does not prohibit) |

## 5. Definitions

| Term | Definition |
|------|------------|
| **De-identification** | Removal of personally identifiable information such that remaining data cannot reasonably identify an individual |
| **Direct Identifier** | Information that directly identifies an individual (name, SSN, student ID) |
| **Indirect Identifier** | Information that could identify an individual in combination (DOB, zip code, school) |
| **Quasi-Identifier** | Combination of attributes that could uniquely identify an individual |
| **Tokenization** | Replacement of identifiers with random tokens without maintaining a mapping |
| **Pseudonymization** | Replacement of identifiers with consistent pseudonyms (can be re-linked) |
| **Aggregation** | Combining individual records into summary statistics |
| **Small Cell Suppression** | Withholding statistics based on small numbers to prevent identification |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Student Data Privacy Officer** | Approve de-identification requests; oversee standards compliance |
| **Data Science/Analytics** | Perform de-identification; conduct risk assessments |
| **Legal/Compliance** | Advise on regulatory requirements; review external sharing agreements |
| **Engineering** | Implement de-identification tools; maintain technical controls |
| **All Workforce Members** | Comply with re-identification prohibition; report concerns |

## 7. Related Documents

- STU-POL-001: Student Data Governance Policy
- STU-POL-004: Student Data Sharing Policy
- STU-POL-005: Data Retention and Destruction Policy
- SEC-POL-002: Data Classification Policy
- STU-PROC-006: De-identification Procedure

## 8. Policy Review

This policy is reviewed annually and upon:
- Changes to FERPA or state de-identification guidance
- Advances in re-identification techniques
- Incidents involving re-identification
- Changes to data analytics practices

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
