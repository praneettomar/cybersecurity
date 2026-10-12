# 02. Asset Inventory and Classification

## 1. Purpose

This document identifies the business assets described in the Botium Toys case and explains why they matter from a cybersecurity perspective.

An asset inventory helps an organisation understand what it needs to protect, which business activities depend on each asset, and what could happen if an asset is compromised, unavailable, lost, or accessed without authorisation.

This inventory is based on the supplied case materials. Asset owners, detailed configurations, data volumes, and exact criticality ratings have not been independently verified.

## 2. Asset Inventory

| Asset ID | Asset or Asset Group | Business Purpose | Potential Security Concern |
|---|---|---|---|
| AST-01 | On-premises equipment | Supports office and business operations | Equipment compromise, unauthorised access, service disruption |
| AST-02 | Employee endpoints | Supports employee work through desktops, laptops, smartphones, and remote workstations | Malware, stolen devices, unauthorised access, data exposure |
| AST-03 | Accounting systems | Supports financial and accounting activities | Financial data exposure, unauthorised changes, service disruption |
| AST-04 | Telecommunications systems | Supports business communications | Communication disruption, unauthorised access |
| AST-05 | Databases | Stores and manages business information | Data exposure, unauthorised modification, data loss |
| AST-06 | Security systems and software | Supports security operations | Detection gaps, security configuration weaknesses |
| AST-07 | E-commerce systems | Supports online sales and customer transactions | Customer data exposure, transaction disruption, payment security risks |
| AST-08 | Inventory management systems | Supports inventory tracking and warehouse operations | Incorrect inventory records, operational disruption |
| AST-09 | Internet access | Enables online services and external connectivity | Connectivity disruption, exposure to external threats |
| AST-10 | Internal network | Connects internal systems and devices | Unauthorised network access, malware spread, service disruption |
| AST-11 | Data retention and storage | Maintains business records and stored information | Data loss, unauthorised disclosure, retention issues |
| AST-12 | Legacy systems | Supports systems requiring manual monitoring and maintenance | Unpatched vulnerabilities, unsupported software, unclear maintenance procedures |
| AST-13 | Customer personal information | Supports customer-related business activities | Unauthorised disclosure, misuse, privacy harm |
| AST-14 | Customer payment card information | Supports payment processing and related transactions | Payment data exposure, fraud, financial and regulatory consequences |
| AST-15 | Physical product inventory | Supports retail sales and warehouse operations | Theft, physical damage, inventory loss |
| AST-16 | Office, storefront, and warehouse premises | Supports business operations and physical asset storage | Unauthorised physical access, theft, environmental damage |
| AST-17 | CCTV and physical security systems | Supports physical security and surveillance | Loss of monitoring capability, unauthorised access to recordings |
| AST-18 | Fire detection and prevention systems | Helps protect people, equipment, and inventory from fire | Failure to detect or limit fire-related damage |
| AST-19 | Backups and recovery capability | Supports restoration of business information after an incident | Inability to recover data or resume operations |
| AST-20 | Identity and password management | Controls access to systems and information | Account compromise, unauthorised access, password-related incidents |

## 3. Asset Classification

For this portfolio assessment, assets are classified according to their business function and the type of protection they may require.

| Classification | Meaning | Examples |
|---|---|---|
| Business-critical systems | Systems whose failure could significantly disrupt business operations | E-commerce, accounting, inventory management |
| Sensitive information | Information requiring protection against unauthorised disclosure or modification | Customer personal information, payment card information |
| Infrastructure | Technology that supports connectivity and business systems | Internal network, internet access, on-premises equipment |
| End-user assets | Devices used by employees to perform business activities | Laptops, desktops, smartphones |
| Physical assets | Premises, equipment, and inventory requiring physical protection | Warehouse inventory, office equipment |
| Security and recovery assets | Systems and capabilities that support protection, detection, and recovery | Firewall, antivirus, CCTV, backups, disaster recovery capability |

These classifications are preliminary. The company would need a formal classification policy, business impact analysis, and confirmation from asset owners to establish final classifications.

## 4. CIA Triad Assessment

The CIA triad provides a basic method for considering the security needs of each asset.

### Confidentiality

Confidentiality means that information is available only to authorised people and systems.

Assets requiring particular attention include customer personal information, payment card information, databases, employee devices, and accounting systems.

The original case identifies excessive employee access and a lack of encryption for customer credit card information.

### Integrity

Integrity means that information remains accurate, complete, and protected against unauthorised changes.

Relevant assets include accounting systems, databases, inventory management systems, and e-commerce transaction records.

The source report states that data integrity controls are in place. Their effectiveness has not been independently tested.

### Availability

Availability means that systems and information remain accessible to authorised users when required.

Relevant assets include e-commerce systems, databases, internal networks, accounting systems, and inventory management systems.

The source report states that availability controls exist. However, it also states that there are no disaster recovery plans and no backups of critical data. This creates a potential recovery risk.

## 5. Preliminary Asset Criticality

The following ratings are proposed for this portfolio exercise. They are not ratings supplied by the original case.

| Asset Group | Proposed Criticality | Reason |
|---|---|---|
| Customer payment card information | Critical | Exposure could affect customers, payment security, and regulatory obligations |
| Customer personal information | High | Exposure could cause privacy harm and legal consequences |
| E-commerce systems | Critical | Disruption could affect online sales and customer transactions |
| Databases and data storage | Critical | Loss or compromise could affect multiple business functions |
| Accounting systems | High | Disruption or unauthorised changes could affect financial operations |
| Inventory management | High | Incorrect records or outages could disrupt retail and warehouse operations |
| Internal network and internet connectivity | High | Disruption could affect multiple dependent systems |
| Employee endpoints | High | Compromised devices could provide access to business systems and information |
| Legacy systems | High | Weak maintenance processes may increase exposure to vulnerabilities |
| Physical inventory and premises | Medium to High | Theft or damage could affect operations and financial performance |
| CCTV and fire protection | Medium to High | Failure could weaken physical security and damage prevention |

Final criticality ratings should be confirmed through business impact analysis and discussions with the relevant business and IT owners.

## 6. Asset Management Gaps

The original case identifies inadequate asset management and states that the IT department does not know which assets would be at risk if an asset were lost.

The following items should therefore be investigated:

- Whether a complete and current asset register exists.
- Who owns each asset and who is responsible for securing it.
- Which systems store or process sensitive customer information.
- Which systems depend on legacy infrastructure.
- Which assets are essential for revenue generation and business continuity.
- How assets are classified and how their criticality is determined.
- Whether asset inventories are reviewed when systems change.
- Whether data retention and disposal requirements are documented.

These are assessment questions, not confirmed additional findings.

## 7. Recommendations

### Recommendation 1: Establish a Central Asset Register

Maintain a single inventory of hardware, software, systems, information assets, and relevant physical assets.

Each record should include an asset identifier, owner, location, business purpose, data classification, criticality, dependencies, and lifecycle status.

### Recommendation 2: Classify Sensitive Information

Identify customer personal information, payment card information, financial records, and other sensitive data.

Document where the information is collected, processed, transmitted, stored, accessed, and deleted.

### Recommendation 3: Identify Critical Dependencies

Document the systems and services that support e-commerce, payment processing, accounting, inventory management, and other important business functions.

Use this information to support recovery planning and prioritisation.

### Recommendation 4: Assign Asset Ownership

Assign responsibility for maintaining asset records, approving access, reviewing security requirements, and coordinating remediation.

### Recommendation 5: Review the Inventory Regularly

Establish a documented review schedule and update asset records when systems are introduced, changed, transferred, or retired.

## 8. Conclusion

The available case information shows that asset management is an important area for improvement at Botium Toys.

A complete and classified asset inventory would help the organisation understand its most important systems and information, identify relevant threats, assess business impact, and prioritise security controls.

The inventory developed in this document provides a starting point for the controls assessment and risk register. It should be treated as a preliminary inventory based on the fictional case, not as a verified inventory of a real organisation.

## 9. Source and Framework References

- Botium Toys: Scope, Goals, and Risk Assessment Report, supplied case material.
- NIST Cybersecurity Framework 2.0, for risk management and asset identification.
- NIST Privacy Framework, as a reference for managing privacy risks.
- CIA triad, for confidentiality, integrity, and availability analysis.
