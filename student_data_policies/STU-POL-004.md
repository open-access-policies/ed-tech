# Student Data Sharing Policy (STU-POL-004)

## 1. Objective

This policy governs **[Company Name]**'s sharing and disclosure of student data to third parties. It ensures that student data is shared only for legitimate educational purposes and in compliance with FERPA, COPPA, state student privacy laws, and contractual obligations to schools.

## 2. Scope

This policy applies to:
- All disclosure of student data to parties outside **[Company Name]**
- All subcontractors and service providers with access to student data
- All integrations with third-party systems
- All workforce members who authorize or facilitate data sharing

## 3. Policy

**[Company Name]** shares student data only when necessary to provide contracted educational services and only with appropriate safeguards.

### 3.1 Fundamental Principles

**3.1.1 Prohibitions**

**[Company Name]** does NOT:
- **Sell student data** to any third party for any purpose
- **Rent or lease** student data
- **Disclose for advertising** student data for targeted advertising purposes
- **Share for profiling** student data for creating commercial profiles
- **Share with data brokers** or marketing companies

**3.1.2 Permitted Sharing**

Student data may only be shared:
- To provide contracted educational services
- With subcontractors performing essential functions (under contract)
- As directed by the contracting school
- As required by law or legal process
- To protect safety in emergencies

### 3.2 Disclosure Categories

**3.2.1 Disclosure to Schools**

**[Company Name]** discloses student data to contracting schools:
- Usage reports and analytics
- Assessment results and progress data
- Administrative and compliance information
- Any data the school requests about its students

Schools are not considered "third parties" for purposes of this policy.

**3.2.2 Disclosure to Parents and Eligible Students**

Upon school direction, **[Company Name]** provides:
- Student's own education records
- Account information and activity data
- Responses to rights requests (see STU-POL-003)

**3.2.3 Disclosure to Subcontractors**

**[Company Name]** may share student data with approved subcontractors who:
- Provide services essential to **[Company Name]**'s educational services
- Are bound by written agreements with equivalent privacy protections
- Process data only for specified purposes
- Maintain appropriate security controls

**Examples of Permitted Subcontractor Functions:**
- Cloud infrastructure hosting
- Customer support platforms (with data minimization)
- Analytics for service improvement (aggregated/de-identified where possible)
- Security services (monitoring, incident response)

**3.2.4 Disclosure for Legal Compliance**

**[Company Name]** may disclose student data:
- In response to valid subpoenas, court orders, or warrants
- To regulatory agencies with lawful authority
- As required by law

**Before Legal Disclosure:**
1. Verify validity of legal process
2. Notify contracting school (unless prohibited by law)
3. Limit disclosure to data specifically required
4. Document disclosure per FERPA record-keeping requirements

**3.2.5 Disclosure for Safety**

In health or safety emergencies, **[Company Name]** may disclose:
- To appropriate authorities to protect student safety
- To schools regarding safety threats
- Without consent when necessary to address the emergency

**After Emergency Disclosure:**
1. Document the disclosure
2. Notify the school as soon as practicable
3. Record in disclosure log

### 3.3 Subcontractor Management

**3.3.1 Due Diligence**

Before engaging subcontractors with student data access:
- Evaluate privacy and security practices
- Review data handling policies
- Assess ability to comply with FERPA/COPPA/state laws
- Verify SOC 2 or equivalent certification where appropriate

**3.3.2 Contractual Requirements**

All subcontractor agreements include:

| Requirement | Description |
|-------------|-------------|
| **Use limitation** | Data used only for specified services |
| **No further disclosure** | Cannot share data without authorization |
| **Security obligations** | Maintain appropriate security controls |
| **FERPA compliance** | Comply with FERPA as agent of **[Company Name]** |
| **Breach notification** | Notify **[Company Name]** within **[Number, e.g., 24]** hours |
| **Data return/destruction** | Delete data upon termination |
| **Audit rights** | **[Company Name]** may audit compliance |

**3.3.3 Ongoing Oversight**

**[Company Name]** monitors subcontractors through:
- Periodic assessment of privacy practices
- Review of security certifications
- Incident tracking and response evaluation
- Annual compliance attestations

**3.3.4 Subcontractor List**

**[Company Name]** maintains a list of subcontractors with access to student data. Schools may request this list and information about subcontractor data access.

### 3.4 Integration and API Controls

**3.4.1 School-Directed Integrations**

Schools may direct **[Company Name]** to share data with other systems:
- Learning Management Systems (LMS)
- Student Information Systems (SIS)
- Assessment platforms
- Other school-authorized tools

**Requirements:**
- Written authorization from school
- Data limited to integration purpose
- Technical security (encrypted transmission, authentication)

**3.4.2 API Security**

When providing APIs that access student data:
- Authentication required (OAuth 2.0 or equivalent)
- School authorization required to access their data
- Rate limiting and monitoring
- Audit logging of API access
- Scope limitations to necessary data

### 3.5 Re-disclosure Prohibition

**3.5.1 FERPA Re-disclosure Requirements**

When **[Company Name]** shares education records with third parties:
- Recipients may not re-disclose without school consent
- **[Company Name]** includes re-disclosure prohibition in agreements
- Condition of disclosure: data used only for intended purpose

**3.5.2 Documentation**

For each disclosure to third parties (except schools):
- Name of recipient
- Legitimate interest in information
- Date of disclosure
- Description of information disclosed

### 3.6 Research and Analytics

**3.6.1 Internal Analytics**

**[Company Name]** may use student data for:
- Improving educational services
- Ensuring service quality and security
- Generating reports for schools

Internal analytics use de-identified or aggregated data where possible.

**3.6.2 External Research**

**[Company Name]** does not share identifiable student data for external research without:
- School authorization in the DPA; OR
- Specific research agreement with appropriate safeguards

Research sharing, if authorized, complies with:
- FERPA's studies exception (34 CFR 99.31(a)(6))
- IRB approval where applicable
- Data use agreements with research institutions

## 4. Standards Compliance

| Requirement | Citation | [Company Name] Control |
|-------------|----------|------------------------|
| No sale of student data | SOPIPA, state laws | This policy Section 3.1.1 |
| Re-disclosure prohibition | 34 CFR 99.33 | This policy Section 3.5 |
| Record of disclosures | 34 CFR 99.32 | This policy Section 3.5.2 |
| School official subcontractors | 34 CFR 99.31(a)(1) | This policy Section 3.3 |
| COPPA disclosure limits | 16 CFR 312.5 | This policy Section 3.2 |
| Student Privacy Pledge | Commitment 5 | This policy Section 3.1.1 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **Disclosure** | Permitting access to or release of education records or personally identifiable information |
| **Third Party** | Any party other than **[Company Name]**, the contracting school, or the student/parent |
| **Subcontractor** | A third party engaged by **[Company Name]** to perform services requiring access to student data |
| **Re-disclosure** | Disclosure by a recipient of education records to another party |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Student Data Privacy Officer** | Approve subcontractors; oversee data sharing practices |
| **Legal/Compliance** | Review subcontractor agreements; advise on disclosures |
| **Procurement** | Include required terms in subcontractor contracts |
| **Engineering** | Implement API security and integration controls |
| **All Workforce Members** | Share data only through approved channels |

## 7. Related Documents

- STU-POL-001: Student Data Governance Policy
- STU-POL-002: School Official Designation Policy
- PRV-POL-001: FERPA Compliance Policy
- SEC-POL-005: Vendor and Third-Party Risk Management Policy
- ANNEX-005: School DPA Template

## 8. Policy Review

This policy is reviewed annually and upon:
- Changes to FERPA or state data sharing requirements
- Addition of new subcontractors
- Significant changes to integration capabilities

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
