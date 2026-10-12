# Evidence Collection and Management Guide

## 1. Purpose

This directory documents how supporting evidence should be collected, referenced, reviewed, and protected during the Botium Toys cybersecurity assessment.

The supplied case materials provide the starting point for the assessment. This directory defines a proposed evidence management approach for a real engagement or future practical exercise.

**No independent technical evidence has been collected or verified as part of this portfolio.** The evidence register and procedures described here are proposed methods, not records of completed testing.

## 2. Evidence Management Principles

Evidence should be:

- **Relevant:** Directly related to a finding, risk, control, or recommendation.
- **Traceable:** Linked to a unique evidence ID and the finding it supports.
- **Accurate:** Recorded without changing the meaning of the original information.
- **Current:** Dated and reviewed for relevance.
- **Protected:** Stored with appropriate access restrictions.
- **Minimised:** Limited to the information required for the assessment.
- **Reproducible:** Collected using a documented method where practical.

Evidence should support conclusions rather than simply confirm an existing assumption.

## 3. Proposed Evidence Register

The following register identifies evidence that would be useful in validating the assessment. All items are marked as pending because the underlying evidence has not been independently collected.

| Evidence ID | Evidence Required | Related Assessment Area | Status |
|---|---|---|---|
| E-001 | Current asset inventory | Asset management and scope | Pending |
| E-002 | User access review records | Least privilege and access management | Pending |
| E-003 | Privileged account inventory | Account governance | Pending |
| E-004 | Payment data flow diagram | Payment security and encryption | Pending |
| E-005 | Encryption configuration evidence | Sensitive data protection | Pending |
| E-006 | Backup policy and backup job reports | Backup controls | Pending |
| E-007 | Backup restoration test results | Recovery capability | Pending |
| E-008 | Disaster recovery plan | Business continuity and recovery | Pending |
| E-009 | Security monitoring and alert configuration | Detection capabilities | Pending |
| E-010 | Legacy system maintenance records | Patch and maintenance management | Pending |
| E-011 | Approved security policies | Governance and control design | Pending |
| E-012 | Data classification and retention records | Privacy and data governance | Pending |
| E-013 | Physical access and CCTV maintenance records | Physical security | Pending |
| E-014 | Applicable compliance assessment records | GDPR, PCI DSS, and assurance requirements | Pending |
| E-015 | Control testing results | Overall control effectiveness | Pending |

## 4. Evidence Collection Procedure

For a real authorised assessment, the following procedure should be followed:

1. Define the question or control that requires validation.
2. Identify the evidence needed to answer that question.
3. Obtain approval from the relevant system or business owner.
4. Collect the minimum necessary information using an authorised method.
5. Record the collection date, source, collector, and relevant context.
6. Link the evidence to the relevant finding or risk ID.
7. Review the evidence for completeness, accuracy, and relevance.
8. Record limitations or conflicting evidence.
9. Store the evidence in an approved location with appropriate access controls.
10. Document the conclusion and any further validation required.

Evidence collection must respect organisational policies, legal obligations, and authorised assessment boundaries.

## 5. Evidence-to-Finding Traceability

Each confirmed finding should be supported by one or more evidence references.

For example:

| Finding ID | Assessment Issue | Evidence Needed |
|---|---|---|
| F-01 | Sensitive data protection weakness | E-004, E-005 |
| F-02 | Excessive access and weak account management | E-002, E-003 |
| F-03 | Missing backups and disaster recovery planning | E-006, E-007, E-008 |
| F-04 | Limited security detection and legacy maintenance | E-009, E-010 |
| F-05 | Data governance and compliance evidence gaps | E-012, E-014 |
| F-06 | Control effectiveness requires validation | E-011, E-015 |

These links identify proposed validation requirements. They do not indicate that the evidence has been obtained or that each finding has been independently confirmed.

## 6. Sensitive Information Handling

This repository is public. Do not upload:

- Passwords, API keys, access tokens, or private keys.
- Customer names, email addresses, payment card details, or personal records.
- Unredacted security logs or configuration exports.
- Internal IP addresses, sensitive network diagrams, or exploitable system details.
- Confidential policies, contracts, or proprietary documents.
- Evidence collected without appropriate authorisation.

Where an example is needed, use fictional or synthetic data. If real evidence is collected in an authorised environment, keep it in an approved private storage location and publish only a sanitised summary when disclosure is permitted.

Removing a file in a later commit does not necessarily remove it from repository history. Sensitive information should never be committed in the first place.

## 7. Evidence Quality and Review

Before using evidence to support a conclusion, check:

- Does it relate directly to the stated control or risk?
- Is the source identifiable and trustworthy?
- Is the evidence sufficiently recent?
- Does it demonstrate control design, implementation, or actual operation?
- Are there missing records or alternative explanations?
- Does the conclusion go beyond what the evidence establishes?

A policy document may demonstrate that a policy exists, but it does not prove that employees follow it. A backup job report may show that a job completed, but it does not prove that the data can be restored successfully. Restoration testing is needed to validate recovery capability.

## 8. Conclusion

Evidence management supports reliable findings, transparent risk decisions, and defensible recommendations.

For this portfolio, the evidence register is a proposed validation plan. In a real engagement, evidence would need to be collected through authorised processes, reviewed, protected, and linked to the final assessment findings.

