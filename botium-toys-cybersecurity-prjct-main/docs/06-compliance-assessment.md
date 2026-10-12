# 06. Compliance Assessment

## 1. Purpose

This document reviews the compliance implications of the security weaknesses identified in the Botium Toys case study.

The assessment focuses on three areas:

- General Data Protection Regulation (GDPR).
- Payment Card Industry Data Security Standard (PCI DSS).
- SOC 2 Trust Services Criteria.

The objective is to identify potential compliance gaps, explain their business implications, and recommend corrective actions.

This is a preliminary gap assessment based on the supplied case information. It is not a legal opinion, formal compliance audit, or certification assessment.

## 2. Assessment Approach

Each compliance area is evaluated using the following statuses:

- **Gap identified:** The case describes a condition that conflicts with the control practice being assessed.
- **Potential gap:** The available information suggests a concern, but further investigation is required.
- **Documented practice:** The case describes a relevant process or control as established.
- **Not verified:** The available information is insufficient to determine whether the requirement is satisfied.

These statuses describe the evidence available for this project. They do not establish a formal legal or regulatory conclusion.

## 3. GDPR Assessment

### 3.1 Overview

The General Data Protection Regulation establishes requirements for the processing and protection of personal data within its scope.

The original case states that Botium Toys serves customers in the European Union and has established a plan to notify EU customers within 72 hours of a security breach.

However, the applicability of GDPR must be determined from the actual processing activities and territorial scope. Serving customers in another country does not, by itself, establish every GDPR obligation.

### 3.2 Assessment Findings

| ID | Assessment Area | Case Evidence | Status | Recommended Action |
|---|---|---|---|---|
| GDPR-01 | Protection of personal data | All employees have access to internally stored data, which may include customer personal information. | Gap identified | Restrict access according to job responsibilities and implement access reviews. |
| GDPR-02 | Data classification and inventory | Asset management is inadequate, and the company does not know which assets would be at risk. | Gap identified | Inventory personal data, document processing activities, and classify information according to sensitivity. |
| GDPR-03 | Security of processing | Payment information is not encrypted, and access restrictions are inadequate. | Potential gap | Assess appropriate technical and organisational safeguards for personal data, including encryption where appropriate. |
| GDPR-04 | Personal data breach notification | The case states that a plan exists to notify EU customers within 72 hours. | Documented practice; effectiveness not verified | Confirm that incident procedures distinguish regulatory notification to the supervisory authority from communication to affected individuals. |
| GDPR-05 | Privacy policies and procedures | Privacy policies and procedures are documented and enforced according to the case. | Documented practice; effectiveness not verified | Review the policies, training records, responsibilities, and implementation evidence. |

### 3.3 Important GDPR Considerations

**Personal data protection**

The company should identify the personal data it collects, the purposes for which it is processed, where it is stored, who can access it, and how long it is retained.

**Access restrictions**

Access should be limited to authorised individuals who require the information for legitimate business purposes.

**Security measures**

The organisation should assess the appropriate technical and organisational measures needed to protect personal data, considering the risks associated with its processing.

**Breach notification**

The GDPR generally requires a controller to notify the relevant supervisory authority of a personal data breach without undue delay and, where feasible, within 72 hours after becoming aware of it, unless an applicable exception applies.

Communication to affected individuals is a separate obligation that depends on the conditions set out in the regulation. A plan to notify customers within 
