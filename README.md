# security-audit-project
Conducting a simulated internal IT audit for the fictional company Botium Toys, evaluating IT controls, identifying vulnerabilities, and reviewing NIST CSF compliance.

# Internal Security Audit – Botium Toys (Simulated)

## Scenario
Botium Toys is a small U.S. business that develops and sells toys, with a single physical location serving as office, storefront, and warehouse. 
Their online presence has grown internationally, putting pressure on the IT department to maintain secure operations.

The IT manager initiated an internal audit to better secure the company’s infrastructure, identify potential risks, threats, and vulnerabilities, and ensure compliance with regulations for processing online payments and conducting business in the E.U.

## Objective
To evaluate existing IT controls, identify gaps and vulnerabilities, and provide actionable recommendations to improve Botium Toys' security posture while supporting compliance with NIST CSF and relevant regulations.

## Scope
The audit scope includes the entire security program at Botium Toys, covering IT assets (employee devices, office equipment), internal networks, and critical systems. All assets and existing controls will be reviewed for compliance and effectiveness.

### Goals
- Assess existing IT assets and classify them by criticality
- Complete controls and compliance checklist
- Identify gaps in security controls and compliance
- Provide actionable recommendations to improve overall security posture

## Methodology
The internal IT audit followed the NIST Cybersecurity Framework (CSF) guidelines:

1. **Review of IT Assets** – Inventory of all IT assets including devices, software, network, and physical assets.  
2. **Risk Assessment** – Analyze gaps, identify vulnerabilities, assign risk scores.  
3. **Control Evaluation** – Evaluate existing technical and administrative controls.  
4. **Compliance Review** – Compare practices against NIST CSF and relevant regulations.  
5. **Documentation** – Compile findings and recommendations.

**Supporting documents:**
- [Scope, Goals, and Risk Assessment Report](./Botium Toys_ Scope_goals_risk_assessment_report.pdf)
- [Controls Checklist](./Controls_Checklist.pdf)

## Findings

The audit revealed several vulnerabilities and gaps in Botium Toys’ IT environment:

- **Asset Management:** Inadequate tracking and classification of assets; all employees currently have access to critical data, including cardholder information and PII.
- **Data Protection:** Lack of encryption for sensitive data; no intrusion detection system (IDS) implemented.
- **Access Controls:** Least privilege and separation of duties not enforced; nominal password policy without centralized enforcement.
- **Disaster Recovery:** No formal disaster recovery plan or backups for critical systems.
- **Compliance:** Partial compliance with E.U. GDPR requirements; gaps in best practices for risk and control management.
- **Physical Security:** The physical office, store, and warehouse are secured with locks, CCTV, and fire prevention systems.
- **Legacy Systems:** Monitored manually but without a regular schedule or clear intervention methods.
- **Strengths:** Firewalls and antivirus software are implemented and monitored; data availability and integrity measures in place.

## Recommendations

Based on the audit findings, the following recommendations are proposed to improve Botium Toys’ security posture and compliance:

- **Asset Management:**  
  - Create and maintain a centralized database of all company assets (physical and digital).  
  - Classify and prioritize assets based on their value and criticality to business operations.

- **Access Control:**  
  - Implement the principle of **least privilege** to ensure employees have access only to resources necessary for their role and tasks.  
  - Enforce proper authorization processes for access based on department and responsibilities.  
  - Apply the **Principle of Separation of Duties (SoD)** for critical processes, ensuring no single employee has control over all steps of sensitive operations (e.g., financial transactions or access to critical systems).

- **Data Protection:**  
  - Encrypt sensitive data, including customer information, employee data, and critical system data, to protect against internal and external threats.  
  - Implement multi-factor authentication (MFA) for all critical accounts.

- **Network Security:**  
  - Deploy additional firewalls and configure SIEM tools to monitor and detect threats in system logs.  
  - Implement an Intrusion Detection System (IDS) to identify and respond to potential network intrusions.  
  - Segment networks containing critical or sensitive assets to harden infrastructure against attacks.

- **Disaster Recovery:**  
  - Develop and implement a disaster recovery plan, including regular backups of critical data.  
  - Ensure continuity of business operations in the event of incidents or attacks.

- **User and Password Management:**  
  - Establish policies for secure user account creation and password complexity aligned with NIST CSF standards.  
  - Centralize user and password management for easier recovery, monitoring, and enforcement.  

- **Legacy Systems:**  
  - Maintain legacy systems that cannot receive patches or updates with constant monitoring.  
  - Plan migration to cloud-based systems to ensure up-to-date security and reduce operational risks.

## Skills Demonstrated

- **Risk Assessment & Analysis**: Conducted a detailed risk assessment of IT assets, identifying vulnerabilities, potential threats, and gaps in controls.  
- **Security Control Evaluation**: Evaluated technical, administrative, and physical security controls, including firewalls, antivirus, access controls, and legacy system management.  
- **Regulatory Compliance Awareness**: Assessed compliance with NIST CSF and relevant U.S. and E.U. regulations, including GDPR and data privacy requirements.  
- **Access Management & Least Privilege**: Applied principles of least privilege, proper user access controls, and centralized account/password management policies.  
- **Data Protection & Encryption**: Evaluated encryption needs and data protection mechanisms to safeguard sensitive information.  
- **Network Security Fundamentals**: Reviewed network segmentation, firewall deployment, IDS, and monitoring strategies using SIEM tools.  
- **Disaster Recovery & Business Continuity Planning**: Designed recommendations for backup strategies and disaster recovery plans to maintain operational continuity.  
- **Legacy System Management**: Assessed risks associated with legacy systems and proposed upgrades/migration strategies for cloud-based environments.  
- **Documentation & Reporting**: Produced professional audit documentation, summarizing methodology, findings, and actionable recommendations.  
- **Analytical & Problem-Solving Skills**: Applied structured thinking to identify risks, prioritize remediation, and propose practical solutions.
