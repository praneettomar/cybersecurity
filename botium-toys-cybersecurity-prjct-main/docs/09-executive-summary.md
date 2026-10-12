# 09. Executive Summary: Cybersecurity Internal Audit and Risk Assessment

## 1. Assessment Overview

This assessment reviews the cybersecurity controls, information assets, risk exposure, and selected compliance considerations of Botium Toys, a fictional toy retailer with a physical business location and an international e-commerce operation.

The assessment is based on the supplied case materials. It identifies reported control weaknesses, evaluates potential business consequences, and proposes a prioritised remediation roadmap.

The original case report assigns Botium Toys a risk score of 8 out of 10. This score is retained as a source finding. The numerical risk ratings used in the accompanying risk register are separate, provisional estimates based on the methodology documented in this portfolio.

## 2. Overall Assessment

The case materials identify weaknesses in access management, protection of payment information, security monitoring, and business recovery preparedness.

These weaknesses may expose the organisation to unauthorised access, loss or disclosure of sensitive information, disruption of business operations, and difficulty recovering from a security incident.

The assessment also identifies existing controls, including a firewall, antivirus software, privacy policies and procedures, physical locks, CCTV, and fire detection and prevention systems.

However, the presence of a control does not establish that it is effective. Further testing and supporting evidence would be required to confirm the design and operation of these safeguards.

## 3. Key Findings

### Finding 1: Sensitive Data Protection Requires Improvement

The case materials report that credit card data handled or stored locally is not encrypted. They also indicate that all employees have access to internally stored data, which may include customer personal information and payment information.

**Business implication:** Unnecessary access and inadequate protection of sensitive information may increase the likelihood and impact of a data breach.

**Recommended priority:** High.

**Management action:** Review payment data flows, restrict access according to business requirements, and implement appropriate safeguards for sensitive information.

### Finding 2: Access Management Is Inadequate

The reported environment lacks least-privilege enforcement and separation of duties. The password policy exists but is described as weak, and there is no central password management system.

**Business implication:** Excessive permissions and weak account management may increase the risk of unauthorised access, misuse of privileges, and difficulty managing employee access.

**Recommended priority:** High.

**Management action:** Establish role-based access, review user permissions, strengthen authentication practices, and introduce suitable account management processes.

### Finding 3: Recovery Preparedness Is Weak

The case materials report that critical data is not backed up and that a disaster recovery plan is absent.

**Business implication:** A major system failure, cyberattack, or accidental data loss could result in extended disruption and loss of business information.

**Recommended priority:** High.

**Management action:** Identify critical systems, implement protected backups, test restoration, and develop a disaster recovery plan with approved recovery objectives.

### Finding 4: Security Detection and Monitoring Need Improvement

The case materials report that an intrusion detection system is absent. Legacy systems are monitored and maintained manually, but the process lacks a defined schedule and clear intervention methods.

**Business implication:** Security events may remain undetected for longer, while inconsistent legacy maintenance may leave known weaknesses unresolved.

**Recommended priority:** High.

**Management action:** Define monitoring requirements, establish alert-handling procedures, and implement a scheduled legacy system maintenance process.

### Finding 5: Compliance Evidence and Data Governance Need Strengthening

The case materials identify gaps involving payment card protection, customer data classification, access governance, and confidentiality of sensitive information.

Some documented practices already exist, including privacy procedures and a process to notify EU customers within 72 hours. Their scope, operation, and applicability require further validation.

**Business implication:** Weak data governance and incomplete evidence may make it difficult to demonstrate that applicable obligations and security requirements are being met.

**Recommended priority:** High.

**Management action:** Establish a data inventory and classification process, confirm applicable legal and contractual requirements, assign control owners, and retain evidence of control operation.

## 4. Priority Recommendations

The recommended sequence is:

| Priority | Recommended Action | Expected Business Benefit |
|---|---|---|
| 1 | Review access to payment and customer information. | Reduces unnecessary exposure of sensitive data. |
| 2 | Map payment data flows and implement appropriate protection. | Improves payment data security and supports scope validation. |
| 3 | Establish protected backups and test restoration. | Improves the ability to recover critical information. |
| 4 | Implement least privilege and stronger account management. | Reduces unauthorised access and excessive permissions. |
| 5 | Strengthen security monitoring and alert handling. | Improves visibility into potential security incidents. |
| 6 | Develop disaster recovery and incident response procedures. | Improves operational resilience and response coordination. |
| 7 | Improve data classification and compliance evidence. | Supports accountability and informed compliance decisions. |
| 8 | Introduce regular control reviews and management reporting. | Supports sustained improvement and risk oversight. |

These recommendations should be reviewed against business priorities, available resources, dependencies, and applicable obligations before implementation.

## 5. Proposed Implementation Approach

The accompanying remediation roadmap proposes four phases:

- **Days 0–30:** Address urgent access and data protection concerns, identify critical assets, and assign risk owners.
- **Days 31–60:** Strengthen access management, payment data protection, monitoring, and endpoint and network control reviews.
- **Days 61–90:** Improve backups, recovery planning, incident response, and legacy maintenance.
- **Days 91–180:** Validate controls, conduct exercises, review compliance evidence, and establish ongoing management reporting.

The proposed timeline is a planning estimate for this portfolio exercise. It is not an approved implementation commitment.

## 6. Governance and Accountability

Successful remediation requires clear ownership and management oversight.

The proposed governance model assigns coordination to the IT Manager, security control guidance to the Security Lead, operational implementation to IT Operations, and system-specific responsibilities to System Owners.

Business Owners should define operational requirements and recovery priorities. Privacy and legal advisers should help confirm applicable privacy and regulatory obligations.

Management should receive periodic reporting covering:

- High and critical risks.
- Remediation progress and overdue actions.
- Control validation results.
- Backup and recovery test outcomes.
- Outstanding compliance and evidence gaps.
- Risks requiring formal acceptance or escalation.

Risk acceptance should be documented, authorised, and reviewed. It should not replace required corrective action where applicable obligations must be met.

## 7. Limitations

This assessment is based on the supplied fictional case materials. It does not include independent interviews, technical testing, penetration testing, configuration reviews, or inspection of production systems.

The assessment therefore distinguishes reported weaknesses from items requiring further validation.

The provisional risk ratings in the risk register are analytical estimates. They are not
