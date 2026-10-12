# 07. NIST Cybersecurity Framework 2.0 Mapping

## 1. Purpose

This document maps the cybersecurity findings from the Botium Toys assessment to the NIST Cybersecurity Framework (CSF) 2.0.

The objective is to organise the identified weaknesses into recognised cybersecurity risk management areas and recommend practical actions for improvement.

The mapping is based on the supplied fictional case study, the asset inventory, the controls assessment, and the risk register developed for this portfolio.

This document is an analytical mapping exercise. It is not a formal NIST assessment, certification, or statement of compliance.

## 2. Framework Overview

NIST CSF 2.0 provides a structure for organisations to understand, assess, prioritise, and communicate cybersecurity risks.

The framework contains six core functions:

| Function | Purpose | Application to Botium Toys |
|---|---|---|
| Govern | Establish cybersecurity strategy, responsibilities, policies, and oversight. | Define security ownership, accountability, and risk management priorities. |
| Identify | Understand assets, risks, and business dependencies. | Improve asset inventory, data classification, and risk assessment. |
| Protect | Implement safeguards to manage cybersecurity risk. | Improve access management, authentication, and sensitive data protection. |
| Detect | Identify possible cybersecurity attacks and other adverse events. | Improve monitoring and detection capabilities. |
| Respond | Take action when a cybersecurity incident occurs. | Define incident handling, escalation, and communication procedures. |
| Recover | Restore systems and services affected by an incident. | Establish backups, recovery plans, and recovery testing. |

## 3. Assessment Method

Each finding is mapped to the relevant NIST CSF function and selected outcome areas.

The mapping uses three principles:

1. Connect documented weaknesses to relevant cybersecurity outcomes.
2. Recommend actions that address the underlying weakness.
3. Identify evidence that would help demonstrate improvement.

A mapped outcome does not automatically mean that the organisation has failed a formal NIST requirement. The framework is used here to organise the assessment and guide improvement.

## 4. Govern Function

### Objective

Establish the responsibilities, policies, risk decisions, and oversight needed to manage cybersecurity effectively.

### Relevant Findings

The case identifies inadequate asset management, missing access controls, weak password requirements, and unclear legacy system maintenance procedures.

These conditions indicate a need for stronger accountability and documented security processes.

| Finding ID | Observation | Recommended Action | Validation Evidence |
|---|---|---|---|
| GOV-01 | Security responsibilities are not fully established in the available documentation. | Assign owners for security controls, assets, risks, and remediation actions. | Approved responsibility matrix and assigned risk owners. |
| GOV-02 | Asset management is inadequate. | Establish an asset management policy and review process. | Approved policy and maintained asset inventory. |
| GOV-03 | Legacy system maintenance procedures are unclear. | Define maintenance responsibilities, escalation procedures, and exception approvals. | Approved procedures and maintenance records. |
| GOV-04 | Risk management needs a structured approach. | Establish a risk register, review process, and management escalation criteria. | Reviewed risk register and documented management decisions. |

### Expected Outcome

Management has clear responsibility for cybersecurity risks, control implementation, and remediation progress.

## 5. Identify Function

### Objective

Understand the assets, data, threats, vulnerabilities, and business dependencies that influence cybersecurity risk.

### Relevant Findings

The original report states that asset management is inadequate and that the IT department does not know which assets would be at risk if an asset were lost.

### Recommended Actions

| Finding ID | Observation | Recommended Action | Validation Evidence |
|---|---|---|---|
| ID-01 | Asset inventory and classification are inadequate. | Create and maintain an inventory of hardware, software, systems, and information assets. | Reviewed asset register with owners and classification. |
| ID-02 | Customer personal and payment information requires stronger protection. | Identify where sensitive data is collected, processed, transmitted, and stored. | Data inventory and documented data flows. |
| ID-03 | The criticality of business assets is not fully established. | Conduct a business impact analysis for essential business processes. | Approved criticality ratings and business impact analysis. |
| ID-04 | Legacy systems require manual monitoring and maintenance. | Document legacy system ownership, dependencies, support status, and known risks. | Legacy system inventory and maintenance records. |
| ID-05 | The current risk assessment lacks detailed asset-level risk information. | Maintain a risk register linked to affected assets and business processes. | Risk register with traceable findings and owners. |

### Expected Outcome

The company understands its important assets, the information they handle, and the business consequences of losing or compromising them.

## 6. Protect Function

### Objective

Implement safeguards that reduce the likelihood and impact of cybersecurity incidents.

### Relevant Findings

The source case identifies excessive employee access, missing separation of duties, inadequate password requirements, missing encryption, and the absence of a centralised password management system.

### Recommended Actions

| Finding ID | Observation | Recommended Action | Validation Evidence |
|---|---|---|---|
| PR-01 | Least privilege is not implemented. | Introduce role-based access and restrict permissions according to business need. | Approved access matrix and access review records. |
| PR-02 | Separation of duties is not implemented. | Separate conflicting responsibilities and introduce independent approvals where appropriate. | Documented role assignments and approval records. |
| PR-03 | Password policy requirements are inadequate. | Establish appropriate authentication requirements and secure account recovery procedures. | Approved authentication policy and configuration review. |
| PR-04 | Centralised password management is absent. | Implement suitable identity and password management capabilities. | System configuration and access management evidence. |
| PR-05 | Customer credit card information is not encrypted. | Review data flows and implement appropriate protection for stored and transmitted sensitive data. | Approved architecture, configuration records, and encryption validation. |
| PR-06 | Critical data backups are absent. | Implement protected backups and validate restoration procedures. | Backup logs and successful restoration test results. |
| PR-07 | A firewall and antivirus software exist, but their effectiveness has not been independently tested. | Review configurations, updates, coverage, and operating procedures. | Documented control review and remediation records. |

### Expected Outcome

Access to sensitive information is restricted, security safeguards are implemented consistently, and important business data receives appropriate protection.

## 7. Detect Function

### Objective

Identify cybersecurity events and possible attacks in a timely manner.

### Relevant Findings

The case states that an intrusion detection system has not been installed. Antivirus software is present and monitored regularly, and a firewall is in place.

### Recommended Actions

| Finding ID | Observation | Recommended Action | Validation Evidence |
|---|---|---|---|
| DET-01 | No intrusion detection system is installed. | Assess and implement suitable network or host-based detection capabilities. | Approved detection architecture and test results. |
| DET-02 | The complete monitoring capability has not been independently assessed. | Review available logs, monitoring coverage, and alert handling. | Monitoring coverage assessment and documented alert procedures. |
| DET-03 | Legacy systems lack a regular maintenance schedule. | Establish scheduled checks and monitoring procedures for legacy systems. | Maintenance logs and documented escalation records. |
| DET-04 | Security control effectiveness is not independently verified. | Conduct authorised control validation and assess detection coverage. | Approved test plan and documented findings. |

### Expected Outcome

Suspicious activity can be identified, investigated, and escalated through a documented process.

## 8. Respond Function

### Objective

Manage cybersecurity incidents through defined response, analysis, containment, communication, and improvement activities.

### Relevant Findings

The source case describes a plan to notify EU customers within 72 hours if a security breach occurs. However, the available information does not establish whether a complete incident response process has been documented and tested.

### Recommended Actions

| Finding ID | Observation | Recommended Action | Validation Evidence |
|---|---|---|---|
| RES-01 | The effectiveness of incident response procedures has not been verified. | Develop or review an incident response plan covering identification, escalation, containment, and recovery coordination. | Approved incident response plan. |
| RES-02 | The case describes a breach notification plan, but its complete regulatory alignment is not verified. | Define incident classification, legal escalation
