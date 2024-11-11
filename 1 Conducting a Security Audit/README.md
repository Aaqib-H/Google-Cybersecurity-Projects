# Conducting a security audit for Botium Toys

## Project Description
This project simulates the role of a security analyst performing an internal security audit for **Botium Toys**, a fictional U.S.-based toy company. The audit was conducted to assess the company's security posture as it grows its online presence and navigates compliance requirements, especially for handling customer data and online payments, including in the E.U. The project involved evaluating existing controls, identifying compliance gaps, and recommending improvements to enhance Botium Toys' information security and resilience.

## Scenario
Botium Toys operates a physical storefront and a growing online business, requiring robust IT security practices to protect customer data, maintain business continuity, and comply with regulations. With a focus on establishing secure processing and storage of payment and personal data, Botium Toys’ IT manager has outlined an audit scope and goals to identify risks and compliance gaps.

## Audit Scope and Goals
- **Scope**: The audit covers all IT assets, including employee devices, network infrastructure, internal systems, and data management practices.
- **Goals**: Assess Botium Toys’ security controls, identify gaps, and evaluate compliance with standards such as PCI DSS, GDPR, and SOC. Complete the controls and compliance checklist and provide actionable recommendations to improve the company's security posture and regulatory compliance.

## Current Assets Managed by IT
1. On-premises equipment for in-office needs
2. Employee end-user devices (desktops/laptops, smartphones, remote workstations)
3. Storefront products in the adjoining warehouse
4. Systems and software for accounting, telecommunication, security, e-commerce, and inventory management
5. Internet access and internal network infrastructure
6. Data retention and storage systems
7. Legacy systems requiring manual maintenance and monitoring

## Risk Assessment
- **Risk Score**: 8/10 (High)
- **Key Risks**:
  - **Data Exposure**: Lack of encryption for sensitive data, such as customer credit card information.
  - **Access Control Issues**: All employees can access sensitive data, which increases the risk of data exposure.
  - **Compliance Risks**: Lack of adherence to certain compliance requirements (PCI DSS, GDPR) due to insufficient controls.
  - **Disaster Preparedness**: No disaster recovery plans or data backup systems in place, posing a risk to business continuity.
  - **Legacy System Maintenance**: Manual intervention for legacy systems without clear procedures, increasing potential vulnerability.

## Controls Assessment Checklist

| Control                           | In Place (Yes/No) | Explanation                                                                 |
|-----------------------------------|--------------------|-----------------------------------------------------------------------------|
| **Least Privilege**               | No                | All employees have access to customer data; privileges need restriction.    |
| **Disaster Recovery Plans**       | No                | No disaster recovery plans exist, which threatens business continuity.      |
| **Password Policies**             | No                | Minimal password requirements increase the risk of unauthorized access.      |
| **Separation of Duties**          | No                | CEO manages critical operations alone, creating risk of fraud/access issues.|
| **Firewall**                      | Yes               | Existing firewall blocks traffic based on security rules.                   |
| **Intrusion Detection System (IDS)** | No             | No IDS in place to detect potential intrusions.                             |
| **Backups**                       | No                | Lack of data backups endangers data recovery capabilities.                  |
| **Antivirus Software**            | Yes               | Installed and regularly monitored by IT.                                    |
| **Legacy System Monitoring**      | No                | Legacy systems require more consistent monitoring and intervention.         |
| **Encryption**                    | No                | Customer credit card information is not encrypted.                          |
| **Password Management System**    | No                | No system for managing or enforcing password policy complexity.             |
| **Physical Locks**                | Yes               | Sufficient locks at the store, office, and warehouse.                       |
| **CCTV Surveillance**             | Yes               | CCTV installed and functional at the physical location.                     |
| **Fire Detection/Prevention**     | Yes               | Fire alarms and sprinklers are operational.                                 |

## Compliance Assessment Checklist

### PCI DSS (Payment Card Industry Data Security Standard)
- **Only authorized users have access to customer credit card information**: **No** – All employees currently have access to this data.
- **Customer credit card information is stored securely**: **No** – Lacks encryption, and all employees have access.
- **Implement encryption procedures**: **No** – Encryption is not in use, leaving customer data exposed.
- **Adopt secure password management policies**: **No** – Minimal password requirements and no password management system.

### GDPR (General Data Protection Regulation)
- **E.U. customers' data is kept private/secured**: **No** – Lack of encryption leaves data exposed.
- **Plan in place to notify E.U. customers of breaches within 72 hours**: **Yes** – Plan established to meet GDPR notification requirements.
- **Data properly classified and inventoried**: **No** – Assets are inventoried but not classified.
- **Privacy policies, procedures, and processes enforced**: **Yes** – Documented and enforced among IT and relevant staff.

### SOC Compliance (System and Organization Controls)
- **User access policies established**: **No** – No least privilege or separation of duties in place; all employees have access to data.
- **Sensitive data (PII/SPII) remains confidential**: **No** – No encryption for sensitive data.
- **Data integrity maintained**: **Yes** – Data integrity is ensured.
- **Data access restricted to authorized personnel**: **No** – All employees currently have access.

## Key Recommendations
1. **Implement Least Privilege Access**: Restrict access to customer data based on job roles.
2. **Enforce Data Encryption**: Encrypt customer credit card information to comply with PCI DSS and GDPR standards.
3. **Establish a Disaster Recovery Plan**: Develop and test disaster recovery protocols and implement regular data backups.
4. **Upgrade Password Policies**: Enforce strong password policies and introduce a password management system.
5. **Deploy an Intrusion Detection System (IDS)**: Monitor for potential intrusions with an IDS.
6. **Regular Legacy System Monitoring**: Implement a consistent schedule for monitoring and maintaining legacy systems.

## Project Outcome
The audit identified significant areas for improvement in Botium Toys’ security and compliance practices. Implementing the recommendations would enhance data confidentiality, integrity, and availability, while aligning with applicable standards and reducing compliance risks.

## Supporting Documents
The files are in .docx format. Please download them to view them.
- [Scope, Goals, and Risk Assessment Report](https://github.com/Aaqib-H/Google-Cybersecurity-Projects/blob/main/1%20Conducting%20a%20Security%20Audit/Botium%20Toys_%20Scope%2C%20goals%2C%20and%20risk%20assessment%20report.docx)
- [Controls Categories](https://github.com/Aaqib-H/Google-Cybersecurity-Projects/blob/main/1%20Conducting%20a%20Security%20Audit/Control%20categories.docx)
- [Controls and Compliance Checklist](https://github.com/Aaqib-H/Google-Cybersecurity-Projects/blob/main/1%20Conducting%20a%20Security%20Audit/Controls%20and%20compliance%20checklist.docx)

