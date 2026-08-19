# Incident Management Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines how Stark Industries detects, reports, assesses, responds to, and recovers from information security incidents.

## Scope

This policy applies to employees, contractors, third-party vendors, and systems within the ISMS scope, including AWS infrastructure, production systems, developer tools, and endpoint devices.

## Incident Definitions

**Security Event** – An observable event, such as an alert or log entry, that may indicate a security issue.

**Incident** – An event that has or may affect the confidentiality, integrity, or availability of information or systems.

**Major Incident** – An incident that significantly disrupts operations, affects multiple users, or may result in legal or regulatory consequences.

## Incident Reporting

Security incidents must be reported through:

- `security@starkindustries.com`; or
- the internal `#security-incidents` Slack channel.

Reports should include:

- description of the issue;
- time and location;
- affected systems or users; and
- known actions already taken.

## Incident Response Process

### Detection

Identify suspicious activity through logs, alerts, and user reports.

### Assessment

Validate the event and classify the incident as Low, Medium, High, or Critical.

### Containment

Isolate affected systems, accounts, or services.

### Eradication

Remove the cause of the incident, such as malware, vulnerabilities, or compromised access.

### Recovery

Restore affected systems to a secure operating state.

### Notification

Notify relevant internal stakeholders, customers, or regulators where required.

### Lessons Learned

Conduct a post-incident review and update controls where necessary.

## Severity Classification

| Level | Description |
|---|---|
| Low | Minimal impact with no customer effect |
| Medium | Limited disruption affecting some users or internal systems |
| High | Customer-facing impact or possible confidential-data breach |
| Critical | Severe compromise, regulatory impact, or widespread outage |

## Evidence Handling

Incident-related logs must be preserved.

Screenshots, network captures, and audit trails should be stored in a restricted-access evidence location.

## Training and Testing

All staff must complete incident-reporting awareness training annually.

Technical teams should participate in tabletop exercises or incident simulations every 12 months.

Incident response procedures must be tested at least annually.

Major incidents require a post-incident report covering root cause, corrective action, and any required ISMS control updates.

## Roles and Responsibilities

### All Users

Report suspected incidents immediately.

### Information Security Analyst

Leads technical response and evidence collection.

### Information Security Manager

Approves severity classification, coordinates escalation, and makes sure response plans are tested.

### Cyber Security GRC Analyst

Maintains the incident register and supports post-incident reviews.

## Exceptions

Exceptions must be documented, approved by the Information Security Manager, and supported by alternative controls where possible.

## Policy Review

This policy is reviewed annually and after significant environmental or regulatory changes.