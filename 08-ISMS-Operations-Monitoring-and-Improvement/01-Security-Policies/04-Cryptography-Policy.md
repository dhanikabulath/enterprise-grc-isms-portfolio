# Cryptography Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy defines how Stark Industries uses cryptographic controls to protect the confidentiality, integrity, and authenticity of information across the SaaS platform and supporting systems.

## Scope

This policy applies to systems, services, employees, contractors, and third-party vendors that handle or transmit classified or sensitive information within the ISMS scope.

## Objectives

Stark Industries uses cryptography to:

- protect sensitive information;
- define consistent standards for encryption;
- manage cryptographic keys securely; and
- support applicable security and regulatory requirements.

## Cryptographic Use

### Data in Transit

Sensitive information transmitted across public or untrusted networks must be encrypted.

Stark Industries requires:

- TLS 1.2 or higher for supported services;
- encrypted API communications;
- encrypted transmission of sensitive information; and
- secure communication channels where confidential information is exchanged.

### Data at Rest

Sensitive information stored in databases, backups, and cloud storage must be encrypted.

AWS S3, EBS volumes, databases, and other relevant storage should use:

- AES-256; or
- an equivalent approved encryption standard.

### Authentication

Passwords must not be stored in plaintext.

Approved password hashing methods include:

- bcrypt; and
- Argon2.

### Code Signing and Integrity

Hashes and digital signatures should be used where required to verify the integrity and authenticity of software builds and updates.

## Key Management

### Key Generation

Cryptographic keys must be generated using approved algorithms and secure cryptographic libraries.

Random number generation used for cryptographic purposes must be cryptographically secure.

### Key Storage

Private keys and encryption keys must be stored securely.

Approved approaches include:

- hardware security modules; and
- managed key services such as AWS KMS.

Cryptographic keys must not be stored directly in source code or CI/CD pipelines.

### Key Distribution

Keys must only be transferred through secure and authenticated channels.

### Key Rotation and Expiry

Cryptographic keys should be rotated regularly.

Rotation is also required where compromise is suspected.

Expired or unused keys must be securely deleted or archived.

## Approved Cryptographic Standards

| Purpose | Minimum Requirement |
|---|---|
| TLS | TLS 1.2 or higher |
| Data at Rest | AES-256 |
| Password Hashing | bcrypt or Argon2 |
| Key Exchange | ECDHE or RSA ≥ 2048 bits |
| Digital Signatures | RSA ≥ 2048 bits or ECDSA |

## Monitoring and Review

Cryptographic controls are reviewed annually.

Records of key usage and rotation must be retained and available for review.

Violations of this policy may result in removal of access or disciplinary action.

## Exceptions

Exceptions must be:

- risk assessed;
- approved by the Information Security Manager; and
- documented with an appropriate mitigation plan.

## Roles and Responsibilities

### Information Security Manager

Responsible for enforcing cryptographic standards and policy compliance.

### Cyber Security GRC Analyst

Maintains documentation relating to cryptographic controls and supports audit activities.

### Developers

Implement approved cryptographic functions and must avoid creating custom cryptographic algorithms.

### Cloud / Infrastructure Engineer

Ensures encryption is properly configured at the infrastructure level.

## Policy Review

This policy is reviewed annually and when significant changes occur to the environment or regulatory requirements.

## ISO/IEC 27001:2022 Alignment

This policy supports:

- A.8.24 — Use of cryptography
- A.8.25 — Secure development lifecycle requirements related to key management
- A.8.26 — Application security requirements