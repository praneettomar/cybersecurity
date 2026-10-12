# 03. Security Controls Assessment

## 1. Purpose

This document assesses the security controls described in the Botium Toys case study.

The objective is to determine which controls are documented as implemented, which are missing, and which require improvement. The assessment also considers how each condition may affect business operations, information security, and risk exposure.

The assessment is based on the supplied case materials. The effectiveness of controls has not been independently tested.

## 2. Assessment Method

Each control is assessed using one of the following statuses:

- **Implemented:** The source material confirms that the control exists.
- **Missing:** The source material explicitly states that the control is absent.
- **Needs improvement:** The control exists, but the source material identifies weaknesses in its implementation.
- **Partially established:** Some elements exist, but the control is incomplete or lacks a clearly defined process.

These statuses describe the information available in the case. They do not represent the results of technical testing.

## 3. Administrative and Managerial Controls

| Control ID | Control | Status | Source-Based Finding | Business Risk | Recommended Action |
|---|---|---|---|---|---|
| CTRL-01 | Least privilege | Missing | All employees have access to internally stored data. | Unauthorised access to sensitive information and greater impact from compromised accounts. | Introduce role-based access and grant users only the access required for their responsibilities. |
| CTRL-02 | Disaster recovery plans | Missing | No disaster recovery plans are in place. | Prolonged disruption after a major incident or system failure. | Develop, approve, and test a disaster recovery plan. |
| CTRL-03 | Password policies | Needs improvement | A password policy exists, but its requirements are inadequate. | Increased exposure to password-based attacks and account compromise. | Establish an appropriate password policy aligned with current security guidance. |
| CTRL-04 | Separation of duties | Missing | Separation of duties has not been implemented. | One individual may have excessive control over sensitive activities. | Separate conflicting responsibilities and establish independent approval for sensitive actions. |

## 4. Technical Controls

| Control ID | Control | Status | Source-Based Finding | Business Risk | Recommended Action |
|---|---|---|---|---|---|
| CTRL-05 | Firewall | Implemented | A firewall blocks traffic according to defined security rules. | Firewall rules may not address every threat or configuration weakness. | Review firewall rules periodically and validate their effectiveness. |
| CTRL-06 | Intrusion detection system | Missing | No intrusion detection system is installed. | Malicious or unusual network activity may go undetected. | Assess and implement suitable intrusion detection and monitoring capabilities. |
| CTRL-07 | Backups | Missing | Critical data is not backed up. | Data loss and extended recovery time after an incident. | Implement regular, protected backups and test restoration. |
| CTRL-08 | Antivirus software | Implemented | Antivirus software is installed and monitored regularly by the IT department. | Existing antivirus coverage may not detect every threat. | Maintain updates, review alerts, and evaluate whether additional endpoint detection capabilities are required. |
| CTRL-09 | Legacy system monitoring and maintenance | Partially established | Legacy systems are monitored and maintained, but there is no regular schedule and intervention methods are unclear. | Unaddressed vulnerabilities, inconsistent maintenance, and increased exposure to system failures. | Establish a documented maintenance schedule, assign responsibility, and define escalation procedures. |
| CTRL-10 | Encryption | Missing | Customer credit card information is not encrypted, according to the source report. | Unauthorised disclosure of payment information. | Assess and implement appropriate encryption for sensitive data in transit and at rest, as applicable. |
| CTRL-11 | Password management system | Missing | No centralised password management system is available. | Inconsistent password practices and additional account management workload. | Implement a suitable password management solution and strengthen account recovery procedures. |

## 5. Physical and Operational Controls

| Control ID | Control | Status | Source-Based Finding | Business Risk | Recommended Action |
|---|---|---|---|---|---|
| CTRL-12 | Physical locks | Implemented | The premises have sufficient locks. | Physical access risks may remain if access permissions are not reviewed. | Maintain locks and review physical access arrangements periodically. |
| CTRL-13 | CCTV surveillance | Implemented | Up-to-date CCTV surveillance is available. | Incidents may still occur or remain unresolved if footage is unavailable or not reviewed when needed. | Maintain cameras, protect recordings, and define appropriate review and retention procedures. |
| CTRL-14 | Fire detection and prevention | Implemented | Functioning fire detection and prevention systems are in place. | Equipment and inventory may still be affected by fire or other environmental incidents. | Maintain the systems and conduct appropriate inspections and tests. |

## 6. Key Findings

### Finding F-01: Excessive Access to Internal Data

**Related controls:** CTRL-01 and CTRL-04

The case states that all employees have access to internally stored data and that separation of duties has not been implemented.

**Potential impact:**

- Unauthorised access to customer personal information.
- Increased exposure if an employee account is compromised.
- Greater opportunity for inappropriate or unauthorised changes.
- Difficulty limiting the impact of insider misuse.

**Recommendation:**

Introduce role-based access controls, least privilege, periodic access reviews, and separation of conflicting responsibilities. Sensitive activities should have clearly defined approval and monitoring requirements.

### Finding F-02: Inadequate Protection of Payment Information

**Related controls:** CTRL-10 and CTRL-11

The case states that customer credit card information is not encrypted and that centralised password management is absent.

**Potential impact:**

- Exposure of payment information.
- Increased risk from compromised accounts.
- Potential payment security and compliance consequences.

**Recommendation:**

Review the complete payment data flow, identify where cardholder data is stored or transmitted, restrict access, and implement appropriate encryption and access safeguards. Evaluate the applicable PCI DSS requirements.

### Finding F-03: Weak Recovery Capabilities

**Related controls:** CTRL-02 and CTRL-07

The case states that there are no disaster recovery plans and no backups of critical data.

**Potential impact:**

- Loss of business records.
- Extended interruption to sales and internal operations.
- Difficulty restoring systems after a cyberattack or other incident.
- Potential financial and reputational damage.

**Recommendation:**

Identify critical systems, establish backup requirements, protect backup copies from unauthorised modification, and test restoration. Develop recovery procedures with approved recovery time and recovery point objectives.

### Finding F-04: Limited Detection Capabilities

**Related control:** CTRL-06

The case states that an intrusion detection system has not been installed.

**Potential impact:**

- Delayed identification of malicious network activity.
- Longer periods of undetected compromise.
- Greater potential impact from security incidents.

**Recommendation:**

Assess the organisation's monitoring needs, implement suitable detection capabilities, define alert-handling procedures, and assign responsibility for investigating security events.

### Finding F-05: Inconsistent Legacy System Maintenance

**Related control:** CTRL-09

The case confirms that legacy systems are monitored and maintained but that there is no regular schedule and intervention methods are unclear.

**Potential impact:**

- Delayed security updates.
- Unclear accountability for maintenance.
- Increased likelihood of unresolved technical weaknesses.

**Recommendation:**

Create an inventory of legacy systems, document their support status, establish maintenance schedules, and define procedures for patching, exception approval, escalation, and replacement planning.

### Finding F-06: Inadequate Password Controls

**Related controls:** CTRL-03 and CTRL-11

The case identifies weak password policy requirements and the absence of a centralised password management system.

**Potential impact:**

- Greater exposure to account compromise.
- Inconsistent password practices.
- Increased operational workload for password recovery.

**Recommendation:**

Adopt current authentication guidance, use multifactor authentication where appropriate, establish secure account recovery, and implement centralised identity and password management.

## 7. Existing Controls and Positive Findings

The assessment also recognises safeguards that the case describes as present.

### Firewall

The company has a firewall with defined security rules. This provides a baseline layer of network protection. Rule reviews and validation are still recommended.

### Antivirus Software

Antivirus software is installed and monitored regularly. The organisation should maintain updates and assess whether its endpoint protection is sufficient for its threat environment.

### Data Integrity and Availability

The source report states that the IT department has established controls to support data integrity and availability.

However, the effectiveness of these controls has not been independently verified. The absence of backups and disaster recovery planning remains a significant recovery concern.

### Physical Security

The case describes sufficient locks, up-to-date CCTV, and functioning fire detection and prevention systems.

These controls support physical security and asset protection. Ongoing maintenance and periodic review remain necessary.

## 8. Overall Assessment

The source material identifies several important control gaps affecting access management, payment data protection, threat detection, and recovery.

The most urgent improvements should address excessive access to sensitive information, inadequate protection of payment card data, and the absence of critical-data backups and disaster recovery planning.

The presence of a firewall, antivirus software, and physical safeguards provides a useful starting point. However, these controls do not eliminate risks arising from missing or inadequate safeguards elsewhere.

The assessment supports a risk-based remediation programme with clear ownership, implementation milestones, and evidence of effectiveness.

## 9. Assessment Limitations

This assessment is based on the fictional Botium Toys case study.

No live systems were tested, and no technical configurations, security logs, or independent control evidence were examined. The findings describe the conditions reported in the case rather than independently verified security weaknesses.

Recommendations are proposed improvements and do not constitute proof of compliance with any regulation or security standard.

## 10. Source Reference

Source: Botium Toys Scope, Goals, and Risk Assessment Report and Controls and Compliance Checklist, supplied as part of the learning activity.
