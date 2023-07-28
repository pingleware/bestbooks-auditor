# BestBooks Accounting Application Framework - AUDITOR

Using the R-language and examples from https://github.com/ameypophali/Auditing-financial-data-using-R.git and https://github.com/PieInOblivion/ABRA repositories.

BestBooks Auditor will provide automatic financial audits with a notation added to the financial report using the noteToFinancialStatement component of bestbooks-reports.

## Introduction to R

See https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf

## Installing R

R language is required and can be installed from https://www.r-project.org/. The Rscript tool is used to launch R scripts from the command line, and is included in the R installation package.

## Financial Statement Notes

An entry to the financial statements by bestbooks-auditor would be considered a management entry since the BestBooks Auditor is NOT a registered CPA or licensed Auditor.

### 10 GAAP Principles

1. **Principle of Regularity:** GAAP-compliant accountants strictly adhere to established rules and regulations.
2. **Principle of Consistency:** Consistent standards are applied throughout the financial reporting process.
3. **Principle of Sincerity:** GAAP-compliant accountants are committed to accuracy and impartiality.
4. **Principle of Permanence of Methods:** Consistent procedures are used in the preparation of all financial reports.
5. **Principle of Non-Compensation:** All aspects of an organization's performance, whether positive or negative, are fully reported with no prospect of debt compensation.
6. **Principle of Prudence:** Speculation does not influence the reporting of financial data.
7. **Principle of Continuity:** Asset valuations assume the organization's operations will continue.
8. **Principle of Periodicity:** Reporting of revenues is divided by standard accounting periods, such as fiscal quarters or fiscal years.
9. **Principle of Materiality:** Financial reports fully disclose the organization's monetary situation.
10. **Principle of Utmost Good Faith:** All involved parties are assumed to be acting honestly.

## Audits

The audits which can be automated include,

    - Fixed and Intangible Assets

    - Prepaid Expenses and Deferred Charges

    - Details and Transactions

    - Long Term Liabilities and Stockholder Equity

    - Cash and Investments (common accounts inclulde: Operating Checking Account, Payroll Checking Account, Merchant Account and Money Market Account [can also be currency trading account, a sweep account may also serve as this purpos ]))

* **Anti Money Laundering (AML), review of OFAC (Office of Foreign Assets Control) procedures and AML processes, strategy, policy, controls and related technologies.**
* **Financial Condition, expresses an unqualified opinion, that the financial statements were presented fairly, in all material respects, in accordance with US GAAP accounting principles.**
* **Digital Currency required because custody bitcoin on behalf of our clients, Grant Thorton conducted a thorough examination of how we hold digital assets.**
* **Security, an Information Technology (IT) Security Risk Assessment that evaluated the effectiveness of existing security controls.**
* **Internal Controls, (technically known as a SOC I Type II Audit) to ensure that they are operating effectively and appropriately protecting client data**
* **Onsite IT systems, onsite systems and safeguards**

## Internal Controls

An important factor of audits is to access the risk of internal controls. When revenue was received by the USPS, there were four employees to process, record and deposit the checks received. In today's economy where electronic payments are the norm, a paper trail is already established and routing payments to operating accountin is usually automatic.

Technically known as a SOC I Type II Audit. A SOC 1 –Type II audit report **contains the same opinions as a Type I, but it adds an opinion on the operating effectiveness to achieve related control objectives throughout a specified period**

## Conducting a SOC 1 - Type II Audit

SOC 1 audits focus on the controls related to financial reporting, so it's important to ensure that the controls are adequately designed and operating effectively. Here's an outline of the process:

1. Understand the Audit Scope: Familiarize yourself with the scope and objectives of the SOC 1 - Type II audit. Determine the specific controls and processes that need to be assessed.
2. Identify Control Objectives: Identify the control objectives for the audit. These objectives define the criteria against which the controls will be evaluated. Control objectives typically include areas such as data security, access controls, change management, and backup and recovery procedures.
3. Design Audit Tests: Develop a plan for testing the controls. This includes determining the appropriate audit procedures, sampling methods, and data analysis techniques. R can be used for data analysis and statistical procedures to support the audit testing.
4. Data Collection: Collect the necessary data and evidence to support the audit procedures. This may involve gathering documentation, conducting interviews, or extracting data from relevant systems. R can be used for data extraction, transformation, and loading (ETL) processes.
5. Perform Audit Procedures: Execute the audit procedures according to the plan. This may involve testing the controls, reviewing documentation, and analyzing data. R can be used for performing data analysis, statistical tests, and generating audit reports.
6. Evaluate Control Effectiveness: Assess the effectiveness of the controls based on the audit findings. Determine if the controls are adequately designed and operating effectively to achieve the control objectives.
7. Document Audit Findings: Document the audit findings, including any control deficiencies or areas for improvement. R can be used to generate audit reports, charts, and visualizations to communicate the results effectively.
8. Issue Audit Report: Prepare and issue the SOC 1 - Type II audit report based on the audit findings. The report should include a description of the scope, control objectives, testing procedures, and the results of the audit.

It's worth noting that while R can be used for data analysis and statistical procedures, conducting a SOC 1 - Type II audit involves a broader set of activities that require expertise in auditing, accounting, and information systems. Therefore, it's essential to have a thorough understanding of the audit requirements and engage qualified professionals to perform the audit.

### Scope and Objectives

The scope and objectives of a SOC 1 - Type II audit are focused on assessing the effectiveness of a service organization's internal controls over financial reporting. The audit is conducted to provide assurance to user entities (typically the service organization's clients) regarding the reliability and security of the financial information processed by the service organization. Here's an overview of the scope and objectives:

1. Scope:

   - The audit scope defines the boundaries and components of the audit engagement. It specifies the systems, processes, and controls that are subject to examination.
   - The scope typically includes the service organization's financial systems, applications, and related processes that are relevant to the financial reporting of the user entities.
   - It may also include the underlying IT infrastructure, data centers, and other systems that support the financial processes.
2. Objectives:

   - The primary objective of a SOC 1 - Type II audit is to assess the effectiveness of the service organization's controls over financial reporting.
   - The audit aims to determine if the controls are suitably designed to achieve specific control objectives and whether they have been operating effectively over a specified period of time.
   - The control objectives typically include areas such as data integrity, security, availability, processing accuracy, and compliance with relevant regulations or industry standards.
   - The audit provides assurance to user entities that the service organization's controls adequately safeguard their financial information and ensure the reliability of financial reporting.

The SOC 1 - Type II audit follows the guidelines and criteria established by the American Institute of Certified Public Accountants (AICPA). It requires the service organization to provide detailed information about its systems, controls, and processes. The audit involves testing and evaluating the design and operating effectiveness of the controls, as well as assessing any identified control deficiencies or weaknesses.

It's important to note that the specific scope and control objectives of the audit may vary depending on the nature of the service organization's business, industry regulations, and client requirements. Therefore, it is crucial to consult with qualified professionals and engage with a reputable audit firm to ensure compliance with the appropriate standards and guidelines.

### Control Objectives

When conducting a SOC 1 - Type II audit, the control objectives can vary depending on the nature of the service organization's operations, industry regulations, and client requirements. However, here are some common control objectives that are typically assessed in a SOC 1 - Type II audit:

1. Security Controls:
   a. Access Controls: Ensure that access to systems and data is appropriately restricted, and user access is granted based on authorized roles and responsibilities.
   b. Authentication and Authorization: Validate the identity of users and ensure they have the necessary permissions to perform authorized actions.
   c. Physical Security: Protect physical assets, such as data centers and servers, against unauthorized access, theft, or damage.
   d. Network Security: Safeguard networks against unauthorized access, malicious activities, and data breaches through firewalls, intrusion detection systems, and encryption mechanisms.
2. Change Management Controls:
   a. Change Authorization: Implement a structured process for reviewing, approving, and implementing changes to systems, applications, and configurations.
   b. Change Documentation: Maintain proper documentation of all changes, including the reason for the change, the individuals involved, and the date and time of the change.
   c. Testing and Validation: Perform appropriate testing and validation procedures to ensure that changes are implemented accurately and do not adversely impact financial reporting.
3. Data Integrity and Processing Controls:
   a. Data Validation and Accuracy: Implement controls to ensure the accuracy, completeness, and integrity of financial data throughout the processing and reporting cycles.
   b. Error Handling and Exception Reporting: Establish procedures for identifying and resolving errors or exceptions encountered during data processing.
   c. Data Backup and Recovery: Maintain appropriate backup and recovery procedures to protect financial data and enable timely restoration in the event of system failures or data loss.
4. Compliance Controls:
   a. Regulatory Compliance: Ensure compliance with relevant laws, regulations, and industry-specific standards that impact financial reporting, such as Sarbanes-Oxley Act (SOX) requirements.
   b. Internal Policies and Procedures: Establish and enforce internal policies and procedures that govern financial reporting processes, ensuring adherence to established guidelines and standards.
   c. Audit Trail and Monitoring: Implement mechanisms to capture and retain an audit trail of activities, including system logs, user activity logs, and change logs, to facilitate monitoring and forensic investigations.
5. Service Continuity and Availability:
   a. Business Continuity Planning: Develop and maintain a comprehensive business continuity plan to mitigate risks and ensure timely resumption of critical operations in the event of disruptions.
   b. Redundancy and Failover: Implement redundant systems, failover mechanisms, and backup infrastructure to ensure continuous availability of services.
   c. Incident Response: Establish protocols and procedures to promptly respond to and manage security incidents or disruptions.

It's important to note that the control objectives can vary based on the specific industry, regulatory requirements, and client expectations. The service organization and the auditor should work together to define the appropriate control objectives for the audit engagement, considering the organization's unique circumstances and risks.

### COBIT Control Objectives

COBIT (Control Objectives for Information and Related Technologies) provides a framework for IT governance and management. While COBIT does not prescribe specific control objectives, it offers a set of high-level control objectives organized into domains and processes. Here are the standard COBIT control objectives organized by domain:

1. Evaluate, Direct, and Monitor (EDM) Domain:

   - EDM01: Ensure Governance Framework Setting and Maintenance.
   - EDM02: Ensure Benefits Delivery.
   - EDM03: Ensure Risk Optimization.
   - EDM04: Ensure Resource Optimization.
   - EDM05: Ensure Stakeholder Transparency.
2. Align, Plan, and Organize (APO) Domain:

   - APO01: Manage the IT Management Framework.
   - APO02: Manage Strategy.
   - APO03: Manage Enterprise Architecture.
   - APO04: Manage Innovation.
   - APO05: Manage Portfolio.
   - APO06: Manage Budget and Costs.
   - APO07: Manage Human Resources.
   - APO08: Manage Relationships.
   - APO09: Manage Service Agreements.
3. Build, Acquire, and Implement (BAI) Domain:

   - BAI01: Manage Programs and Projects.
   - BAI02: Manage Requirements Definition.
   - BAI03: Manage Solutions Identification and Build.
   - BAI04: Manage Availability and Capacity.
   - BAI05: Ensure Systems Security.
   - BAI06: Manage Changes.
   - BAI07: Manage Change Acceptance and Transitioning.
   - BAI08: Manage Knowledge.
   - BAI09: Manage Assets.
   - BAI10: Manage Configuration.
4. Deliver, Service, and Support (DSS) Domain:

   - DSS01: Manage Operations.
   - DSS02: Manage Service Requests and Incidents.
   - DSS03: Manage Problems.
   - DSS04: Manage Continuity.
   - DSS05: Manage Security Services.
   - DSS06: Manage Business Process Controls.
   - DSS07: Manage Data.
   - DSS08: Manage Facilities.
5. Monitor, Evaluate, and Assess (MEA) Domain:

   - MEA01: Monitor, Evaluate, and Assess Performance and Conformance.
   - MEA02: Monitor, Evaluate, and Assess System of Internal Control.
   - MEA03: Monitor, Evaluate, and Assess Compliance with External Requirements.
   - MEA04: Provide Assurance of IT Governance.

These control objectives provide a framework for organizations to define specific control activities and measures based on their unique requirements, risks, and regulatory environment. Organizations should tailor and adapt the COBIT control objectives to their specific circumstances to effectively manage and govern their IT functions.

It's important to note that the control objectives can evolve with changes in technology, industry standards, and regulations. Therefore, staying updated with the latest version of COBIT and relevant industry guidance is crucial for organizations implementing COBIT control objectives.

## PCAOB Auditing Standards

See [https://pcaobus.org/oversight/standards/auditing-standards](https://pcaobus.org/oversight/standards/auditing-standards)

## GAO Financial Audit Manual

* [Financial Audit Manual - Volume 1](assets/gao-22-105894.pdf)
* [Financial Audit Manual - Volume 2](assets/gao-22-105895.pdf)
* [Financial Audit Manual - Volume 3](assets/gao-21-105127.pdf)
