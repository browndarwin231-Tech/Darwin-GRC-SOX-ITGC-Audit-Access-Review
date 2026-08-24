# SOX ITGC Remediation Plan

## Purpose

This remediation plan addresses the control weaknesses identified during the simulated SOX ITGC audit for CloudNova Financial Systems.

The goal is to assign corrective actions, responsible owners, target timelines, validation evidence, and closure criteria for each identified finding.

---

## Remediation Summary

| Action ID | Finding | ITGC Area | Risk Level | Owner | Target Timeline | Status |
|---|---|---|---|---|---|---|
| SOX-RA-001 | Terminated User Access Removal | Access Management | High | IT / HR | 30 Days | Open |
| SOX-RA-002 | Quarterly User Access Review | Access Management | High | IT Security / GRC | 30 Days | Open |
| SOX-RA-003 | Privileged Access Review | Access Management | High | IT Security | 30 Days | Open |
| SOX-RA-004 | Segregation of Duties Conflicts | Access / Change Management | High | GRC / Finance / IT | 60 Days | Open |
| SOX-RA-005 | Change Testing Evidence | Change Management | Medium | Application Management | 60 Days | Open |
| SOX-RA-006 | Emergency Change Review | Change Management | Medium | Change Management | 60 Days | Open |
| SOX-RA-007 | Independent Production Approval | Change Management | High | IT Management | 30 Days | Open |
| SOX-RA-008 | Backup Restoration Testing | IT Operations | Medium | IT Operations | 90 Days | Open |
| SOX-RA-009 | Scheduled Job Exception Documentation | IT Operations | Medium | IT Operations | 60 Days | Open |
| SOX-RA-010 | Control Ownership | Governance | Medium | GRC / IT Leadership | 90 Days | Open |

---

## SOX-RA-001: Improve Terminated User Access Removal

### Issue

Some terminated-user accounts are not disabled immediately.

### Corrective Action

- Integrate HR termination notifications with IT offboarding
- Disable accounts on the employee termination date
- Record disablement timestamps
- Review inactive accounts quarterly
- Escalate delayed removals

### Success Criteria

- 100% of sampled terminated users disabled on time
- Disablement evidence retained
- No active accounts for former employees identified during review

### Validation Evidence

- HR termination records
- Account disablement logs
- Access timestamps
- Quarterly inactive-user review

### Target Timeline

**30 Days**

---

## SOX-RA-002: Formalize Quarterly User Access Reviews

### Issue

Quarterly access review documentation is incomplete.

### Corrective Action

- Generate quarterly system-access reports
- Assign designated reviewers
- Validate business need for each user's access
- Remove unnecessary permissions
- Retain approval evidence
- Track exceptions through closure

### Success Criteria

- Quarterly reviews completed
- Reviewer decisions documented
- Unnecessary access removed
- Exceptions tracked and resolved

### Validation Evidence

- Access review reports
- Reviewer approvals
- Removed-access evidence
- Exception records

### Target Timeline

**30 Days**

---

## SOX-RA-003: Strengthen Privileged Access Reviews

### Issue

Privileged access is not reviewed consistently.

### Corrective Action

- Maintain a privileged-account inventory
- Document business justification
- Assign account owners
- Perform quarterly privileged-access reviews
- Apply least privilege
- Remove unnecessary administrator access

### Success Criteria

- All privileged accounts inventoried
- Quarterly review completed
- Business justification documented
- Unnecessary privileges removed

### Validation Evidence

- Privileged account inventory
- Access review report
- Approval records
- Removed-role evidence

### Target Timeline

**30 Days**

---

## SOX-RA-004: Resolve Segregation of Duties Conflicts

### Issue

Some users have conflicting permissions.

### Corrective Action

- Develop a segregation-of-duties matrix
- Identify conflicting role combinations
- Remove unnecessary conflicts
- Document compensating controls when conflicts cannot be removed
- Require management approval for exceptions

### Success Criteria

- SoD matrix completed
- High-risk conflicts resolved
- Compensating controls documented
- Exceptions formally approved

### Validation Evidence

- SoD conflict report
- Access change records
- Compensating-control documentation
- Management approvals

### Target Timeline

**60 Days**

---

## SOX-RA-005: Require Complete Change Testing Evidence

### Issue

Testing occurs, but documentation is incomplete for some changes.

### Corrective Action

Require change records to include:

- Test scenario
- Expected result
- Actual result
- Tester
- Test date
- Test evidence
- Approval before deployment

### Success Criteria

- 100% of sampled production changes include testing evidence
- Failed tests are remediated before deployment
- Approval occurs after testing

### Validation Evidence

- Change tickets
- Test screenshots
- Test results
- Production approvals

### Target Timeline

**60 Days**

---

## SOX-RA-006: Formalize Emergency Change Reviews

### Issue

Post-implementation review of emergency changes is inconsistent.

### Corrective Action

Require every emergency change to include:

- Emergency justification
- Implementation details
- Approval
- Testing performed
- Production impact
- Retrospective review
- Follow-up actions

### Success Criteria

- 100% of emergency changes receive retrospective review
- Review evidence retained
- Follow-up actions tracked

### Validation Evidence

- Emergency change tickets
- Retrospective approvals
- Testing records
- Follow-up documentation

### Target Timeline

**60 Days**

---

## SOX-RA-007: Enforce Independent Production Approval

### Issue

Some changes are developed and approved by the same individual.

### Corrective Action

Separate responsibility for:

- Development
- Testing
- Approval
- Production deployment

Where full separation is not possible, require an independent compensating review.

### Success Criteria

- No sampled high-risk change lacks independent approval
- Compensating controls documented where necessary
- Production approvals retained

### Validation Evidence

- Change tickets
- Approval records
- Deployment records
- Compensating-review documentation

### Target Timeline

**30 Days**

---

## SOX-RA-008: Perform Quarterly Backup Restoration Testing

### Issue

Backups are performed, but restoration testing is inconsistent.

### Corrective Action

- Schedule quarterly restore tests
- Test critical financial systems
- Record recovery time
- Document successful and failed restores
- Track corrective actions

### Success Criteria

- Quarterly tests completed
- Critical systems successfully restored
- Recovery results documented
- Failed tests remediated

### Validation Evidence

- Restore test reports
- Backup logs
- Recovery-time results
- Corrective-action records

### Target Timeline

**90 Days**

---

## SOX-RA-009: Improve Scheduled Job Exception Documentation

### Issue

Failed scheduled jobs are not always documented through resolution.

### Corrective Action

Require failed-job records to include:

- Job name
- Failure date and time
- Error message
- Business impact
- Assigned owner
- Corrective action
- Resolution date
- Reviewer approval

### Success Criteria

- All failed critical jobs documented
- Remediation traceable
- Resolution evidence retained

### Validation Evidence

- Job monitoring logs
- Exception tickets
- Resolution records
- Review approvals

### Target Timeline

**60 Days**

---

## SOX-RA-010: Formalize ITGC Control Ownership

### Issue

Some key ITGC controls do not have clearly documented owners.

### Corrective Action

Create an ITGC control inventory containing:

- Control ID
- Control description
- ITGC area
- Control owner
- Review frequency
- Evidence required
- Current status

### Success Criteria

- 100% of key controls assigned an owner
- Review frequency documented
- Evidence requirements defined

### Validation Evidence

- ITGC control inventory
- Owner assignments
- Management approval

### Target Timeline

**90 Days**

---

## Closure Process

A remediation action should only be marked **Closed** after:

1. Corrective action is completed
2. Supporting evidence is collected
3. GRC or audit reviewer validates the evidence
4. Remaining risk is documented
5. Closure approval is recorded

---

## Final Goal

The goal of this remediation plan is to strengthen SOX ITGC control effectiveness and improve audit readiness.

High-risk access and change-management findings should be remediated first, followed by medium-risk operational and governance findings.
