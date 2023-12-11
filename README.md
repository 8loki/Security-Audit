# Security-Audit-Practice
IT Security Recommendations 

## Botium Toys: Scope, Goals, and Risk Assessment Report

## Scope and Goals of the Audit
### Scope:
The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.
### Goals:
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.

## Current Assets
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

## Risk Assessment
### Risk Description:
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.
### Control Best Practices:
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
### Risk Score:
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
### Additional Comments:
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure.

Review the following bullet points for specific details:
- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.


### My Recommendations to Enhance IT Security and Data Management:

1. **Implement Least Privilege:** Restrict user access to only the resources and data necessary for their roles. This helps limit potential damage from insider threats or compromised accounts.

2. **Develop Comprehensive Disaster Recovery Plans:** Formulate detailed procedures to recover IT infrastructure and data in case of emergencies or disasters. This includes regular backups, off-site storage, and a tested recovery process.

3. **Enforce Strong Password Policies:** Implement guidelines for creating and managing passwords securely, including complexity requirements, regular changes, and multi-factor authentication where possible.

4. **Establish Separation of Duties:** Define clear roles and responsibilities to prevent any single individual from having complete control over critical systems or processes.

5. **Consider Implementing an Intrusion Detection System (IDS):** IDS helps in identifying and responding to potential security threats in real-time, enabling proactive measures against attacks.

6. **Regular Backups:** Establish a routine backup strategy for essential data and systems to ensure minimal data loss in case of system compromise or failure.

7. **Enable Encryption:** Implement encryption protocols to protect sensitive data both in transit and at rest, enhancing overall data security.

8. **Adopt a Password Management System:** Consider using a password manager to securely store and manage access credentials.

9. **Ensure Compliance with Data Privacy Regulations:** Especially concerning E.U. customer data, make sure to follow GDPR guidelines and protect customer information according to legal requirements.

10. **Establish User Access Policies:** Define and enforce strict access control policies, limiting access to sensitive data to authorized personnel only.

11. **Protect Sensitive Data:** Implement measures to ensure confidentiality, integrity, and availability of personally identifiable information (PII) and sensitive personal information (SPII).

12. **Regularly Validate Data Integrity:** Ensure that data remains accurate, complete, and consistent throughout its lifecycle.
