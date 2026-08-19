# Risk Assessment Methodology

## Purpose

This document explains how Stark Industries Inc. identifies, analyses, and evaluates information security risks within the ISMS.

The aim is to use the same method for each risk so that risks can be compared and treated consistently.

## Scope

The risk assessment applies to information assets, personnel, systems, and operations within the ISMS scope supporting the development, deployment, and maintenance of the SaaS marketing platform.

## Risk Assessment Process

Stark Industries follows six main steps:

1. Identify the asset.
2. Identify relevant threats and vulnerabilities.
3. Assess likelihood.
4. Assess impact.
5. Calculate and evaluate the risk.
6. Assign a risk owner and document the result.

## Asset Identification

The assessment starts with the assets recorded in the asset inventory.

Assets considered may include:

- source code repositories;
- CI/CD pipelines;
- AWS EC2 and S3 infrastructure;
- employee laptops; and
- company or application data.

Each asset is reviewed for threats and vulnerabilities that could affect confidentiality, integrity, or availability.

## Threat and Vulnerability Identification

Threats and vulnerabilities are considered using sources such as:

- OWASP Top 10;
- NIST SP 800-30;
- industry threat intelligence; and
- internal incident history.

The purpose is to identify realistic situations that could affect an asset rather than creating risks without a clear link to the environment.

## Likelihood Rating

Likelihood represents how likely it is that a risk event could occur.

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | May occur only in exceptional circumstances |
| 2 | Unlikely | Not expected, but still possible |
| 3 | Possible | Could occur at some point |
| 4 | Likely | Expected to occur occasionally |
| 5 | Almost Certain | Expected to occur frequently |

## Impact Rating

Impact represents the level of damage or disruption that could result if the risk occurs.

| Score | Rating | Description |
|---|---|---|
| 1 | Negligible | No significant disruption or damage |
| 2 | Minor | Minor disruption or limited financial or reputational impact |
| 3 | Moderate | Noticeable impact requiring management attention |
| 4 | Major | Serious impact on operations, finances, or compliance |
| 5 | Severe | Critical impact, regulatory breach, or long-term damage |

## Risk Calculation

Risk is calculated using:

**Risk Score = Likelihood × Impact**

The maximum possible score is 25.

For example:

Likelihood = 4  
Impact = 5

Risk Score = 4 × 5 = 20

## Risk Evaluation

| Risk Score | Risk Level | Required Action |
|---|---|---|
| 1–6 | Low | Acceptable risk; monitor |
| 7–14 | Medium | Treatment or mitigation may be required depending on the context |
| 15–25 | High | Unacceptable risk; treatment is required |

## Risk Acceptance

Low risks are generally accepted with monitoring.

Medium risks require business justification or partial mitigation depending on the circumstances.

High risks must be treated or formally accepted by senior management.

## Risk Ownership

Each risk is assigned to a Risk Owner.

The Risk Owner is normally the person responsible for the affected asset or business process.

The Risk Owner is responsible for:

- reviewing the risk assessment;
- confirming that the assessment is reasonable; and
- supporting any required risk treatment.

## Review Frequency

Risk assessments are reviewed:

- at least once a year;
- when significant changes are made to systems or processes;
- when the threat environment changes; and
- before internal audits and management reviews where updates are required.

## Outputs

The risk assessment process produces or updates:

- Risk Register;
- Risk Assessment Report;
- Asset Inventory;
- Risk Treatment Plan input; and
- Statement of Applicability input.