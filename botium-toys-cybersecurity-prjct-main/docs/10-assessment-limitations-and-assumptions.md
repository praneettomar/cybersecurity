# 10. Assessment Limitations and Assumptions

## 1. Purpose

This document explains the assumptions, limitations, and evidence requirements associated with the Botium Toys cybersecurity assessment.

The purpose is to make the assessment transparent and prevent conclusions from being presented with more certainty than the available information supports.

Botium Toys is a fictional organisation used for this portfolio exercise. The assessment is based on supplied case materials and does not represent an engagement with a real company.

## 2. Assessment Basis

The assessment uses the following supplied materials:

- Botium Toys Scope, Goals, and Risk Assessment Report.
- Botium Toys Controls and Compliance Checklist.
- Botium Toys Control Categories and Descriptions.
- Related portfolio activity instructions.

These materials describe the business environment, selected security controls, identified weaknesses, and compliance-related observations.

The assessment interprets those observations and develops additional analytical outputs, including an asset inventory, risk register, framework mapping, and remediation roadmap.

These outputs are the author's analysis and recommendations. They should not be interpreted as additional facts independently verified by Botium Toys.

## 3. Key Assumptions

| ID | Assumption | Reason | Validation Required |
|---|---|---|---|
| A-01 | The organisation operates a physical retail business and an online store. | This is described in the supplied case materials. | Confirm business and system boundaries in a real engagement. |
| A-02 | The listed IT systems and assets represent the known assessment environment. | The case materials identify relevant systems and technology assets. | Obtain a complete and current asset inventory. |
| A-03 | Reported control weaknesses are treated as assessment findings for this exercise. | The checklist identifies controls as absent or inadequate. | Review configurations, procedures, records, and operating evidence. |
| A-04 | Risk ratings are preliminary estimates rather than measured incident probabilities. | No quantitative incident or loss data was supplied. | Validate ratings with business and technical owners. |
| A-05 | Proposed asset classifications and criticality ratings are analytical judgements. | The source material does not provide a complete formal classification scheme. | Confirm business impact, data sensitivity, and asset ownership. |
| A-06 | Remediation timelines and proposed owners are illustrative. | No approved budget, staffing plan, or implementation schedule was supplied. | Obtain management approval and confirm available resources. |
| A-07 | GDPR, PCI DSS, and SOC 2 are relevant assessment reference points, subject to applicability. | The case includes international customers, payment information, and control objectives relevant to these frameworks. | Confirm legal scope, payment processing arrangements, contractual obligations, and assurance requirements. |

## 4. Assessment Limitations

### 4.1 No Direct Technical Testing

No live systems were accessed or tested as part of this portfolio exercise.

The work does not include:

- Penetration testing or vulnerability scanning.
- Firewall or endpoint configuration reviews.
- Source code review.
- Identity and access management testing.
- Network traffic analysis.
- Backup restoration testing.
- Incident response simulations.
- Verification of security alerts or monitoring coverage.

Consequently, the assessment does not establish whether systems can actually be exploited or whether reported controls operate effectively.

### 4.2 Limited Evidence

The supplied materials do not include configuration exports, access logs, vulnerability reports, incident records, backup test results, or signed policy approvals.

Where such evidence is unavailable, the assessment records the reported condition and identifies the additional evidence needed.

A control described as present is not automatically considered effective. Its design, implementation, and operation would need to be verified.

### 4.3 Preliminary Risk Ratings

The source report assigns Botium Toys a risk score of 8 out of 10.

The risk register in this portfolio uses a separate proposed likelihood-and-impact methodology. Those scores are analytical estimates developed for prioritisation and are not a recalculation or replacement of the original score.

The ratings may change when additional evidence, threat information, business impact analysis, or management input becomes available.

### 4.4 Compliance Assessment Limitations

The compliance assessment is a preliminary gap analysis against selected requirements and control objectives. It is not a formal compliance audit or legal opinion.

Applicability depends on factors such as the organisation's operations, data flows, payment processing arrangements, jurisdictions, contractual commitments, and assurance objectives.

The assessment does not establish that a legal violation has occurred. It identifies areas that require further investigation and evidence.

### 4.5 Business Impact and Financial Estimates

The supplied materials do not provide reliable financial loss estimates, revenue figures, recovery costs, incident history, or detailed business impact analysis.

Therefore, the portfolio does not assign monetary values to individual risks or claim a quantified return on security investment.

A real assessment should obtain business impact information and use it to support investment decisions and recovery priorities.

## 5. Evidence Required for Further Validation

The following evidence would strengthen the assessment if this were a real engagement.

| Area | Evidence Required | Purpose |
|---|---|---|
| Asset management | Current asset register, system owners, data flows, and system classifications. | Confirm the scope and identify critical assets. |
| Access management | User lists, role definitions, privileged account records, and access review results. | Validate least privilege and account governance. |
| Payment security | Payment data flow diagrams, system boundaries, encryption settings, and relevant PCI DSS evidence. | Determine where payment data is handled and which safeguards apply. |
| Data protection | Data inventory, classification rules, retention schedules, and access restrictions. | Evaluate how sensitive information is identified and protected. |
| Monitoring | Logging configuration, alert rules, incident tickets, and monitoring coverage. | Assess the ability to detect and investigate security events. |
| Backup and recovery | Backup policies, job reports, restoration test results, and recovery objectives. | Verify that critical information can be restored. |
| Legacy systems | System versions, patch records, maintenance schedules, and exception approvals. | Assess exposure arising from outdated or inconsistently maintained systems. |
| Physical security | Access records, CCTV maintenance records, and fire safety inspection evidence. | Validate the operation of physical safeguards. |
| Governance | Approved policies, risk acceptance records, assigned owners, and management reports. | Establish accountability and oversight. |
| Privacy and compliance | Applicable legal assessments, privacy procedures, contractual requirements, and compliance evidence. | Confirm obligations and evaluate supporting controls. |

## 6. Confidence in Findings

Confidence describes the strength of the available supporting information, not the severity of a risk.

For this portfolio, confidence is assessed qualitatively:

- **High:** The supplied case materials explicitly describe the condition.
- **Medium:** The condition is reasonably inferred from the supplied materials but requires clarification.
- **Low:** The issue is primarily a validation requirement or depends on information not supplied.

These confidence labels are preliminary and should be updated as evidence becomes available.

## 7. Appropriate Use of This Portfolio

This portfolio is intended to demonstrate cybersecurity assessment, risk analysis, control mapping, compliance awareness, and remediation planning skills.

It is suitable as a learning project and as a discussion artefact during interviews.

It should not be presented as:

- A completed penetration test.
- An independent audit of a real organisation.
- A formal GDPR, PCI DSS, or SOC 2 certification.
- Proof that a system is secure or insecure beyond the evidence described.
- An approved implementation plan for a real business.

## 8. Conclusion

A credible cybersecurity assessment must distinguish documented facts, analytical judgements, assumptions, and unverified conditions.

This portfolio follows that principle by identifying the source of its findings, documenting its proposed risk methodology, explaining its limitations, and specifying the evidence required for further validation.

The next step in a real engagement would be to obtain stakeholder input, collect supporting evidence, validate risk ratings, and agree on an authorised remediation plan.

## 9. References

- Botium Toys Scope, Goals, and Risk Assessment Report, supplied case material.
- Botium Toys Controls and Compliance Checklist, supplied case material.
- NIST Cybersecurity Framework 2.0: https://www.nist.gov/cyberframework
- NIST SP 800-30 Rev. 1, Guide for Conducting Risk Assessments: https://csrc.nist.gov/pubs/sp/800/30/r1/final
- Regulation (EU) 2016/679 (GDPR): https://eur-lex.europa.eu/eli/reg/2016/679/oj
- PCI Security Standards Council: https://www.pcisecuritystandards.org/
