# 08. Cybersecurity Remediation Roadmap

## 1. Purpose

This document presents a proposed remediation roadmap for the cybersecurity weaknesses identified in the Botium Toys assessment.

The roadmap translates the assessment findings into practical actions with proposed priorities, responsible roles, timelines, dependencies, and measures of success.

The objective is to reduce cybersecurity risk, improve protection of sensitive information, strengthen business continuity, and establish a process for monitoring security improvements.

All timelines and responsibilities in this document are proposed for this portfolio exercise. They have not been approved by Botium Toys management.

## 2. Remediation Principles

The remediation programme follows five principles:

1. Address the most significant risks first.
2. Prioritise protection of sensitive information and critical business operations.
3. Establish basic governance and ownership for every action.
4. Validate that implemented controls work as intended.
5. Track progress through measurable results and documented evidence.

Remediation priorities should be reviewed when new evidence, business requirements, or significant changes become available.

## 3. Proposed Implementation Phases

The roadmap uses four implementation phases.

| Phase | Proposed Timeline | Main Objective |
|---|---|---|
| Phase 1 | Days 0–30 | Address urgent security gaps and establish ownership. |
| Phase 2 | Days 31–60 | Implement key access, data protection, and monitoring improvements. |
| Phase 3 | Days 61–90 | Strengthen recovery, incident response, and operational procedures. |
| Phase 4 | Days 91–180 | Validate controls, improve governance, and establish ongoing monitoring. |

These timelines are planning estimates. Actual delivery dates depend on resources, technical dependencies, procurement, and management approval.

## 4. Phase 1: Immediate Risk Reduction

### Objective

Address the most important identified weaknesses and establish ownership of the remediation programme.

| Action ID | Recommended Action | Proposed Owner | Target | Success Measure |
|---|---|---|---|---|
| ACT-01 | Identify users with access to customer personal and payment information. | IT Manager | Days 0–10 | Sensitive-data access list reviewed and approved. |
| ACT-02 | Restrict unnecessary access to sensitive information. | IT Manager and System Owners | Days 0–30 | Access changes completed and validated against approved permissions. |
| ACT-03 | Review where payment card information is stored, processed, and transmitted. | Payment System Owner | Days 0–15 | Payment data flow documented and reviewed. |
| ACT-04 | Assess appropriate safeguards for payment data and define the remediation plan. | Security Lead and Payment System Owner | Days 10–30 | Documented gap analysis and approved action plan. |
| ACT-05 | Identify critical business data and systems that require backup and recovery. | IT Operations Lead | Days 0–15 | Critical asset and recovery requirements list approved. |
| ACT-06 | Assign an owner and target date to every high-priority risk. | IT Manager | Days 0–15 | Risk register contains an owner and treatment decision for every high-priority item. |
| ACT-07 | Establish a baseline asset inventory. | IT Manager and Asset Owners | Days 0–30 | Initial inventory records identified in-scope assets and their owners. |

### Expected Outcome

Management understands the highest-priority risks, access to sensitive information is being addressed, and critical recovery requirements have been identified.

## 5. Phase 2: Core Security Improvements

### Objective

Strengthen access management, authentication, payment data protection, and threat detection.

| Action ID | Recommended Action | Proposed Owner | Target | Success Measure |
|---|---|---|---|---|
| ACT-08 | Implement role-based access and least privilege. | IT Manager | Days 31–60 | In-scope systems have approved roles and permissions. |
| ACT-09 | Establish separation of duties for sensitive activities. | IT Manager and Business Owners | Days 31–60 | Conflicting responsibilities are identified and addressed or formally managed. |
| ACT-10 | Strengthen password and authentication practices. | Identity and Access Administrator | Days 31–60 | Approved authentication policy is implemented and validated. |
| ACT-11 | Implement appropriate centralised identity and password management capabilities. | IT Manager | Days 31–60 | Selected systems use approved account management processes. |
| ACT-12 | Implement appropriate protection for sensitive payment data. | Payment System Owner and Security Lead | Days 31–60 | Approved safeguards are implemented and their operation is validated. |
| ACT-13 | Assess and implement suitable intrusion detection and security monitoring. | Security Lead | Days 31–60 | Critical systems have defined monitoring coverage and alert handling procedures. |
| ACT-14 | Review firewall rules and endpoint protection coverage. | Network Administrator and IT Operations Lead | Days 31–60 | Reviews are documented and required changes are completed or tracked. |

### Expected Outcome

Access is better controlled, sensitive information receives appropriate protection, and the company has improved visibility into potential security events.

## 6. Phase 3: Recovery and Incident Readiness

### Objective

Improve the company's ability to recover from incidents and respond in a coordinated manner.

| Action ID | Recommended Action | Proposed Owner | Target | Success Measure |
|---|---|---|---|---|
| ACT-15 | Implement protected backups of critical business data. | IT Operations Lead | Days 31–75 | Critical systems are covered by approved backup procedures. |
| ACT-16 | Test data restoration from backups. | IT Operations Lead | Days 61–90 | Restoration tests are completed and results are documented. |
| ACT-17 | Develop and approve a disaster recovery plan. | IT Manager and Business Owners | Days 61–90 | Recovery plan is approved and identifies critical systems, roles, and procedures. |
| ACT-18 | Define recovery time objectives and recovery point objectives. | Business Owners and IT Operations Lead | Days 31–75 | Recovery objectives are approved for critical business services. |
| ACT-19 | Review or develop the incident response plan. | Security Lead | Days 61–90 | Plan documents incident classification, escalation, containment, communication, and recovery coordination. |
| ACT-20 | Review breach notification decision-making and responsibilities. | Privacy Lead and Legal Adviser | Days 61–90 | Documented procedures identify applicable notification requirements and decision owners. |
| ACT-21 | Establish scheduled legacy system maintenance. | IT Operations Lead | Days 61–90 | Legacy systems have documented owners, maintenance schedules, and escalation procedures. |

### Expected Outcome

The company has a defined approach to recovering critical information and services, and its response responsibilities are documented.

## 7. Phase 4: Validation and Continuous Improvement

### Objective

Confirm that improvements work as intended and establish ongoing control monitoring.

| Action ID | Recommended Action | Proposed Owner | Target | Success Measure |
|---|---|---|---|---|
| ACT-22 | Conduct access reviews. | System Owners | Days 91–120 | Reviews are completed for all systems included in the approved review scope. |
| ACT-23 | Test incident response procedures through a tabletop exercise. | Security Lead | Days 91–120 | Exercise results and corrective actions are documented. |
| ACT-24 | Test disaster recovery procedures. | IT Operations Lead | Days 91–150 | Recovery tests are completed and gaps are tracked. |
| ACT-25 | Review compliance requirements and supporting evidence. | Privacy Lead, Security Lead, and Legal Adviser | Days 91–150 | Applicable requirements, gaps, owners, and evidence needs are documented. |
| ACT-26 | Review the risk register and update risk ratings. | IT Manager and Risk Owners | Days 91–120 | Ratings reflect updated evidence and approved methodology. |
| ACT-27 | Establish a management reporting process. | IT Manager | Days 91–180 | Management receives a documented report on risks, remediation, and outstanding actions. |
| ACT-28 | Establish periodic security control reviews. | Security Lead | Days 91–180 | Review schedule, responsibilities, and evidence requirements are approved. |

### Expected Outcome

Security improvements are supported by validation evidence, management oversight, and a repeatable process for identifying new risks.

## 8. Dependencies and Delivery Considerations

Some actions depend on earlier activities.

### Asset Inventory Before Detailed Risk Prioritisation

The company needs to identify its important systems and information before it can assign reliable asset criticality and recovery requirements.

### Payment Data Mapping Before Selecting Safeguards

The organisation should understand where payment data flows before deciding which systems and controls require changes.

### Recovery Objectives Before Finalising Recovery Plans

Business owners should establish acceptable recovery times and data loss limits before the recovery strategy is approved.

### Access Design Before Broad Access Changes

Access roles should be
