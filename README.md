<h1 style="font-size:300%;">Botium Toys Security Audit Conduct</h1>

<h1 style="font-size:160%;">Scenario</h1>

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 
The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   
The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.
Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 



<h1 style="font-size:160%;">Scope and Goals of the audit</h1>

<b>Scope:</b>

Botium Toys' internal IT audit will assess the following:

1. Current user permissions set in the following systems: accounting, endpoint detection, firewalls, intrusion detection system, security information, and event management (SIEM) tool.
2. Current implemented controls in the following systems: accounting, endpoint detection, firewalls, intrusion detection system, Security Information, and Event Management (SIEM) tool.
3. Current procedures and protocols set for the following systems: accounting, endpoint detection, firewall, intrusion detection system, Security Information, and Event Management (SIEM) tool.
4. Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
5. Ensure current technology is accounted for. Both hardware and system access.
   
<b>Goals:</b>

The goals for Botium Toys’ internal IT audit are:

1. To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
2. Establish a better process for their current systems to ensure they are compliant
3. Fortify system controls
4. Implement the concept of least privilege when it comes to user credential management
5. Establish their policies and procedures, which includes their playbooks
6. Ensure they are meeting compliance requirements.

<b>Current assets:</b>

1. On-premises equipment for in-office business needs   
2. Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
3. Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
4. Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management 
5. Internet access  
6. Internal network
7. Data retention and storage
8. Legacy system maintenance: end-of-life systems that require human monitoring

<h1 style="font-size:160%;">Risk assessment</h1>

<b>Risk description:</b>

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

<b>Control best practices:</b>

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

<b>Risk score:</b>

On a scale of 1 to 10, the risk score is 8, which is high. This is due to a lack of controls  and adherence to compliance best practices.

<b>Additional comments:</b>

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure.
Review the following bullet points for specific details:
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



<h1 style="font-size:160%;">Control categories</h1>

<b>Control categories:</b>

Controls within cybersecurity are grouped into three main categories:

<b>● Administrative/Managerial controls

   ● Technical controls
   
   ● Physical/Operational controls</b>
   
<b>Administrative/Managerial controls</b> address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsibilities, including their role in protecting the organization. While administrative controls are typically policy based, the enforcement of those policies may require the use of technical or physical controls.

<b>Technical controls</b> consist of solutions such as firewalls, intrusion detection systems(IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in a number of ways to meet organizational goals and objectives.

<b>Physical/Operational controls</b> include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.

<b>Control types</b>

Control types include, but are not limited to:

<ol><b>
<li> Preventative</li>	
<li>Corrective</li>
<li>Detective  </li>
<li> Deterrent</li>
 </b></ol>
 
These controls work together to provide defense in depth and protect assets.

<b>1.Preventative controls</b> are designed to prevent an incident from occurring in the first place.

<b>2.Corrective controls</b> are used to restore an asset after an incident.

<b>3.Detective controls</b> are implemented to determine whether an incident has occurred or is in progress.

<b>4.Deterrent controls</b> are designed to discourage attacks.


Review the following charts for specific details about each type of control and its purpose.

<h1 style="font-size:160%;">Administrative Controls</h1>
<table>
  <tr>
    <th>Control Name</th>
    <th>Control Type and Purpose</th>
    <th>Needs to be Implemented</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Least Privilege</td>
    <td>Preventative: reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs.</td>
    <td>X</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Disaster recovery plans </td>
    <td>Corrective. Provide business continuity to ensure systems can run in the event of an incident/there is limited to no loss of productivity own time/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration</td>
    <td>X</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Password policies </td>
    <td>Preventative: establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques</td>
    <td>X</td>
    <td>High</td>
  </tr>
   <tr>
    <td>Access Control Policy	 </td>
    <td>Preventative; increase confidentiality and integrity of data</td>
    <td>X</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Account Management Policies</td>
    <td>Preventative: reduce attack surface and limit overall impact from disgruntled/former employees</td>
    <td>X</td>
    <td>High</td>
  </tr>
  <tr>
	  <td>Separation of duties</td>	
	  <td>Preventative: ensure no one has so much access that they can abuse the system for personal gain</td>
	  <td>X</td>
	<td>High</td>
</tr>
	 
</table>	

<h1 style="font-size:160%;">Technical Controls</h1>
<table>
  <tr>
    <th>Control Name</th>
    <th>Control Type and Purpose</th>
    <th>Needs to be Implemented</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Firewalls</td>
    <td>Preventative:firewalls are already in place to filter unwanted/malicious traffic from entering internal network </td>
    <td>NA</td>
    <td>Low</td>
  </tr>
  <tr>
<td>Intrusion Detection System (IDS)</td>	
<td>Detective: allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly</td>	
<td>X</td>
	<td>High</td>
 </tr>
<tr>
	<td>Encryption</td>
	<td>Deterrent; makes confidential information/data more secure (e.g., website payment transactions)</td>
	<td>X</td>
	<td>High</td>
	</tr>
<tr>
	
<td>Backups</td>
<td>Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan</td>
<td>X</td>

<td>High</td>
</tr>
<tr>
	<td>Password management system</td>
	<td>Corrective: password recovery, reset, lock out notifications</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Antivirus (AV) software</td>
	<td>Corrective: password recovery, reset, lock out notifications</td>
	<td>X</td>
	<td>	High</td>
</tr>
<tr>
<td>Manual monitoring, maintenance, and intervention</td>
	<td>Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities</td>
	<td>X</td>
	<td>High</td>
</tr>
</table>

<h1 style="font-size:160%;">Physical Controls</h1>
<table>
  <tr>
    <th>Control Name</th>
    <th>Control Type and Purpose</th>
    <th>Needs to be Implemented</th>
    <th>Priority</th>
  </tr>

<tr>
	<td>Time-controlled safe</td>
	<td>Deterrent; reduce attack surface/impact of physical threats</td>
	<td>NA</td>
	<td>Medium/Low
	</td>
</tr>
<tr>
	<td>Adequate lighting</td>
	<td>Deterrent: limit “hiding” places to deter threats</td>	
	<td>X</td>
	<td>Medium/Low</td>
</tr>
<tr>
<td>Closed-circuit television (CCTV) surveillance</td>
	<td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation</td>
	<td>	X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Locking cabinets (for network gear)	</td>
	<td>Preventative: increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear
	</td>
	<td>X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Signage indicating alarm service provider</td>
	<td>Deterrent: makes the likelihood of a successful attack seem low</td>
	<td>X</td>
	<td>Low</td>
</tr>
 <tr>
	 <td>Locks</td>
	 <td>Preventative: physical and digital assets are more secure</td>
	 <td>X</td>
	 <td>High</td>
 </tr>
<tr>
	
<td>Fire detection and prevention (fire alarm, sprinkler system, etc.)	</td>

<td>Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.</td>

<td>X</td>
	
 <td>Medium</td>
</tr>
</table>


<h1 style="font-size:160%;">Compliance Evaluation</h1>

<b>Payment Card Industry Data Security Standard (PCI DSS):- </b>

<b>Authorized Access Control:</b>

Not Satisfactory - Currently, all employees possess access to the company’s internal data, including customer credit card information.

<b> Handling of Credit Card Data:</b>
Adequate - However, improvements are imperative, particularly in the realm of data encryption.

<b>Data Encryption Procedures:</b>

Absent - Encryption is not employed to ensure the confidentiality of financial information.

<b>Password Management Policies:</b>

Inadequate - Existing policies lack robustness, and a password management system is conspicuously absent.

<h1 style="font-size:160%;">General Data Protection Regulation (GDPR)</h1>

<b> Data Confidentiality: </b>

Unsatisfactory - Encryption measures need to be introduced to safeguard financial data.

<b> Data Breach Notification: </b>

Adequate - A plan exists for notifying E.U. customers within 72 hours of a data breach.

<b> Data Classification and Inventory:</b>

Incomplete - Assets have been inventoried but require systematic classification.

<b>Enforcement of Privacy Policies: </b>

Adequate - Privacy policies are in place and stringently enforced among IT team members and other relevant staff.

<h1 style="font-size:160%;">System and Organizations Controls (SOC type 1, SOC type 2)</h1>

<b>User Access Policies: </b>

Absent - Controls pertaining to least privilege and separation of duties require implementation, as unrestricted access is currently granted to all employees.

<b>Handling of Sensitive Data:</b>

Inadequate - Encryption is not employed to ensure the confidentiality of sensitive data.

<b>Data Integrity: </b>

Adequate - Measures for data integrity have been implemented.

<b>Authorized Data Access: </b>

Incomplete - Access control should be restricted to authorized personnel for enhanced data security.


<a href="">Back to Profile</a>


