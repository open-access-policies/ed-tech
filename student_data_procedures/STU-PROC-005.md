# Data Retention and Destruction Procedure (STU-PROC-005)

## 1. Purpose

This procedure provides step-by-step instructions for retaining and destroying student data in compliance with STU-POL-005, including scheduled destruction, deletion requests, and contract termination.

## 2. Scope

This procedure applies to IT Operations, Engineering, Customer Success, and all workforce members who manage student data lifecycle.

## 3. Procedure

### 3.1 Routine Data Retention

#### 3.1.1 Applying Retention Schedules

**When:** Ongoing basis per retention schedule.

**Steps:**

1. **Identify data categories**
   - Review data inventory for retention periods
   - Note any school-specific retention requirements
   - Identify data approaching retention limit

2. **Configure automated retention**
   - Set up automated deletion for log data
   - Configure backup expiration
   - Enable retention policies in systems

3. **Review exception requests**
   - Legal holds
   - School-directed extended retention
   - Regulatory requirements

4. **Monitor retention compliance**
   - Regular reports on data age
   - Verify automated deletion is functioning
   - Address any gaps

#### 3.1.2 Legal Hold Management

**When:** Legal hold is issued or lifted.

**Steps:**

1. **Receive legal hold notice**
   - Document scope (data types, schools, time period)
   - Document effective date

2. **Implement hold**
   - Suspend deletion for in-scope data
   - Suspend backup rotation for affected data
   - Notify affected teams

3. **Track held data**
   - Maintain inventory of held data
   - Tag data as under legal hold
   - Prevent inadvertent deletion

4. **Lift hold** (when authorized)
   - Receive written release from Legal
   - Resume normal retention schedule
   - Process any pending deletions

### 3.2 Contract Termination

#### 3.2.1 Pre-Termination Data Handling

**When:** School contract is ending (non-renewal or termination).

**Steps:**

1. **Notify school** (per DPA timeline)
   - Provide termination notice
   - Offer data export options
   - Request school's data disposition preference

2. **Prepare data export** (if requested)
   - Generate export in agreed format (CSV, JSON, etc.)
   - Include all student data for the school
   - Validate export completeness

3. **Transfer to school**
   - Use secure transfer method
   - Confirm receipt by school
   - Document transfer

4. **Retain for export window**
   - Maintain data for **[Number, e.g., 60]** days post-termination
   - Allow for additional export requests

#### 3.2.2 Post-Termination Destruction

**When:** Export window has closed.

**Steps:**

1. **Verify export complete**
   - Confirm school received data (or declined export)
   - Document confirmation

2. **Initiate destruction**
   - Identify all systems with school's student data
   - Include production, staging, backups

3. **Execute destruction** (see Section 3.3)
   - Follow secure destruction methods
   - Delete from all systems

4. **Verify destruction**
   - Confirm deletion from all locations
   - Document verification

5. **Provide destruction certificate**
   - Generate certificate per ANNEX-007
   - Send to school contact
   - Retain copy

6. **Close contract record**
   - Document termination completion
   - Archive customer record

### 3.3 Secure Destruction Methods

#### 3.3.1 Electronic Data Destruction

**When:** Destroying student data from electronic systems.

**Steps:**

1. **Identify storage locations**
   - Primary database
   - File storage
   - Search indexes
   - Caches
   - Backups

2. **Select destruction method**
   | Storage Type | Method |
   |--------------|--------|
   | Database records | SQL DELETE with verification |
   | File storage | Secure delete API |
   | Cloud storage | Provider deletion + key destruction |
   | Local SSD | Cryptographic erasure |
   | Local HDD | Secure overwrite (NIST 800-88) |

3. **Execute destruction**
   - Run deletion scripts/commands
   - Destroy encryption keys (for encrypted data)
   - Document commands executed

4. **Verify destruction**
   - Query systems to confirm no data remains
   - Check replica/secondary locations
   - Document verification

5. **Address backups**
   - Backups expire per retention schedule
   - For immediate deletion: mark for exclusion from restores
   - Document backup handling

#### 3.3.2 Physical Media Destruction

**When:** Decommissioning hardware containing student data.

**Steps:**

1. **Identify media**
   - Hard drives, SSDs, tapes, etc.
   - Document serial numbers

2. **Select destruction method**
   | Media Type | Method |
   |------------|--------|
   | HDD | Degaussing or physical destruction |
   | SSD | Physical destruction |
   | Tape | Degaussing or physical destruction |
   | Paper | Cross-cut shredding (DIN 66399 P-4+) |

3. **Execute destruction**
   - Use certified destruction service if physical
   - Witness or verify destruction

4. **Document destruction**
   - Certificate from destruction service
   - Serial numbers destroyed
   - Date and method

### 3.4 Deletion Requests

#### 3.4.1 Processing Deletion Requests

**When:** School or parent requests data deletion.

**Steps:**

1. **Receive request** (from STU-PROC-003)
   - Verify source and authorization
   - Confirm scope (all data, specific data)

2. **Check for exceptions**
   - Legal hold? → Cannot delete; notify requestor
   - Contractual retention? → Coordinate with school
   - Legal requirement? → Retain required data

3. **Identify data for deletion**
   - All systems with student's data
   - All data types in scope

4. **Execute deletion**
   - Delete from production systems
   - Mark for deletion from backups
   - Delete from subcontractor systems

5. **Verify deletion**
   - Confirm removal from all systems
   - Document verification steps

6. **Confirm to requestor**
   - Notify completion
   - Note any exceptions (data retained by law)
   - Timeline: within **[Number, e.g., 30]** days

7. **Document**
   - Record in deletion log
   - Retain record per schedule

### 3.5 Destruction Verification

#### 3.5.1 Verifying Destruction

**When:** After any data destruction activity.

**Steps:**

1. **Verify primary systems**
   - Query for deleted data
   - Confirm no results returned
   - Screenshot or log verification

2. **Verify secondary systems**
   - Check replicas, caches
   - Check search indexes
   - Verify removal

3. **Verify backups** (where applicable)
   - Confirm backup retention policy
   - Note backup expiration dates
   - Document backup status

4. **Document verification**
   - Date and method of verification
   - Systems checked
   - Results
   - Verifier identity

#### 3.5.2 Generating Destruction Certificate

**When:** School requests certificate of destruction.

**Steps:**

1. **Gather information**
   - School/district name
   - Data categories destroyed
   - Destruction dates
   - Destruction method

2. **Complete certificate template** (ANNEX-007)
   - Fill all required fields
   - Include verification statement

3. **Obtain signature**
   - Authorized signatory (IT Director, Privacy Officer)
   - Date signature

4. **Deliver certificate**
   - Send to school contact
   - Retain copy in customer record

### 3.6 Subcontractor Data Destruction

#### 3.6.1 Directing Subcontractor Destruction

**When:** Requiring subcontractor to delete student data.

**Steps:**

1. **Identify subcontractors with data**
   - Review subcontractor list
   - Identify those with school's data

2. **Send deletion directive**
   - Written instruction to delete
   - Specify school and data scope
   - Set deadline per contract

3. **Receive confirmation**
   - Written confirmation of completion
   - Certificate if available

4. **Verify** (as contract allows)
   - Request evidence of deletion
   - Exercise audit rights if needed

5. **Document**
   - Record directive and confirmation
   - Include in destruction records

## 4. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Destruction log | 7 years | **[System]** |
| Destruction certificates | 7 years | Customer record |
| Legal hold records | Hold + 7 years | Legal files |
| Media destruction records | 7 years | IT records |

## 5. References

- STU-POL-005: Data Retention and Destruction Policy
- STU-PROC-003: Parent Rights Request Procedure
- SEC-POL-006: Media Handling and Destruction Policy
- ANNEX-007: Certificate of Destruction Template

## 6. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
