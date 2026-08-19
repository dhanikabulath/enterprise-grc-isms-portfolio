# Monitoring and Logging Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines how Stark Industries monitors systems and protects security logs so that suspicious or unauthorised activity can be detected and investigated.

## Scope

This policy applies to:

- AWS environments;
- internal systems;
- endpoints;
- the SaaS platform;
- administration tools;
- GitHub Actions; and
- CI/CD pipelines.

## Objectives

Stark Industries uses monitoring and logging to:

- detect security incidents and policy violations;
- preserve forensic evidence; and
- support audit, contractual, and regulatory requirements.

## Logging Requirements

The following activity must be logged where applicable:

### Authentication Events

- successful login attempts;
- failed login attempts; and
- MFA bypass events.

### System Changes

- user provisioning;
- permission changes; and
- deployments.

### Network Activity

- firewall changes;
- VPN connections; and
- AWS Security Group changes.

### Application Activity

- source-code pushes;
- build failures; and
- administrative production access.

### Incident Indicators

- anomalous behaviour;
- IDS/WAF alerts; and
- brute-force attempts.

## Log Retention and Storage

Logs must be retained for at least 12 months.

Logs should be stored in a secure centralised system such as:

- AWS CloudWatch; or
- a SIEM platform.

Critical log backups must be encrypted and stored separately.

## Log Protection

Logs must be protected from unauthorised modification or deletion.

Controls include:

- role-based access control;
- restricted access;
- immutable storage where appropriate; and
- documented approval before logs are modified or deleted.

## Monitoring

Automated log reviews are performed daily for key systems and security events.

Alerts should be generated for:

- failed login attempts;
- access to sensitive information;
- unusual network traffic; and
- deployment activity outside approved hours.

Continuous monitoring covers:

- SaaS application health;
- cloud-infrastructure changes; and
- IAM misuse or privilege escalation.

Critical alerts must be escalated to the Information Security Manager within one hour.

## Incident Integration

Suspicious log activity must be escalated according to the Incident Management Policy.

Logs may be retained as investigation and post-incident evidence.

## Roles and Responsibilities

### Information Security Analyst

Triages alerts and performs regular log reviews.

### IT Infrastructure Engineer

Ensures logging agents and related infrastructure are working.

### Cyber Security GRC Analyst

Checks log-retention and review compliance.

### Information Security Manager

Oversees monitoring requirements and approves exceptions.

## Review and Audit

Quarterly internal reviews cover:

- log integrity;
- completeness of reviews; and
- alerting thresholds.

## Exceptions

Exceptions require documented justification and approval from the Information Security Manager.

## Policy Review

This policy is reviewed annually and following significant environmental or regulatory changes.