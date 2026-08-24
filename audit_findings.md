# SOX ITGC Audit Findings

## Purpose

This document summarizes control exceptions identified during the simulated SOX ITGC audit for CloudNova Financial Systems.

The review focuses on access management, privileged access, change management, segregation of duties, and IT operations controls supporting financial reporting systems.

---

## Finding 1: Terminated User Access Removal

### Current State

User termination procedures exist, but some account disablement evidence shows delays between employee termination and access removal.

### Risk

Former employees may retain access to systems supporting financial reporting.

### Risk Level

**High**

### ITGC Area

**Access Management**

### Gap

The organization does not consistently remove terminated-user access immediately.

### Recommendation

Automate offboarding where possible and require:

- Immediate account disablement
- HR-to-IT termination notification
- Disablement timestamps
- Quarterly review of inactive accounts
- Evidence retention

---

## Finding 2: Quarterly User Access Review

### Current State

Quarterly access reviews are performed, but approval documentation is incomplete for some review periods.

### Risk

Users may retain unnecessary or inappropriate access to financial systems.

### Risk Level

**High**

### ITGC Area

**Access Management**

### Gap

Access reviews are not consistently documented and approved.

### Recommendation

Perform formal quarterly access reviews that include:

- User name
- Role
- Access level
- Business justification
- Reviewer
- Review decision
- Removed access
- Approval date

---

## Finding 3: Privileged Access Review

### Current State

Privileged accounts exist across financial applications and cloud systems, but recurring review evidence is incomplete.

### Risk

Users may retain excessive administrative access.

### Risk Level

**High**

### ITGC Area

**Access Management**

### Gap

Privileged access is not consistently reviewed.

### Recommendation

Perform quarterly privileged-access reviews and document:

- Account owner
- Privileged role
- Business justification
- Reviewer decision
- Removed privileges
- Approval evidence

---

## Finding 4: Segregation of Duties Conflict

### Current State

Some users have conflicting access rights, including combinations of requester and approver permissions.

### Risk

A user may be able to initiate and approve the same transaction or system activity without independent oversight.

### Risk Level

**High**

### ITGC Area

**Access Management / Change Management**

### Gap

Segregation-of-duties conflicts are not consistently identified and remediated.

### Recommendation

Maintain a formal SoD conflict matrix and perform recurring reviews.

Where conflicts cannot be removed, document compensating controls and management approval.

---

## Finding 5: Change Testing Evidence

### Current State

Production changes are generally approved before deployment.

However, testing evidence is not consistently attached to change records.

### Risk

Untested or insufficiently tested changes may affect financial reporting systems.

### Risk Level

**Medium**

### ITGC Area

**Change Management**

### Gap

Testing evidence is incomplete for some changes.

### Recommendation

Require documented testing before production approval.

Evidence should include:

- Test scenario
- Expected result
- Actual result
- Tester
- Test date
- Approval

---

## Finding 6: Emergency Change Review

### Current State

Emergency changes are documented, but post-implementation review is inconsistent.

### Risk

Emergency changes may bypass standard approval or testing controls.

### Risk Level

**Medium**

### ITGC Area

**Change Management**

### Gap

Emergency changes are not always reviewed after implementation.

### Recommendation

Require retrospective review of all emergency changes.

Document:

- Reason for emergency
- Change details
- Approver
- Testing performed
- Production impact
- Post-implementation review
- Follow-up action

---

## Finding 7: Independent Production Approval

### Current State

Some changes were approved or deployed by the same individual who developed the change.

### Risk

Lack of independent approval may allow unauthorized or inappropriate production changes.

### Risk Level

**High**

### ITGC Area

**Change Management**

### Gap

Segregation between development and production deployment is inconsistent.

### Recommendation

Separate:

- Development
- Testing
- Approval
- Production deployment

Where separation is not possible, require documented compensating review.

---

## Finding 8: Backup Restoration Testing

### Current State

Backups are performed regularly, but restoration testing is inconsistent.

### Risk

The organization may be unable to recover financial systems or data during a disruption.

### Risk Level

**Medium**

### ITGC Area

**IT Operations**

### Gap

There is insufficient evidence that backups can be successfully restored.

### Recommendation

Perform quarterly restoration testing and document:

- System tested
- Backup selected
- Test date
- Recovery result
- Recovery time
- Issues identified
- Corrective actions

---

## Finding 9: Scheduled Job Exception Documentation

### Current State

Scheduled system jobs are monitored.

However, failed-job remediation evidence is inconsistent.

### Risk

Processing failures may affect financial reporting or business operations.

### Risk Level

**Medium**

### ITGC Area

**IT Operations**

### Gap

Failed jobs are not always documented through resolution.

### Recommendation

Require failed-job records to include:

- Job name
- Failure date/time
- Error
- Business impact
- Assigned owner
- Corrective action
- Resolution date
- Reviewer approval

---

## Finding 10: Control Ownership

### Current State

Most ITGC controls have identified owners, but ownership documentation is incomplete.

### Risk

Control failures may remain unresolved if accountability is unclear.

### Risk Level

**Medium**

### ITGC Area

**Governance**

### Gap

Not every key ITGC control has a formally documented owner.

### Recommendation

Maintain an ITGC control inventory containing:

- Control ID
- Control description
- Control owner
- Review frequency
- Evidence required
- Current status

---

## Overall Findings Summary

| Finding | ITGC Area | Risk Level |
|---|---|---|
| Terminated User Access Removal | Access Management | High |
| Quarterly User Access Review | Access Management | High |
| Privileged Access Review | Access Management | High |
| Segregation of Duties Conflict | Access / Change Management | High |
| Change Testing Evidence | Change Management | Medium |
| Emergency Change Review | Change Management | Medium |
| Independent Production Approval | Change Management | High |
| Backup Restoration Testing | IT Operations | Medium |
| Scheduled Job Exception Documentation | IT Operations | Medium |
| Control Ownership | Governance | Medium |

---

## Conclusion

The SOX ITGC review identified several control weaknesses involving access governance, privileged access, segregation of duties, change management, and IT operations.

The highest-priority remediation items involve terminated-user access, quarterly access reviews, privileged access, segregation of duties, and independent change approval.

Addressing these findings would strengthen control effectiveness and improve SOX audit readiness.
