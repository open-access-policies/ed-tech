# Student Data Governance Procedure (STU-PROC-001)

## 1. Purpose

This procedure provides step-by-step instructions for implementing the Student Data Governance Policy (STU-POL-001), including data classification, inventory management, and governance oversight.

## 2. Scope

This procedure applies to all workforce members who classify, inventory, or manage student data.

## 3. Procedure

### 3.1 Data Classification

#### 3.1.1 Classifying New Data Elements

**When:** New data elements are introduced through product features or integrations.

**Steps:**

1. **Identify data element**
   - Document the data element name and description
   - Identify source (user-provided, school-provided, system-generated)
   - Determine if it relates to students

2. **Determine if Education Record**
   - Is it directly related to a student? (If no → not an education record)
   - Is it maintained by **[Company Name]** on behalf of a school? (If no → not an education record)
   - Does it fit an exclusion (sole possession notes, law enforcement, employment, alumni)? (If yes → not an education record)
   - If yes to first two and no exclusion → classify as Education Record

3. **Apply data category**
   - Education Record: Apply FERPA protections
   - Directory Information: Confirm school has designated; apply appropriate controls
   - De-identified Data: Verify de-identification per STU-POL-006
   - Aggregated Data: Verify aggregation thresholds met

4. **Document classification**
   - Record in data inventory
   - Note applicable regulations (FERPA, COPPA, state laws)
   - Assign data owner

5. **Obtain approval**
   - Submit classification to Student Data Privacy Officer for review
   - Update classification if directed

#### 3.1.2 Re-classifying Existing Data

**When:** Data use changes, regulations change, or annual review identifies need.

**Steps:**

1. Review current classification
2. Assess against current criteria (Section 3.1.1)
3. Document any classification changes
4. Update data inventory
5. Notify affected teams of classification change
6. Update access controls if needed

### 3.2 Data Inventory Management

#### 3.2.1 Adding to Data Inventory

**When:** New data elements are collected, new product features launch, or new integrations are enabled.

**Steps:**

1. **Complete inventory template** (ANNEX-004)
   - Data element name
   - Description and purpose
   - Data category/classification
   - Collection method
   - Storage location(s)
   - Retention period
   - Access roles
   - Legal basis (contract, consent, legitimate interest)

2. **Submit for review**
   - Route to data owner for accuracy confirmation
   - Route to Privacy Officer for approval

3. **Add to master inventory**
   - Update central data inventory system
   - Record approval and date

4. **Communicate updates**
   - Notify affected teams
   - Update documentation as needed

#### 3.2.2 Annual Inventory Review

**When:** Annually, per policy schedule.

**Steps:**

1. **Generate inventory report**
   - Export current inventory
   - Identify data elements for review

2. **Review each category**
   - Confirm data is still collected
   - Verify classification remains accurate
   - Confirm retention periods are appropriate
   - Verify legal basis is still valid

3. **Identify changes needed**
   - Data no longer collected → remove from inventory
   - Classification changes → update per Section 3.1.2
   - Retention changes → update per STU-POL-005

4. **Document review**
   - Record review date and reviewer
   - Document any changes made
   - Report findings to Student Data Privacy Officer

5. **Produce inventory report for schools**
   - Generate school-specific data inventories upon request
   - Include all data elements collected for that school

### 3.3 Legitimate Educational Interest Verification

#### 3.3.1 Verifying Access Requests

**When:** Workforce member requests access to student data.

**Steps:**

1. **Receive access request**
   - Document requestor and role
   - Document specific data and purpose
   - Document school(s) whose data is requested

2. **Verify legitimate educational interest**
   - Is the data needed for a contracted educational service?
   - Is the access within the requestor's job function?
   - Is the access limited to necessary scope?

3. **Approve or deny**
   - If legitimate interest verified → approve with documented scope
   - If not verified → deny and document reason
   - If unclear → escalate to Student Data Privacy Officer

4. **Document decision**
   - Record in access request system
   - Maintain audit trail

#### 3.3.2 Periodic Access Review

**When:** Quarterly or upon role change.

**Steps:**

1. Generate list of personnel with student data access
2. Review each person's legitimate educational interest
3. Remove access no longer justified
4. Document review and any changes
5. Report to Student Data Privacy Officer

### 3.4 Governance Committee Activities

#### 3.4.1 Scheduling Governance Reviews

**When:** Per policy-defined schedule (quarterly or as needed).

**Steps:**

1. **Schedule meeting**
   - Coordinate with committee members
   - Distribute agenda in advance

2. **Prepare materials**
   - Data inventory updates
   - Compliance issues or incidents
   - Policy change proposals
   - New feature privacy reviews

3. **Conduct meeting**
   - Review agenda items
   - Make decisions on policy matters
   - Assign action items

4. **Document outcomes**
   - Record meeting minutes
   - Track action items to completion
   - File documentation

## 4. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Data inventory | Current + 3 years | **[System]** |
| Classification decisions | 3 years | **[System]** |
| Access request records | 3 years | **[System]** |
| Governance meeting minutes | 5 years | **[Location]** |

## 5. References

- STU-POL-001: Student Data Governance Policy
- STU-POL-006: De-identification Policy
- ANNEX-004: Student Data Inventory Template

## 6. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | **[Date]** | **[Author]** | Initial release |
