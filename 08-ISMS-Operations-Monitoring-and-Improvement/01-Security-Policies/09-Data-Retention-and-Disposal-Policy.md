# Data Retention and Disposal Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines how long Stark Industries retains information and how information and media are securely disposed of when no longer required.

## Scope

The policy applies to digital and physical information across:

- AWS;
- developer tools;
- backups;
- employee devices;
- operational systems;
- logs;
- source code; and
- sensitive company information.

## Retention Schedule

| Data Type | Retention Period |
|---|---|
| Source Code | Indefinite |
| Application and Access Logs | 12 months |
| CI/CD Deployment Records | 12 months |
| Employee Records | 7 years |
| Vendor Contracts and NDAs | 7 years after expiry |
| Backup Data | 90-day rolling period |
| Security Incident Records | 3 years |
| Customer Support Data | 24 months |

## Digital Data Disposal

Before reuse or disposal, digital information must be securely deleted using methods such as:

- cryptographic wipe; or
- secure overwrite.

Cloud storage including S3, EBS, and RDS must use supported secure-deletion functions.

Backup snapshots are automatically deleted after the defined 90-day retention period.

## Physical Media Disposal

Physical media containing sensitive information must be destroyed before disposal.

Sensitive physical media must also be recorded where required.

## Cloud Decommissioning

When cloud systems are decommissioned:

- data remnants must be removed; and
- associated IAM permissions must be revoked.

## Roles and Responsibilities

### Data Owners

Set appropriate retention periods and approve deletion.

### IT Infrastructure Engineer

Performs secure deletion and cloud purge activities.

### Information Security Manager

Makes sure disposal records and reviews are maintained.

### Cyber Security GRC Analyst

Checks compliance with retention schedules and supports audits.

## Exceptions

Exceptions require documented justification and approval from the Information Security Manager.

## Policy Review

The policy is reviewed annually and after significant environmental or regulatory changes.