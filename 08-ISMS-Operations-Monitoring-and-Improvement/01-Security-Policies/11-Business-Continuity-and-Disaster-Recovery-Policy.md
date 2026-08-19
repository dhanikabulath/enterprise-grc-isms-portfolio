# Business Continuity and Disaster Recovery Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines how Stark Industries maintains critical business operations and restores systems following disruptive incidents.

## Scope

The policy applies to critical systems, personnel, processes, and third-party services within the ISMS scope, including:

- the SaaS platform;
- AWS infrastructure;
- code repositories; and
- internal operations.

## Key Definitions

**Business Continuity** – Maintaining essential business functions during disruption.

**Disaster Recovery** – Restoring IT systems and infrastructure following disruption.

**RTO** – Maximum acceptable time to restore a system.

**RPO** – Maximum acceptable amount of data loss measured in time.

## Critical Systems

| Function | System | RTO | RPO |
|---|---|---:|---:|
| SaaS Platform Availability | AWS EC2 / RDS | 4 hours | 15 minutes |
| Source Code Repositories | GitHub | 24 hours | 1 hour |
| Internal Communication | Slack / Email | 8 hours | 1 hour |
| Customer Support | CRM / Ticketing Tool | 8 hours | 1 hour |

## Disaster Scenarios

The BC/DR process considers:

- AWS region failure;
- ransomware or malware;
- accidental deletion or insider sabotage;
- power or internet disruption; and
- loss of critical third-party services.

## Business Continuity Planning

Departments must identify:

- critical business processes;
- minimum staffing requirements; and
- workarounds for technology failures.

Remote-work capability should be maintained.

Communication trees are reviewed quarterly.

## Disaster Recovery

Backups must be:

- automated;
- encrypted;
- versioned;
- tested monthly; and
- retained for at least 90 days.

Infrastructure-as-code supports rapid rebuilding of cloud environments.

Disaster-recovery procedures should be stored offline and remain accessible to key personnel.

## Testing and Maintenance

The BC/DR plan is:

- reviewed annually;
- tested twice per year using simulations or failover exercises; and
- updated following significant incidents or organisational changes.

## Communication During Disruption

Internal communication uses Slack with SMS as a fallback.

Customer communications may include:

- email templates;
- FAQ updates; and
- an incident status page where available.

## Roles and Responsibilities

### CEO

Approves BC/DR strategy and emergency declarations.

### Information Security Manager

Maintains the BC/DR plan and coordinates response.

### IT Infrastructure Engineer

Performs technical recovery.

### Department Heads

Define and test departmental continuity arrangements.

### All Staff

Understand their assigned responsibilities during disruption.

## Policy Review

This policy is reviewed annually and after significant changes to the environment or regulatory requirements.