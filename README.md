Botium Toys Security Audit Conduct

Scenario
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 
The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   
The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.
Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 



Scope and Goals of the audit
Scope: Botium Toys' internal IT audit will assess the following:

1. Current user permissions set in the following systems: accounting, endpoint detection, firewalls, intrusion detection system, security information, and event management (SIEM) tool.
2. Current implemented controls in the following systems: accounting, endpoint detection, firewalls, intrusion detection system, Security Information, and Event Management (SIEM) tool.
3. Current procedures and protocols set for the following systems: accounting, endpoint detection, firewall, intrusion detection system, Security Information, and Event Management (SIEM) tool.
4. Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
5. Ensure current technology is accounted for. Both hardware and system access.
Goals: 
The goals for Botium Toys’ internal IT audit are:
1. To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
2. Establish a better process for their current systems to ensure they are compliant
3. Fortify system controls
4. Implement the concept of least privilege when it comes to user credential management
5. Establish their policies and procedures, which includes their playbooks
6. Ensure they are meeting compliance requirements.

Current assets:
1. On-premises equipment for in-office business needs
2. Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
3.Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
4. Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
5. Internet access
6. Internal network
7. Data retention and storage
8. Legacy system maintenance: end-of-life systems that require human monitoring
Risk assessment:
Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.
Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
Risk score
On a scale of 1 to 10, the risk score is 8, which is high. This is due to a lack of controls  and adherence to compliance best practices.
Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:
1. Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
2. Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
3. Access controls pertaining to least privilege and separation of duties have not been implemented.
4. The IT department has ensured availability and integrated controls to ensure data integrity.
5. The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
6. Antivirus software is installed and monitored regularly by the IT department.
7. The IT department has not installed an intrusion detection system (IDS).
8. There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
9. The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
10. Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
11. There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
12. While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
13. The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.



Control categories

Control categories
Controls within cybersecurity are grouped into three main categories:
● Administrative/Managerial controls
● Technical controls
● Physical/Operational controls
Administrative/Managerial controls address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsibilities, including their role in protecting the organization. While administrative controls are typically policy based, the enforcement of those policies may require the use of technical or physical controls.
Technical controls consist of solutions such as firewalls, intrusion detection systems(IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in a number of ways to meet organizational goals and objectives.
Physical/Operational controls include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.
Control types
Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent
These controls work together to provide defense in depth and protect assets. Preventative controls are designed to prevent an incident from occurring in the first place. Corrective controls are used to restore an asset after an incident. Detective controls are implemented to determine whether an incident has occurred or is in progress. Deterrent controls are designed to discourage attacks.


Review the following charts for specific details about each type of control and its purpose.
Administrative Controls:
Control Name	Control Type and Purpose	Needs to be Implemented	Priority
Least Privilege	Preventative: reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs.	X
	High
Disaster recovery plans 
	Corrective. Provide business continuity to ensure systems can run in the event of an incident/there is limited to no loss of productivity own time/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration	X
	High
Password policies	
	Preventative: establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques
	X
	High
Access Control Policy	Preventative; increase confidentiality and integrity of data	X
	High
Account Management Policies	Preventative: reduce attack surface and limit overall impact from disgruntled/former employees	X
	High
Separation of duties	Preventative: ensure no one has so much access that they can abuse the system for personal gain	X
	High



Technical Controls
Control Name	Control Type and Purpose	Needs to be Implemented	Priority
Firewalls	Preventative: firewalls are already in place to filter unwanted/malicious traffic from entering internal network	NA
	Low
Intrusion Detection System (IDS)	Detective: allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly	X
	High
Encryption
	Deterrent; makes confidential information/data more secure (e.g., website payment transactions)	X
	High
Backups	Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan	X
	High
Password management system
	Corrective: password recovery, reset, lock out notifications	X
	High
Antivirus (AV) software	Corrective: password recovery, reset, lock out notifications	X
	High
Manual monitoring, maintenance, and intervention	Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities	X
	High










Physical Controls:
Control Name	Control Type and Purpose	Needs to be Implemented	Priority
Time-controlled safe
	Deterrent; reduce attack surface/impact of physical threats	NA
	Medium/Low
Adequate lighting	Deterrent: limit “hiding” places to deter threats	X
	Medium/Low
Closed-circuit television (CCTV) surveillance	Preventative/detective; can reduce risk of certain events; can be used after event for investigation	X
	High/Medium
Locking cabinets (for network gear)	Preventative: increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear	X
	High/Medium
Signage indicating alarm service provider	Deterrent: makes the likelihood of a successful attack seem low	X
	Low
Locks	Preventative: physical and digital assets are more secure	X
	High
Fire detection and prevention (fire alarm, sprinkler system, etc.)	Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.	X
	Medium




Compliance Evaluation:
Payment Card Industry Data Security Standard (PCI DSS):- 
Authorized Access Control: Not Satisfactory - Currently, all employees possess access to the company’s internal data, including customer credit card information.
- Handling of Credit Card Data: Adequate - However, improvements are imperative, particularly in the realm of data encryption.
- Data Encryption Procedures: Absent - Encryption is not employed to ensure the confidentiality of financial information.
- Password Management Policies: Inadequate - Existing policies lack robustness, and a password management system is conspicuously absent.
General Data Protection Regulation (GDPR):
- Data Confidentiality: Unsatisfactory - Encryption measures need to be introduced to safeguard financial data.
- Data Breach Notification: Adequate - A plan exists for notifying E.U. customers within 72 hours of a data breach.
- Data Classification and Inventory: Incomplete - Assets have been inventoried but require systematic classification.
- Enforcement of Privacy Policies: Adequate - Privacy policies are in place and stringently enforced among IT team members and other relevant staff.

System and Organizations Controls (SOC type 1, SOC type 2):
- User Access Policies: Absent - Controls pertaining to least privilege and separation of duties require implementation, as unrestricted access is currently granted to all employees.
- Handling of Sensitive Data: Inadequate - Encryption is not employed to ensure the confidentiality of sensitive data.
- Data Integrity: Adequate - Measures for data integrity have been implemented.
- Authorized Data Access: Incomplete - Access control should be restricted to authorized personnel for enhanced data security.


