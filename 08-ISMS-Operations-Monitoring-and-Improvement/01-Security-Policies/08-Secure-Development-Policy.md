# Secure Development Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines the security requirements for software developed, maintained, or deployed by Stark Industries.

Security should be considered throughout the software development lifecycle rather than only after development is complete.

## Scope

This policy applies to:

- backend systems;
- APIs;
- SaaS applications;
- administration dashboards;
- CI/CD pipelines; and
- integration scripts.

## Design Phase

For major releases or new systems:

- threat modelling must be performed;
- security requirements must be documented alongside functional requirements; and
- secure and established libraries should be reused where appropriate.

## Development Phase

Developers must:

- follow secure coding standards;
- consider OWASP secure coding guidance;
- use static code analysis in the CI/CD process;
- never hardcode credentials or secrets; and
- check third-party libraries for vulnerabilities.

## Security Testing

Before production release, appropriate testing must include:

- SAST;
- DAST; and
- manual code reviews for critical components.

Production information must not be used as test data in non-production environments.

## Deployment and Maintenance

All deployments must go through a peer-reviewed pull request process.

Infrastructure-as-code should be reviewed for configuration weaknesses.

Post-deployment monitoring must be available for major releases.

## Developer Training

Developers must complete secure-coding training annually.

New developers must complete required training within 30 days of joining.

## Open-Source Software

Third-party dependencies must:

- be managed using appropriate dependency-management tools;
- be checked regularly for CVEs or significant vulnerabilities; and
- be updated or replaced when vulnerabilities are identified.

## CI/CD Controls

Secrets must be stored using environment variables or approved secrets-management tools such as AWS Secrets Manager.

CI/CD pipelines must include:

- access control;
- audit logging; and
- pre-deployment validation.

## Vulnerability Management

Security vulnerabilities must be:

- recorded in an internal issue tracker;
- assigned to a developer;
- prioritised based on severity; and
- re-tested after remediation.

Critical vulnerabilities must be remediated within five business days.

## Roles and Responsibilities

### Software Developers

Follow secure coding requirements and participate in code reviews.

### Product Owners

Define security requirements and ensure they are included in product delivery.

### Information Security Manager

Oversees implementation of this policy and secure-development training.

## Exceptions

Exceptions require documentation, approval from the Information Security Manager, and appropriate alternative controls.

## Policy Review

This policy is reviewed annually and after significant changes.

## ISO/IEC 27001:2022 Alignment

This policy supports Annex A controls A.8.25 through A.8.29.