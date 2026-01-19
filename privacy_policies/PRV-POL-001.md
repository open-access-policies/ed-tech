# FERPA Compliance Policy (PRV-POL-001)

## 1. Objective

This policy establishes **[Company Name]**'s compliance framework for the Family Educational Rights and Privacy Act (FERPA), 20 U.S.C. § 1232g, and its implementing regulations at 34 CFR Part 99. As a technology provider receiving education records from educational institutions, **[Company Name]** operates under the "school official" exception and maintains strict compliance with FERPA requirements.

## 2. Scope

This policy applies to:
- All education records received from educational agencies and institutions
- All workforce members, contractors, and subcontractors who access education records
- All products and services that process student data from schools

**Applicability Note:**
- **K-12 Schools**: Parents have FERPA rights until the student turns 18 or enters postsecondary education
- **Higher Education**: Students are "eligible students" and exercise FERPA rights directly
- **Both**: When a student turns 18 or enters postsecondary education, rights transfer to the student

## 3. Policy

**[Company Name]** ensures full compliance with FERPA requirements governing the privacy of education records and the rights of parents and eligible students.

### 3.1 School Official Exception (34 CFR 99.31(a)(1))

**[Company Name]** qualifies as a "school official" under FERPA by meeting all required criteria in its Data Processing Agreements (DPAs) with educational institutions.

**3.1.1 Criteria for School Official Status**

Each DPA with an educational institution specifies that **[Company Name]**:

1. **Performs an institutional service or function** for which the school would otherwise use employees
2. **Is under the direct control** of the school with respect to the use and maintenance of education records
3. **Uses education records only for authorized purposes** specified in the DPA
4. **Meets the criteria in the school's annual FERPA notification** to parents regarding third-party disclosures

**3.1.2 Direct Control Requirements**

**[Company Name]** demonstrates direct control by schools through:

| Control Mechanism | Implementation |
|-------------------|----------------|
| **Written Agreement** | DPA specifies permitted uses, security requirements, and data handling obligations |
| **Use Limitations** | Data used only for contracted educational purposes; no secondary uses |
| **Access Restrictions** | Access limited to personnel providing contracted services |
| **Audit Rights** | Schools may audit compliance with DPA terms |
| **Data Return/Destruction** | Upon contract termination, data returned or destroyed per school direction |
| **Breach Notification** | Schools notified within **[Number, e.g., 24]** hours of any data breach |

### 3.2 Education Records Handling

**3.2.1 Receipt of Education Records**

**[Company Name]** receives education records through:
- Secure API integrations with Student Information Systems (SIS)
- Secure file transfers (SFTP, encrypted email)
- Rostering protocols (OneRoster, Clever, ClassLink)
- Direct data entry by school administrators

All data transfers must use encryption (TLS 1.2 or higher) and authenticate the sending institution.

**3.2.2 Use Limitations**

Education records received by **[Company Name]** are used ONLY for:
- Providing the specific educational services contracted by the school
- Account provisioning and authentication
- Customer support at school request
- Maintaining service security
- Generating reports for the contracting school
- As otherwise specified in the DPA

**Prohibited Uses:**
- Targeted advertising
- Building user profiles for non-educational purposes
- Selling or renting education records
- Using data for **[Company Name]**'s own research without school approval
- Sharing with third parties not authorized by the school

**3.2.3 Re-disclosure Prohibition**

**[Company Name]** shall not disclose education records to third parties unless:
- Specifically authorized in the DPA
- Required by law or legal process (with notice to the school where permitted)
- Necessary for subcontractors under equivalent contractual protections

All subcontractors with access to education records must agree in writing to comply with FERPA requirements.

### 3.3 Parent and Eligible Student Rights

**[Company Name]** supports schools in fulfilling their obligations to parents and eligible students under FERPA.

**3.3.1 Right to Inspect and Review**

When a school forwards a parent or eligible student's request to inspect education records:
- **[Company Name]** responds within **[Number, e.g., 5]** business days
- Records are provided in a format accessible to the requestor
- No charge is assessed for providing access (though reasonable copying fees may apply)

**3.3.2 Right to Request Amendment**

When schools forward requests to amend education records:
- **[Company Name]** corrects factual errors within **[Number, e.g., 10]** business days
- For disputed content, **[Company Name]** follows the school's direction
- Schools retain authority over the content of education records

**3.3.3 Right to Consent**

**[Company Name]** relies on school authorization for disclosure of education records under the school official exception. **[Company Name]** does not directly obtain consent from parents or eligible students for data use, as the school-**[Company Name]** relationship is governed by the DPA.

### 3.4 Permitted Disclosures Without Consent

Under FERPA, certain disclosures are permitted without consent. **[Company Name]** may disclose education records:

| Exception | Conditions | [Company Name] Practice |
|-----------|------------|-------------------------|
| **School officials with legitimate educational interest** | Under direct control of school | Primary basis for access |
| **Health or safety emergency** | Immediate threat to safety | Notify school immediately; document |
| **Subpoena or court order** | Valid legal process | Notify school before disclosure if permitted |
| **Directory information** | School has designated and notified parents | Do not disclose without school direction |
| **Research** | Study to improve instruction | Only with school DPA authorization |

### 3.5 Record-Keeping Requirements

**[Company Name]** maintains records of disclosures as required by FERPA:

**3.5.1 Disclosure Log**

For each disclosure of education records (except disclosures to school officials), **[Company Name]** records:
- Name of the party receiving records
- Legitimate interest in obtaining the information
- Date of disclosure
- Types of records disclosed

**3.5.2 Retention of Disclosure Records**

Disclosure records are maintained for as long as the education records are maintained and are available for inspection by:
- The contracting school
- Parents or eligible students (upon request)
- Authorized government officials

### 3.6 Annual Notification Support

**[Company Name]** provides schools with information necessary for their annual FERPA notification to parents, including:
- Description of services provided
- Types of education records accessed
- Statement of **[Company Name]**'s school official designation
- Confirmation that data will not be used for secondary purposes

### 3.7 Data Security

**[Company Name]** maintains security controls appropriate for education records:

- **Encryption**: All education records encrypted in transit (TLS 1.2+) and at rest (AES-256)
- **Access Control**: Role-based access; least privilege; MFA for all access
- **Monitoring**: Audit logging of all access to education records
- **Incident Response**: Documented procedures for data breaches with school notification
- **Employee Training**: All workforce members trained on FERPA requirements

See SEC-POL-001 (Information Security Policy) for detailed security controls.

### 3.8 Data Retention and Return/Destruction

**3.8.1 Retention Period**

Education records are retained only as long as necessary to:
- Fulfill the contracted services
- Meet legal or regulatory requirements
- Comply with the school's retention directives

Default retention: **[Duration, e.g., 60 days after contract termination]** unless the school specifies otherwise.

**3.8.2 Upon Contract Termination**

At school direction, **[Company Name]** will:
- **Return** education records in a standard, portable format; AND/OR
- **Destroy** education records using secure destruction methods

A certificate of destruction is provided upon request.

See STU-POL-005 (Data Retention and Destruction Policy) for detailed procedures.

## 4. Standards Compliance

| FERPA Requirement | Citation | [Company Name] Control |
|-------------------|----------|------------------------|
| School official exception | 34 CFR 99.31(a)(1) | DPA terms; this policy Section 3.1 |
| Direct control by school | 34 CFR 99.31(a)(1)(i)(B)(1) | DPA audit rights; use limitations |
| Use limitation | 34 CFR 99.31(a)(1)(i)(B)(2) | This policy Section 3.2.2 |
| Criteria in annual notification | 34 CFR 99.31(a)(1)(i)(B)(3) | This policy Section 3.6 |
| Disclosure without consent exceptions | 34 CFR 99.31 | This policy Section 3.4 |
| Record of disclosures | 34 CFR 99.32 | This policy Section 3.5 |
| Right to inspect | 34 CFR 99.10-12 | This policy Section 3.3.1 |
| Right to amend | 34 CFR 99.20-21 | This policy Section 3.3.2 |
| Re-disclosure prohibition | 34 CFR 99.33 | This policy Section 3.2.3 |
| Security safeguards | 34 CFR 99.31(a)(1)(ii) | SEC-POL-001; this policy Section 3.7 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **Education Records** | Records directly related to a student and maintained by an educational agency or institution, or by a party acting for such agency or institution (34 CFR 99.3) |
| **Eligible Student** | A student who has reached 18 years of age or is attending an institution of postsecondary education (34 CFR 99.3) |
| **Parent** | A natural parent, guardian, or individual acting as a parent in the absence of a parent or guardian (34 CFR 99.3) |
| **Personally Identifiable Information (PII)** | Information that includes direct identifiers (name, Social Security Number) or indirect identifiers (date of birth, place of birth) or other information that would allow identification of a specific student |
| **School Official** | A contractor or service provider to whom the educational agency or institution has outsourced institutional services or functions (34 CFR 99.31(a)(1)(i)(B)) |
| **Directory Information** | Information contained in an education record that would not generally be considered harmful if disclosed (34 CFR 99.3) |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Student Data Privacy Officer** | Ensure FERPA compliance; manage relationships with schools on data matters; oversee DPA compliance |
| **Legal/Compliance** | Review DPAs for FERPA compliance; advise on FERPA requirements; respond to legal process |
| **Product/Engineering** | Implement FERPA-compliant data handling features; maintain security controls |
| **Customer Success** | Communicate FERPA practices to schools; facilitate data requests |
| **All Workforce Members** | Handle education records according to this policy; complete FERPA training |

## 7. Related Documents

- STU-POL-001: Student Data Governance Policy
- STU-POL-002: School Official Designation Policy
- STU-POL-003: Parental Consent and Rights Policy
- STU-POL-005: Data Retention and Destruction Policy
- SEC-POL-001: Information Security Policy
- STU-PROC-002: School Data Request Response Procedure
- ANNEX-001: FERPA Control Mapping
- ANNEX-005: School DPA Template

## 8. Policy Review

This policy is reviewed annually and upon any:
- Changes to FERPA regulations or Department of Education guidance
- Significant changes to data processing practices
- Material incidents involving education records

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
