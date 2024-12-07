# Internal Security Audit for Botium Toys

## Introduction
This project involves conducting an internal security audit for Botium Toys, a small U.S.-based toy company with a growing online presence. The purpose of the audit is to identify gaps in security controls and compliance practices, evaluate risks, and provide actionable recommendations to improve the organization’s security posture.

## Scope and Goals

### Scope
The audit covers all aspects of Botium Toys' security program, including:
- IT-managed assets such as on-premises and employee equipment.
- Systems like accounting, telecommunications, and inventory management.
- Internal network, legacy systems, and data retention.

### Goals
- Assess existing assets and controls to identify gaps.
- Evaluate compliance with relevant regulations such as PCI DSS, GDPR, and SOC standards.
- Provide recommendations to improve Botium Toys' overall security posture.

## Current Assets
The following assets are managed by the IT department:
- On-premises equipment for in-office business needs.
- Employee equipment: desktops, laptops, smartphones, remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online.
- Management systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management.
- Internet access and internal network.
- Data retention and storage solutions.
- Legacy systems requiring manual monitoring and maintenance.

## Risk Assessment

### Risk Description
- **Risk Score:** 8/10 (High).
- **Key Risks:**
  1. Unrestricted employee access to sensitive customer data (PII/SPII).
  2. Lack of encryption for sensitive data, including credit card information.
  3. No disaster recovery plan or intrusion detection system (IDS) in place.
  4. Weak password policies and no centralized password management system.

### Potential Impact
- **Medium:** Loss of assets due to inadequate tracking.
- **High:** Regulatory fines due to non-compliance with standards like PCI DSS and GDPR.

---

## Controls and Compliance Checklist

### Controls Assessment

| **Control**                     | **Implemented?** | **Details**                                                                                     |
|----------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| Least Privilege                 | No               | Employees have unrestricted access to sensitive data.                                           |
| Disaster Recovery Plans         | No               | No disaster recovery plans are in place.                                                       |
| Password Policies               | No               | Existing policies do not meet minimum complexity requirements.                                  |
| Separation of Duties            | No               | No clear separation of duties is implemented.                                                  |
| Firewall                        | Yes              | Installed and configured with appropriate security rules.                                       |
| Intrusion Detection System (IDS)| No               | IDS is not currently deployed.                                                                 |
| Backups                         | No               | No backups of critical data are being performed.                                               |
| Antivirus Software              | Yes              | Installed and monitored regularly.                                                             |
| Monitoring for Legacy Systems   | Yes              | Legacy systems are monitored, but there is no regular schedule.                                |
| Encryption                      | No               | Sensitive data is not encrypted.                                                               |
| Password Management System      | No               | No centralized password management system in place.                                            |
| Locks (Offices, Storefront)     | Yes              | Physical locks are in place for critical infrastructure.                                        |
| CCTV Surveillance               | Yes              | Functional and up-to-date CCTV systems are installed.                                          |
| Fire Detection/Prevention       | Yes              | Fire detection systems and sprinklers are in place.                                            |

### Compliance Assessment

#### PCI DSS (Payment Card Industry Data Security Standard)

| **Best Practice**                                              | **Implemented?** | **Details**                                                                                     |
|----------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| Authorized access to credit card data                         | No               | Employees have unrestricted access to sensitive credit card data.                              |
| Secure storage and transmission of credit card data           | No               | Credit card data is neither encrypted nor stored in a secure environment.                      |
| Encryption of credit card data                                | No               | Encryption is not implemented.                                                                 |
| Secure password management                                    | No               | Password policies are weak, and no centralized system is in place.                             |

#### GDPR (General Data Protection Regulation)

| **Best Practice**                                              | **Implemented?** | **Details**                                                                                     |
|----------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| Secure storage of E.U. customer data                          | No               | E.U. customer data is not encrypted or access-restricted.                                      |
| Plan to notify E.U. customers of a breach                     | Yes              | A notification plan exists to inform customers within 72 hours of a breach.                    |
| Proper data classification and inventory                     | No               | Data is not properly classified or inventoried.                                                |
| Privacy policies and procedures                               | Yes              | Policies are enforced among IT staff and employees.                                            |

---

## Recommendations
Based on the findings, the following recommendations are made to improve Botium Toys' security posture:

1. **Implement Least Privilege Access Controls:**
   - Restrict access to sensitive data based on roles and responsibilities.

2. **Strengthen Password Policies:**
   - Enforce a minimum complexity requirement (e.g., 12 characters, mixed case, symbols, numbers).
   - Deploy a centralized password management system.

3. **Adopt Data Encryption:**
   - Use encryption for sensitive data to meet PCI DSS and GDPR requirements.

4. **Deploy an Intrusion Detection System (IDS):**
   - Install and configure an IDS to monitor network activity and detect potential threats.

5. **Establish a Disaster Recovery Plan:**
   - Develop and test a disaster recovery plan to ensure business continuity in case of an incident.

6. **Schedule Regular Maintenance for Legacy Systems:**
   - Create a maintenance schedule to ensure outdated systems are properly monitored and secured.

7. **Enhance Compliance Efforts:**
   - Ensure adherence to PCI DSS and GDPR by implementing encryption and access control measures.

---

## Supporting Files
- **[Controls and Compliance Checklist](Controls-and-Compliance-Checklist.docx)**
- **[Risk Assessment Report](Risk-Assessment-Report.docx)**
