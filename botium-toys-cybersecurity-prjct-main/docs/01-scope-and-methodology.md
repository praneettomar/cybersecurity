# 01. Scope and Methodology

## 1. Document Purpose

This document defines the scope, objectives, assessment approach, and limitations of the Botium Toys Cybersecurity Internal Audit and Risk Assessment.

The purpose is to establish a clear and consistent approach for reviewing the company's documented security controls, identifying risks, evaluating relevant compliance practices, and recommending improvements.

This assessment is based on a fictional business scenario and the supporting case materials.

## 2. Business Background

Botium Toys is a fictional United States-based company that develops and sells toys. It operates from a single physical location that serves as its main office, retail storefront, and warehouse.

The company also sells products online and serves customers in the United States and internationally.

According to the original risk assessment report, the company has an overall risk score of 8 out of 10. The report identifies weaknesses in asset management, access controls, encryption, intrusion detection, backups, disaster recovery, password management, and legacy system maintenance.

These weaknesses may affect customer information, payment data, business operations, and the company's ability to recover from a security incident.

## 3. Assessment Objectives

The objectives of this assessment are:

1. Review the assets and business processes identified in the case materials.
2. Assess the documented administrative, technical, and physical security controls.
3. Identify gaps in confidentiality, integrity, and availability.
4. Evaluate cybersecurity risks and their potential business impact.
5. Review relevant privacy, payment security, and assurance requirements.
6. Map selected findings to recognised cybersecurity frameworks.
7. Prioritise corrective actions according to risk.
8. Recommend practical improvements and measurable validation criteria.

## 4. Assessment Scope

### 4.1 Business Scope

The assessment covers the following business operations described in the case:

- Main office operations.
- Physical retail storefront.
- Warehouse and product storage.
- Online sales and e-commerce operations.
- Internal business and IT operations.
- Processing, storage, and handling of customer information and payment card data, as described in the case.

### 4.2 Technical Scope

The original case identifies the following assets and technology areas:

- On-premises equipment.
- Employee desktops, laptops, smartphones, and remote workstations.
- Supporting employee equipment and peripherals.
- Accounting systems.
- Telecommunications systems.
- Databases.
- Security systems and software.
- E-commerce systems.
- Inventory management systems.
- Internet access and internal networks.
- Data retention and storage.
- Legacy systems requiring manual monitoring and maintenance.
- Storefront products and warehouse inventory.
- Physical security systems, including CCTV and fire detection.

The assessment reviews the documented controls associated with these assets. It does not assume that every technical component has been independently inspected or tested.

### 4.3 Security Control Scope

The following controls are included in the assessment:

- Least privilege.
- Separation of duties.
- Password policies.
- Password management.
- Firewall protection.
- Intrusion detection.
- Antivirus software.
- Encryption.
- Data backups.
- Disaster recovery planning.
- Legacy system monitoring and maintenance.
- Physical locks.
- CCTV surveillance.
- Fire detection and prevention.

The assessment distinguishes between controls that are present, absent, and present but potentially inadequate.

### 4.4 Governance and Compliance Scope

The assessment reviews the following areas:

**NIST Cybersecurity Framework (CSF):** A reference for organising cybersecurity risk management activities.

**CIA triad:** A model for assessing confidentiality, integrity, and availability risks.

**General Data Protection Regulation (GDPR):** Relevant privacy requirements will be evaluated where the regulation applies to the company's processing of personal data.

**Payment Card Industry Data Security Standard (PCI DSS):** Relevant payment card security requirements will be considered because the case describes the handling of customer credit card information.

**SOC 2 Trust Services Criteria:** Selected criteria will be used as a reference for assessing security, availability, confidentiality, processing integrity, and privacy controls.

This is a preliminary review of relevant requirements and control practices. It is not a legal opinion, a formal compliance audit, or an independent certification assessment.

## 5. Assessment Methodology

The assessment follows a structured, risk-based approach.

### Phase 1: Review Available Information

Review the supplied scope, goals, and risk assessment report, control categories document, and controls and compliance checklist.

Record the security conditions explicitly described in the source materials.

### Phase 2: Identify and Classify Assets

Identify the business assets, information, systems, and physical resources described in the case.

Assess their business importance and the potential consequences of loss, unauthorized access, unauthorized modification, or service disruption.

Where the business impact or asset criticality is not documented, record the information as an assumption or an item requiring further investigation.

### Phase 3: Assess Existing Controls

Review each security control against the information available in the case.

Classify findings using the following approach:

- **Implemented:** The case explicitly confirms that the control exists.
- **Missing:** The case explicitly states that the control does not exist.
- **Needs improvement:** The control exists, but its implementation is described as inadequate.
- **Not verified:** The available information does not establish whether the control exists or operates effectively.

A control being present does not automatically mean that it is effective.

### Phase 4: Identify and Evaluate Risks

Describe each identified risk in terms of the affected asset, security weakness, potential threat, and possible business impact.

Use a consistent likelihood and impact methodology to develop proposed risk ratings.

Separate the original overall risk score supplied by the case from any additional risk ratings developed for this portfolio project.

### Phase 5: Review Frameworks and Compliance

Map relevant findings to selected NIST CSF outcomes and assess their relationship to the CIA triad.

Review applicable GDPR obligations, PCI DSS requirements, and selected SOC 2 Trust Services Criteria.

Record whether each requirement is applicable, potentially applicable, or requires further validation.

Do not claim legal or regulatory non-compliance solely because a security weakness exists.

### Phase 6: Develop Recommendations

Recommend corrective actions based on risk, business impact, and implementation needs.

For each significant recommendation, identify a proposed owner, target priority, completion measure, and evidence needed to verify the improvement.

### Phase 7: Prepare Management Reporting

Summarise the most important findings, explain their business impact, and present a prioritised remediation roadmap.

The objective is to help management understand which actions require attention first and how progress should be measured.

## 6. Risk Assessment Principles

The assessment uses the following principles:

### Confidentiality

Assess whether sensitive information is protected against unauthorised access or disclosure.

### Integrity

Assess whether information and systems are protected against unauthorised or improper modification.

### Availability

Assess whether authorised users can access information and systems when needed.

### Least Privilege

Recommend granting users only the access required to perform their responsibilities.

### Defence in Depth

Recommend multiple complementary safeguards rather than relying on a single security control.

### Risk-Based Prioritisation

Prioritise actions according to the severity of the identified risk, potential business impact, and the urgency of treatment.

### Evidence-Based Assessment

Distinguish documented facts from assumptions, analytical judgements, and items requiring further investigation.

## 7. Evidence and Documentation Standards

Each significant finding should include:

- A unique finding or risk identifier.
- A description of the observed condition.
- A reference to the supplied case information.
- The affected asset or business process.
- The potential security and business impact.
- The relevant control or framework reference.
- A recommended corrective action.
- The proposed priority and responsible role.
- A method for validating remediation.

Because this is a fictional case study, the available evidence consists primarily of the supplied learning materials. No independent technical evidence has been collected.

## 8. Assessment Limitations

This assessment has the following limitations:

1. The organisation is fictional.
2. The assessment is based on the supplied case documentation.
3. No live infrastructure, applications, endpoints, or networks have been accessed.
4. No vulnerability scans or penetration tests have been conducted.
5. No technical configuration, source code, security logs, or forensic evidence has been independently reviewed.
6. The effectiveness of documented controls has not been independently tested.
7. The exact applicability of legal and regulatory requirements requires additional business and legal information.
8. Additional risk ratings and remediation priorities represent analytical recommendations rather than independently verified findings.

## 9. Expected Deliverables

The assessment will produce:

- An asset inventory.
- A security controls assessment.
- A documented risk scoring methodology.
- A prioritised risk register.
- A compliance gap assessment.
- A NIST CSF mapping.
- A remediation roadmap.
- An executive summary.
- A record of assumptions and limitations.

## 10. Success Criteria

The project will be considered complete when:

- All controls listed in the supplied checklist have been assessed.
- Identified risks are documented and prioritised consistently.
- Relevant framework and compliance references are mapped transparently.
- Recommendations address the major identified weaknesses.
- Proposed actions include measurable completion criteria.
- Findings can be traced to source information or clearly labelled analysis.
- The final documentation communicates risks and recommendations in language that business stakeholders can understand.

## 11. Source Acknowledgment

The business background, initial control conditions, and original overall risk score are based on the supplied Botium Toys Scope, Goals, and Risk Assessment Report and its supporting learning materials.

The assessment methodology, additional risk analysis, framework mappings, and remediation recommendations are developed for this portfolio project.
