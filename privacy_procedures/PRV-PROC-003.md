# State Privacy Laws Compliance Procedure (PRV-PROC-003)

## 1. Purpose

This procedure provides step-by-step instructions for complying with state student privacy laws, including identifying applicable laws, implementing state-specific requirements, and managing state DPA addenda.

## 2. Scope

This procedure applies to Legal, Compliance, Sales, and Customer Success teams who manage state law compliance.

## 3. Procedure

### 3.1 Identifying Applicable State Laws

#### 3.1.1 Determining State Requirements

**When:** Onboarding new school customer or expanding to new state.

**Steps:**

1. **Identify customer state(s)**
   - School/district location
   - Student residence states (if different)

2. **Consult state law matrix** (ANNEX-003)
   - Identify applicable state laws
   - Note key requirements

3. **Key state laws to check**
   | State | Law | Key Requirements |
   |-------|-----|------------------|
   | California | SOPIPA | No targeted ads; no profiling; deletion rights |
   | New York | Ed Law 2-d | Parents' Bill of Rights; encryption; breach notification |
   | Colorado | Student Data Act | Written contract; data inventory |
   | Connecticut | Student Data Privacy Act | Contract; data minimization |
   | Illinois | SOPPA | No targeted ads; breach notification |

4. **Document applicable requirements**
   - Record in customer onboarding
   - Flag for DPA preparation

### 3.2 State-Specific DPA Requirements

#### 3.2.1 Preparing State DPA Addenda

**When:** Contracting with schools in states with specific DPA requirements.

**Steps:**

1. **New York (Education Law 2-d)**
   - Include Parents' Bill of Rights for Data Privacy and Security
   - Provide supplemental information:
     - Exclusive purposes for data use
     - Data elements collected
     - How data will be stored
     - Security protections
     - Breach notification procedures
     - Subcontractor information
   - School must post Parents' Bill of Rights

2. **California (SOPIPA)**
   - Confirm no targeted advertising based on student data
   - Confirm no profiling for non-K-12 purposes
   - Confirm no sale of student information
   - Include deletion upon request provision

3. **Colorado**
   - Include data element inventory
   - Reference security plan
   - Confirm no sale of student data

4. **Other states**
   - Consult ANNEX-003 for state-specific terms
   - Add required provisions to DPA

5. **Execute state addendum**
   - Attach to master DPA
   - Obtain signatures

#### 3.2.2 Using Standardized State DPAs

**When:** State offers standardized DPA template.

**Steps:**

1. **Identify available standard DPAs**
   - SDPC National DPA
   - California K-12 DPA
   - State-specific templates

2. **Review standard DPA**
   - Confirm **[Company Name]** can comply with all terms
   - Identify any concerns

3. **Execute standard DPA**
   - Use state portal if available (SDPC)
   - Or execute with individual district

4. **Document in contract system**
   - Tag with state and standard used

### 3.3 Common State Requirements

#### 3.3.1 Implementing Prohibited Practices

**When:** Ongoing compliance with state prohibitions.

**Steps:**

1. **No sale of student data**
   - All states prohibit
   - Verify no revenue from student data sale
   - Document compliance

2. **No targeted advertising**
   - Most states prohibit (CA, IL, WA, etc.)
   - Verify no behavioral advertising to students
   - Contextual ads only (if any)

3. **No profile building for non-K-12 purposes**
   - CA, IL, others prohibit
   - Student profiles for educational use only
   - No commercial profiling

4. **Document compliance**
   - Record verification
   - Note any exceptions

#### 3.3.2 Implementing Required Practices

**When:** Ensuring state-mandated practices are in place.

**Steps:**

1. **Written contracts**
   - All states require DPA or equivalent
   - Verify executed DPA for all customers

2. **Security measures**
   - State-appropriate security (encryption, access controls)
   - NY requires encryption in transit and at rest
   - Document security implementation

3. **Breach notification**
   - Know state-specific timelines
   - Ensure notification process meets all states
   - See Section 3.5

4. **Deletion rights**
   - Implement deletion upon school/parent request
   - Meet state-specific timelines

5. **Transparency**
   - Publish privacy policy
   - Provide data inventory to schools upon request

### 3.4 New York Education Law 2-d

#### 3.4.1 NY-Specific Requirements

**When:** Serving New York schools.

**Steps:**

1. **Provide Parents' Bill of Rights**
   - Complete template per 8 NYCRR 121.3
   - Attach to agreement
   - School posts for parents

2. **Provide supplemental information**
   - Complete NY supplemental form
   - Include all required elements

3. **Ensure encryption**
   - TLS 1.2+ for data in transit
   - AES-256 for data at rest on mobile devices

4. **Breach notification**
   - Notify school immediately upon discovery
   - Notify NY Chief Privacy Officer per regulation

5. **Annual certification**
   - Provide compliance certification upon request
   - Attest to compliance with 2-d requirements

### 3.5 State Breach Notification

#### 3.5.1 Complying with State Breach Laws

**When:** Data breach affecting students in regulated states.

**Steps:**

1. **Identify affected states**
   - Which states' students affected?
   - Consult state breach notification matrix

2. **Apply state-specific timelines**
   | State | Timeline | Additional Requirements |
   |-------|----------|------------------------|
   | NY | Per 8 NYCRR 121.9 | Notify Chief Privacy Officer |
   | CA | Most expedient time | AG if >500 CA residents |
   | CO | 30 days | AG notification |
   | CT | 60 days | AG notification |

3. **Prepare state-specific notices**
   - Content per state requirements
   - Method per state requirements

4. **Execute notifications**
   - To schools
   - To regulators (AG, Privacy Officer)
   - Schools notify parents

5. **Document compliance**
   - Record all notifications
   - Retain for audit

### 3.6 Monitoring State Law Changes

#### 3.6.1 Tracking Legislative Updates

**When:** Ongoing monitoring.

**Steps:**

1. **Subscribe to updates**
   - Legal counsel alerts
   - Industry associations (SIIA, FPF, SDPC)
   - State education department communications

2. **Review new laws/amendments**
   - Identify compliance impact
   - Assess gap to current practices

3. **Implement changes**
   - Update policies and procedures
   - Update DPAs if needed
   - Train affected personnel

4. **Update state law matrix**
   - Maintain ANNEX-003 current
   - Document effective dates

### 3.7 State Compliance Documentation

#### 3.7.1 Maintaining State Records

**When:** Ongoing compliance documentation.

**Steps:**

1. **State law matrix** (ANNEX-003)
   - Keep current with law changes
   - Review quarterly

2. **State-specific DPA addenda**
   - Maintain templates
   - Update as requirements change

3. **State compliance attestations**
   - NY annual certification
   - Other state certifications

4. **Training records**
   - State-specific training completion
   - Annual refresh

## 4. Escalation

Escalate to Legal/Compliance when:
- New state law enacted
- State regulator inquiry
- Uncertainty about state requirements
- Customer disputes state compliance

## 5. Records

| Record | Retention | Location |
|--------|-----------|----------|
| State DPA addenda | Contract + 7 years | Contract system |
| State compliance attestations | 5 years | Compliance files |
| State law matrix | Current + versions | **[Location]** |
| Breach notification records | 7 years | Incident files |

## 6. References

- PRV-POL-003: State Student Privacy Laws Policy
- RES-POL-003: Breach Notification (Schools) Policy
- ANNEX-003: State Student Privacy Law Matrix
- ANNEX-005: School DPA Template

## 7. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
