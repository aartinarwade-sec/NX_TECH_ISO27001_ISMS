# NX Technologies – ISO/IEC 27001:2022 ISMS Implementation

> **Note:** NX Technologies is a **fictional company**. Everything in this repository is a sample created for learning and portfolio purposes only.

A documentation set for implementing an Information Security Management System (ISMS) aligned with **ISO/IEC 27001:2022**, written for a fictional Mumbai-based technology services firm that provides information security training, advisory and managed IT/cybersecurity services.

The project walks through the path from planning to risk treatment: defining the project, understanding the organization and setting the ISMS scope, establishing the policy framework, and assessing and treating information security risks.

## Repository structure

```
.
├── 01-Planning/
├── 02-Scope-and-Governance/
├── 03-Risk-Management/
└── 04-Controls/
```

The Word documents are provided as an editable **.docx** and a **.pdf** copy that renders directly in the browser on GitHub. The workbook and the Statement of Applicability are spreadsheets.

## Document index

| Folder | Document | ISO 27001:2022 relevance | Files |
| --- | --- | --- | --- |
| 01-Planning | **Project Plan** – objectives, scope, deliverables, roles, 13-month timeline, resources, budget, project risks, communication, training and monitoring | Clause 5.1 (leadership and commitment), Clause 7.1 (resources) | [PDF](01-Planning/Project_Plan.pdf) · [DOCX](01-Planning/Project_Plan.docx) |
| 02-Scope-and-Governance | **ISMS Scope and Context Document** – organizational context, internal/external issues, interested parties, legal and regulatory requirements, security objectives, scope boundaries and exclusions | Clauses 4.1, 4.2, 4.3 | [PDF](02-Scope-and-Governance/ISMS_Scope_and_Context_Document.pdf) · [DOCX](02-Scope-and-Governance/ISMS_Scope_and_Context_Document.docx) |
| 02-Scope-and-Governance | **Information Security Policy** – roles and responsibilities, policy statements, compliance, exceptions, review | Clause 5.2, Annex A 5.1 | [PDF](02-Scope-and-Governance/Information_Security_Policy.pdf) · [DOCX](02-Scope-and-Governance/Information_Security_Policy.docx) |
| 03-Risk-Management | **Risk Assessment and Risk Treatment Process** – methodology, 5x5 scoring and heat map, risk appetite, risk register and risk treatment plan | Clauses 6.1.2, 6.1.3, 8.2, 8.3 | [PDF](03-Risk-Management/Risk_Assessment_and_Risk_Treatment_Process.pdf) · [DOCX](03-Risk-Management/Risk_Assessment_and_Risk_Treatment_Process.docx) |
| 03-Risk-Management | **Risk Assessment Report** – asset-based assessment of six in-scope assets with scores and treatment decisions | Clauses 6.1.2, 8.2 | [PDF](03-Risk-Management/Risk_Assessment_Report.pdf) · [DOCX](03-Risk-Management/Risk_Assessment_Report.docx) |
| 03-Risk-Management | **NX Tech Risk Workbook** – risk register, asset register, risk treatment and key risk indicators (KRIs) | Clauses 6.1.2, 6.1.3, 8.2, 8.3, 9.1 | [XLSX](03-Risk-Management/NX_Tech_Risk_Workbook.xlsx) |
| 04-Controls | **Statement of Applicability (SoA)** – applicability and implementation status of the Annex A controls | Clause 6.1.3 d, Annex A | [SoA](04-Controls/Statement_of_Applicability.xlsx) |

## Scope at a glance

- **Organization:** NX Technologies (fictional), headquartered in Mumbai, India
- **Standard:** ISO/IEC 27001:2022
- **In scope:** Mumbai headquarters operations; IT, HR, Finance, Operations and other departments handling sensitive information; consulting, training and managed services; website, cloud CRM, Google Workspace, employee laptops, third-party applications and cloud infrastructure
- **Regulatory context:** DPDP Act 2023, IT Act 2000, GDPR (for international clients)
- **Supporting records:** risk register, asset register, risk treatment and KRIs in the risk workbook; Annex A controls in the Statement of Applicability
- **Certification target:** Month 13 of the project (November 2027)

## Risk assessment snapshot

Six risks were assessed on a 5x5 likelihood and impact scale (High 15-25, Medium 7-14, Low 1-6). Five are treated with **Reduce**; R-05 uses **Reduce / Transfer** (supplier SLA review plus business interruption cover).

| ID | Asset | Risk | Score |
| --- | --- | --- | --- |
| R-01 | Web server (hosted externally) | Unauthorized access to customer data on the website | 20 (High) |
| R-02 | Cloud-based CRM | Customer data stolen from the CRM | 20 (High) |
| R-03 | Employee laptops | Lost or stolen laptop exposes data | 12 (Medium) |
| R-04 | Google Workspace | Phishing leads to email account takeover | 9 (Medium) |
| R-05 | Third-party applications | Third-party application outage | 9 (Medium) |
| R-06 | Cloud infrastructure and storage | Unauthorized access to cloud-stored sensitive information | 20 (High) |

## Document status

| Document | Version | Approval status |
| --- | --- | --- |
| Project Plan | 1 | Signed (27/10/26) |
| ISMS Scope and Context Document | 1.0 | Signed (20/01/27) |
| Information Security Policy | 1.0 | Pending |
| Risk Assessment and Risk Treatment Process | 1.0 | Pending |
| Risk Assessment Report | 1.0 | Pending |

## Author

Aarti Narwade

## Disclaimer

This is a learning and portfolio project. NX Technologies, its people, systems and risks are fictional. The documents are not a certified ISMS and are not legal or compliance advice.
