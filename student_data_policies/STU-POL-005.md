# Data Retention and Destruction Policy (STU-POL-005)

## 1. Objective

This policy establishes **[Company Name]**'s requirements for retaining and destroying student data. It ensures that student data is retained only as long as necessary to fulfill educational purposes and contractual obligations, and is securely destroyed when no longer needed.

## 2. Scope

This policy applies to:
- All student data and education records in **[Company Name]**'s custody
- All systems, applications, and storage media containing student data
- All workforce members responsible for data retention and destruction
- All contracts with educational institutions

## 3. Policy

**[Company Name]** retains student data only for the period necessary to provide contracted educational services and comply with legal requirements. Data is securely destroyed when retention is no longer justified.

### 3.1 Retention Principles

**3.1.1 Contract-Limited Retention**

Student data retention is governed by contracts with educational institutions:
- Default retention: Duration of contract plus **[Number, e.g., 60]** days for data export
- Extended retention: Only if specified in the DPA
- Post-termination: Data returned to school and/or destroyed per contract terms

**3.1.2 Purpose Limitation**

Student data is retained only when there is a legitimate purpose:
- Providing contracted educational services
- Meeting legal or regulatory requirements
- Responding to school or parent requests
- Protecting **[Company Name]**'s legal interests (with limitations)

**3.1.3 Data Minimization**

During the retention period:
- Retain only data elements necessary for the stated purpose
- Review data holdings periodically to identify data no longer needed
- De-identify or aggregate data where full retention is unnecessary

### 3.2 Retention Periods

**3.2.1 Standard Retention Schedule**

| Data Category | Retention Period | Basis |
|---------------|------------------|-------|
| **Active student records** | Duration of contract | Operational necessity |
| **Student account data** | Contract + **[Number, e.g., 60]** days | Export window |
| **Usage and activity logs** | **[Number, e.g., 12]** months | Service improvement; security |
| **Assessment and progress data** | Contract + export window | School access |
| **Support communications** | **[Number, e.g., 24]** months | Service quality |
| **De-identified analytics** | Indefinite | No longer personal information |

**3.2.2 Legal Hold Exceptions**

Data subject to legal hold is retained until:
- Legal hold is lifted by Legal/Compliance
- Litigation or investigation is concluded
- Regulatory retention period expires

**3.2.3 School-Directed Retention**

Schools may direct **[Company Name]** to:
- Retain specific data longer than standard periods
- Delete data earlier than standard periods
- Return data in specified formats

**[Company Name]** follows school direction unless legally prohibited.

### 3.3 Contract Termination

**3.3.1 Pre-Termination Notice**

Before contract termination:
1. Notify school **[Number, e.g., 30]** days in advance (or per contract)
2. Provide data export options and formats
3. Confirm school's data disposition preferences

**3.3.2 Data Export**

Upon request, **[Company Name]** provides:
- Student data in machine-readable format (CSV, JSON, or standard format)
- Documentation of data elements included
- Export within **[Number, e.g., 30]** days of request

**3.3.3 Post-Termination Destruction**

After contract termination and export window:

| Timeframe | Action |
|-----------|--------|
| **0-30 days** | Complete data export if requested |
| **31-60 days** | Initiate destruction process |
| **By day 60** | Complete destruction of all student data |
| **Within 90 days** | Provide destruction certificate if requested |

### 3.4 Deletion Requests

**3.4.1 School-Initiated Deletion**

When schools direct deletion:
1. Verify request from authorized contact
2. Confirm scope of deletion (specific students, all data, etc.)
3. Execute deletion within **[Number, e.g., 30]** days
4. Confirm completion to school

**3.4.2 Parent/Student-Initiated Deletion**

For deletion requests from parents or eligible students:
1. School forwards request to **[Company Name]** (or verifies direct request)
2. **[Company Name]** confirms scope with school
3. Execute deletion per school direction
4. Confirm completion to school (who notifies parent/student)

**3.4.3 COPPA Deletion Rights**

For children under 13:
- Parents may request deletion of personal information
- **[Company Name]** deletes within **[Number, e.g., 30]** days
- Service access may be terminated if data is essential

**3.4.4 State Law Deletion Rights**

**[Company Name]** honors deletion rights under state laws:
- California (SOPIPA, CCPA)
- New York (Education Law 2-d)
- Colorado, Connecticut, and others

See PRV-POL-003 for state-specific requirements.

### 3.5 Destruction Methods

**3.5.1 Secure Destruction Standards**

All student data destruction follows secure methods:

| Storage Type | Destruction Method | Standard |
|--------------|-------------------|----------|
| **Electronic records (HDD)** | Secure overwrite or degaussing | NIST SP 800-88 |
| **Electronic records (SSD)** | Cryptographic erasure or physical destruction | NIST SP 800-88 |
| **Cloud storage** | Cryptographic key destruction; provider deletion | Provider SLA |
| **Paper records** | Cross-cut shredding | DIN 66399 Level P-4+ |
| **Backup media** | Secure overwrite or physical destruction | NIST SP 800-88 |

**3.5.2 Cloud Infrastructure**

For data in cloud environments:
- Delete data from primary storage
- Confirm deletion from replicas and caches
- Verify backup expiration or deletion
- Document cloud provider destruction confirmation

**3.5.3 Backups**

Backup data containing student information:
- Expires according to backup retention schedule (typically **[Number, e.g., 30-90]** days)
- Specific student data deleted from backups upon explicit request (where technically feasible)
- Backup media destroyed when decommissioned

### 3.6 Destruction Verification

**3.6.1 Internal Verification**

For each destruction event:
- Document data categories destroyed
- Record destruction method and date
- Verify completion across all systems
- Retain destruction log for **[Number, e.g., 3]** years

**3.6.2 Destruction Certificate**

Upon school request, **[Company Name]** provides a certificate of destruction including:
- School/district name
- Description of data destroyed
- Destruction method
- Date of destruction
- Authorized signature

**Template:** See ANNEX-007 (Certificate of Destruction Template)

**3.6.3 Audit Trail**

Destruction records include:
- Requestor and authorization
- Data scope and categories
- Systems and storage locations
- Personnel involved
- Verification steps completed

### 3.7 Subcontractor Data Destruction

**3.7.1 Subcontractor Obligations**

Subcontractors with student data must:
- Destroy data when instructed by **[Company Name]**
- Follow equivalent destruction standards
- Provide confirmation of destruction
- Maintain destruction records

**3.7.2 Verification**

**[Company Name]** verifies subcontractor destruction through:
- Written confirmation of completion
- Audit rights in subcontractor agreements
- Periodic compliance assessments

### 3.8 Exceptions to Destruction

**3.8.1 Permitted Retention**

Data may be retained beyond standard periods when:
- Required by law or regulation
- Subject to legal hold
- Necessary to complete a transaction requested by the school
- In de-identified or aggregated form (no longer personal information)
- School has directed extended retention

**3.8.2 De-identified Data**

When student data is properly de-identified per STU-POL-006:
- It is no longer subject to destruction requirements
- May be retained for research and product improvement
- Must meet de-identification standards before retention

## 4. Standards Compliance

| Requirement | Citation | [Company Name] Control |
|-------------|----------|------------------------|
| Delete data upon school request | SOPIPA, state laws | This policy Section 3.4 |
| Contract-limited retention | FERPA school official | This policy Section 3.1.1 |
| Secure destruction | SOC 2 CC6.5 | This policy Section 3.5 |
| COPPA retention limits | 16 CFR 312.10 | This policy Section 3.4.3 |
| NY 2-d data destruction | 8 NYCRR 121.3 | This policy Section 3.3 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **Retention Period** | The duration for which data is kept before destruction |
| **Destruction** | The permanent removal of data such that it cannot be recovered |
| **Legal Hold** | A directive to preserve data relevant to litigation or investigation |
| **Cryptographic Erasure** | Destruction of encryption keys rendering encrypted data unrecoverable |
| **De-identification** | Removal of identifiers such that data is no longer personally identifiable |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Student Data Privacy Officer** | Oversee retention compliance; approve retention exceptions |
| **Legal/Compliance** | Issue legal holds; advise on regulatory retention requirements |
| **IT Operations** | Execute data destruction; maintain destruction logs |
| **Engineering** | Implement retention automation; ensure backup compliance |
| **Customer Success** | Coordinate with schools on data export and destruction |
| **All Workforce Members** | Follow retention schedules; report data for destruction |

## 7. Related Documents

- STU-POL-001: Student Data Governance Policy
- STU-POL-004: Student Data Sharing Policy
- STU-POL-006: De-identification Policy
- SEC-POL-002: Data Classification Policy
- SEC-POL-006: Media Handling and Destruction Policy
- OP-POL-005: School District Onboarding Policy
- ANNEX-007: Certificate of Destruction Template

## 8. Policy Review

This policy is reviewed annually and upon:
- Changes to FERPA, COPPA, or state retention requirements
- Changes to data storage infrastructure
- Audit findings or compliance issues

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
