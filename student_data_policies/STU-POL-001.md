# Student Data Governance Policy (STU-POL-001)

## 1. Objective

This policy establishes **[Company Name]**'s framework for governing student data received from educational institutions. It defines what constitutes student data under applicable laws (FERPA, COPPA, and state student privacy laws), establishes data inventory and classification requirements, and ensures that student data is handled only for legitimate educational purposes.

## 2. Scope

This policy applies to all **[Company Name]** workforce members, contractors, and third parties who access, process, store, or transmit student data. It covers:

- All student data received from K-12 schools, school districts, and higher education institutions
- Student data collected directly from students or parents through **[Company Name]** products
- Both personally identifiable information (PII) and de-identified student data
- Data in all forms: electronic, paper, verbal, and visual

**Applicability Note:**
- **K-12**: Full COPPA compliance required for children under 13; school consent model typically applies
- **Higher Education**: Students are "eligible students" with direct rights under FERPA; COPPA generally does not apply

## 3. Policy

**[Company Name]** is committed to responsible stewardship of student data in accordance with FERPA (34 CFR Part 99), COPPA (16 CFR Part 312), applicable state student privacy laws, and industry best practices.

### 3.1 Definition of Student Data

**3.1.1 Education Records (FERPA)**

Education records are records that:
- Are directly related to a student; AND
- Are maintained by an educational agency or institution, or by a party acting for the agency or institution

Education records include, but are not limited to:
- Student names and identifiers (student ID, email, login credentials)
- Demographic information (date of birth, grade level, school)
- Academic records (grades, transcripts, test scores, assignments)
- Attendance and enrollment records
- Disciplinary records
- Special education records (IEPs, 504 plans)
- Health records maintained by the school
- Parent/guardian contact information

**Exclusions from Education Records:**
- Sole possession records (teacher's private notes not shared with anyone)
- Law enforcement unit records
- Employment records (unless employment is contingent on student status)
- Records created after the individual is no longer a student
- Grades on peer-graded papers before they are collected by the teacher

**3.1.2 Personal Information (COPPA)**

For children under 13, personal information includes:
- First and last name
- Home or physical address
- Online contact information (email, screen name)
- Telephone number
- Social Security number
- Persistent identifiers (customer numbers, cookies, IP addresses when used to contact a specific individual)
- Photographs, videos, or audio files containing a child's image or voice
- Geolocation information sufficient to identify street name and city
- Any other information concerning the child or parent combined with the above

**3.1.3 Student Data Inventory**

**[Company Name]** maintains a comprehensive inventory of all student data elements collected, processed, and stored. The inventory includes:

| Data Element | Source | Purpose | Retention Period | Sensitivity Level |
|--------------|--------|---------|------------------|-------------------|
| **[Example: Student Name]** | **[School API/Direct Entry]** | **[Account creation]** | **[Contract term + 60 days]** | **[High]** |

The Student Data Privacy Officer reviews and updates the inventory **[Frequency, e.g., annually]** and upon any material change to data collection practices.

### 3.2 Legitimate Educational Interest

**[Company Name]** accesses and uses student data solely for legitimate educational purposes as specified in contracts with educational institutions.

**3.2.1 Permitted Uses**

Student data may only be used for purposes that:
- Are specified in the Data Processing Agreement (DPA) with the educational institution
- Directly support the educational services contracted by the institution
- Are necessary for the operation, maintenance, or security of the service
- Are required by law or legal process

**Permitted Use Examples:**
- Providing the contracted educational services
- Authenticating and authorizing users
- Maintaining and improving service functionality
- Providing customer support
- Generating usage reports for schools
- Ensuring service security and preventing fraud

**3.2.2 Prohibited Uses**

Student data shall NOT be used for:
- Targeted advertising to students or parents based on student data
- Creating advertising profiles
- Selling student data to third parties
- Any purpose not specified in the DPA or outside the scope of contracted services
- Amending education records without proper school authorization

### 3.3 Data Classification

**[Company Name]** classifies all student data according to sensitivity level:

| Classification | Description | Examples | Handling Requirements |
|----------------|-------------|----------|----------------------|
| **Restricted** | Highest sensitivity; special regulatory protections | Special education records, disability accommodations, disciplinary records, health information | Encryption required, access limited to essential personnel, audit logging mandatory |
| **Confidential** | Standard education records requiring protection | Grades, test scores, attendance, contact information | Encryption in transit/at rest, role-based access, logging required |
| **Internal** | Operational data with limited sensitivity | Aggregate usage statistics, de-identified analytics | Standard security controls, no special restrictions |
| **Public** | No sensitivity; approved for disclosure | School name, published course information | No restrictions |

### 3.4 Data Minimization

**[Company Name]** adheres to data minimization principles:

- **Collection Limitation**: Collect only the minimum student data necessary to provide contracted services
- **Purpose Limitation**: Use student data only for specified, legitimate educational purposes
- **Storage Limitation**: Retain student data only as long as necessary to fulfill contracted purposes
- **Access Limitation**: Grant access to student data only to personnel with legitimate need

Before collecting any new student data element, the requestor must:
1. Document the business/educational need
2. Confirm no existing data element can serve the purpose
3. Obtain approval from the Student Data Privacy Officer
4. Update the data inventory

### 3.5 Directory Information

Directory information is data that would not generally be considered harmful if disclosed. Under FERPA, schools may designate certain information as directory information and disclose it without consent.

**3.5.1 [Company Name] Position on Directory Information**

Even when schools designate information as directory information, **[Company Name]**:
- Does not publicly disclose directory information
- Treats directory information with the same protections as other student data
- Does not rely on the directory information exception to use data beyond contracted purposes

**3.5.2 Common Directory Information Elements**

Schools may designate as directory information:
- Student name
- Address
- Telephone number
- Email address
- Date and place of birth
- Major field of study
- Grade level
- Enrollment status
- Participation in activities and sports
- Dates of attendance
- Degrees and awards received
- Most recent school attended

### 3.6 Data Governance Responsibilities

**3.6.1 Student Data Privacy Officer**

**[Company Name]** designates a Student Data Privacy Officer with responsibility for:
- Overseeing student data governance
- Maintaining the student data inventory
- Reviewing and approving new data collection practices
- Coordinating with schools on data requests and incidents
- Ensuring compliance with FERPA, COPPA, and state laws
- Training workforce on student data handling

**3.6.2 Data Stewards**

Data Stewards are assigned for each product or service that processes student data. Responsibilities include:
- Ensuring data is handled according to this policy
- Maintaining accurate data inventories for their area
- Responding to data access requests
- Reporting data incidents promptly

## 4. Standards Compliance

| Requirement | FERPA | COPPA | SOC 2 | Student Privacy Pledge |
|-------------|-------|-------|-------|------------------------|
| Data inventory and classification | 34 CFR 99.31(a)(1) | 16 CFR 312.8 | CC6.1 | Commitment 1 |
| Legitimate educational purpose | 34 CFR 99.31(a)(1)(i)(B) | 16 CFR 312.5 | CC6.1 | Commitment 2 |
| Data minimization | 34 CFR 99.31 | 16 CFR 312.7 | CC6.5 | Commitment 3 |
| No advertising based on student data | — | 16 CFR 312.5(c)(6) | — | Commitment 4 |
| No sale of student data | — | 16 CFR 312.5(c)(6) | — | Commitment 5 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **Education Records** | Records directly related to a student and maintained by an educational agency or institution, or by a party acting for the agency (per FERPA 34 CFR 99.3) |
| **Eligible Student** | A student who has reached 18 years of age or is attending an institution of postsecondary education (per FERPA 34 CFR 99.3) |
| **Legitimate Educational Interest** | A school official has a legitimate educational interest if the official needs to review an education record to fulfill their professional responsibility |
| **Personal Information** | Under COPPA, individually identifiable information about a child collected online |
| **School Official** | A party to whom an educational agency or institution has outsourced institutional services or functions, provided specific criteria are met |
| **Student Data** | Any information directly related to an identifiable current or former student |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Executive Leadership** | Allocate resources for student data governance; ensure organizational commitment to student privacy |
| **Student Data Privacy Officer** | Oversee student data governance program; maintain data inventory; coordinate compliance activities |
| **Data Stewards** | Manage student data within their area of responsibility; ensure policy compliance |
| **Engineering** | Implement technical controls for student data protection; build privacy-by-design features |
| **Product Management** | Ensure products collect only necessary data; document data flows |
| **Legal/Compliance** | Review DPAs; advise on regulatory requirements; respond to legal inquiries |
| **Customer Success** | Facilitate school data requests; communicate data practices to schools |
| **All Workforce Members** | Handle student data according to this policy; report data concerns; complete training |

## 7. Related Documents

- STU-POL-002: School Official Designation Policy
- STU-POL-003: Parental Consent and Rights Policy
- STU-POL-004: Student Data Sharing Policy
- STU-POL-005: Data Retention and Destruction Policy
- STU-POL-006: De-identification Policy
- PRV-POL-001: FERPA Compliance Policy
- PRV-POL-002: COPPA Compliance Policy
- PRV-POL-003: State Privacy Laws Policy
- STU-PROC-001: Student Data Inventory Procedure
- ANNEX-004: Student Data Inventory Template

## 8. Policy Review

This policy is reviewed annually and updated as needed based on:
- Changes to FERPA, COPPA, or state student privacy laws
- New products or services that process student data
- Feedback from schools, auditors, or regulators
- Lessons learned from incidents or near-misses

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
