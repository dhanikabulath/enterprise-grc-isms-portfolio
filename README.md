# Stark Industries ISO 27001 ISMS

A hands-on GRC project where I built an Information Security Management System (ISMS) for **Stark Industries Inc.**, a fictional SaaS company operating a cloud-based platform on AWS.

The project follows the ISO/IEC 27001:2022 ISMS lifecycle, from defining the organisation and its scope through asset management, risk assessment, risk treatment, control selection, monitoring, internal audit, and continual improvement.

The main goal was to understand how these parts work together in practice rather than treating ISO 27001 as a collection of separate documents.

> **Note:** Stark Industries Inc. is a fictional organisation. This repository is a portfolio and learning project and does not represent a certified ISO 27001 implementation or a real-world audit.

---

## Project Overview

The ISMS covers the design, development, deployment, and maintenance of a cloud-based SaaS marketing platform.

The environment includes:

- AWS production infrastructure
- SaaS applications and supporting services
- GitHub and source code repositories
- CI/CD pipelines
- Employee endpoints
- Internal systems and tools
- Business and application data
- Relevant suppliers and third-party services

---

## Project Structure

| Lab | Area | Work Completed |
|---|---|---|
| **01** | ISMS Context & Scope | Organisational context, interested parties, ISMS boundaries and scope |
| **02** | Governance & Responsibilities | Information Security Policy, ISMS roles and responsibilities |
| **03** | Asset Management | Asset inventory, asset ownership and information classification |
| **04** | Risk Assessment Methodology | Likelihood and impact criteria, risk matrix and risk evaluation |
| **05** | Risk Register | Asset-based risks, threats, vulnerabilities, scoring and risk ownership |
| **06** | Risk Treatment | Treatment decisions, selected controls and residual risk |
| **07** | Statement of Applicability | ISO 27001:2022 Annex A control applicability and justification |
| **08** | ISMS Operations, Monitoring & Improvement | Security policies, objectives, competence, monitoring, audit, management review and corrective action |

```text
.
├── 01-ISMS-Context-and-Scope/
├── 02-Governance-and-Responsibilities/
├── 03-Asset-Inventory-and-Classification/
├── 04-Risk-Assessment-Methodology/
├── 05-Risk-Register/
├── 06-Risk-Treatment-Plan/
├── 07-Statement-of-Applicability/
├── 08-ISMS-Operations-Monitoring-and-Improvement/
└── README.md
```

---

## Risk Assessment & Treatment

I used an asset-based approach to identify and evaluate information security risks.

The basic workflow was:

```text
Asset
  ↓
Threat + Vulnerability
  ↓
Likelihood × Impact
  ↓
Risk Rating
  ↓
Treatment Decision
  ↓
Security Controls
  ↓
Residual Risk
```

Risk scores were calculated using:

**Risk Score = Likelihood × Impact**

The assessment uses a 5 × 5 scoring model:

| Score | Risk Level |
|---:|---|
| 1–6 | Low |
| 7–14 | Medium |
| 15–25 | High |

Identified risks were recorded in the Risk Register and assigned to risk owners before moving into the Risk Treatment Plan.

This gave me a clear link between the assets being protected, the risks affecting them, and the controls selected to reduce those risks.

---

## Statement of Applicability

I worked through the ISO/IEC 27001:2022 Annex A control set and documented control applicability through a Statement of Applicability.

The SoA records:

- Control number and title
- Control description
- Applicability
- Justification

Control decisions were considered alongside the organisation's risks, policies, assets, and operational requirements.

---

## Security Policies

The operational part of the ISMS includes policies covering:

- Acceptable Use
- Access Control
- Asset Management and Data Classification
- Cryptography
- Incident Management
- Monitoring and Logging
- Supplier and Vendor Management
- Secure Development
- Data Retention and Disposal
- Security Training and Awareness
- Business Continuity and Disaster Recovery

These policies were written around the Stark Industries environment rather than as generic policy templates.

---

## Monitoring & ISMS Improvement

The final stage of the project looks at how the ISMS would be maintained after the initial risk and control work.

This includes:

- Information security objectives
- Competence records
- Security KPIs
- Monitoring and measurement records
- Control evidence tracking
- Internal audit planning
- Management review
- Nonconformity tracking
- Corrective action

This part of the project helped connect control implementation with the evidence needed to review whether the ISMS is working as intended.

---

## Skills Demonstrated

### GRC & ISO 27001

- ISO/IEC 27001:2022
- ISMS documentation
- ISMS scope definition
- Information security governance
- Risk assessment
- Risk register development
- Risk treatment
- Statement of Applicability
- Security policy development
- Control evidence tracking
- Security metrics and KPIs
- Internal audit planning
- Management review
- Nonconformity and corrective action

### Security Governance

- Asset management and classification
- Access control
- Cryptography governance
- Incident management
- Vulnerability management
- Supplier risk management
- Secure development governance
- Security awareness
- Business continuity and disaster recovery

### Environment

- AWS
- GitHub
- CI/CD
- SaaS infrastructure
- Cloud security governance

---

## What I Learned

The biggest takeaway from this project was understanding the relationship between the different parts of an ISMS.

An asset does not sit separately from the risk register. A risk does not sit separately from the treatment plan. Treatment decisions lead to controls, and those controls need evidence showing whether they are actually operating as expected.

That evidence then feeds into monitoring, internal audit, management review, and corrective action.

Working through the process end-to-end gave me practical experience with the documentation and decision-making involved in an ISO 27001-based ISMS.

---

## Disclaimer

This repository was created for cybersecurity GRC learning and portfolio purposes.

**Stark Industries Inc. is a fictional organisation.** The project does not represent an ISO/IEC 27001 certification, a production ISMS implementation, or an audit performed for a real organisation.
