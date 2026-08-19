# Access Control Policy

**Organisation:** Stark Industries Inc.  
**Version:** 1.0  
**Owner:** Information Security Manager  
**Status:** Final  
**Review Frequency:** Annual  

## Purpose

This policy brings together the access-control requirements already defined across Stark Industries' ISMS policies.

The aim is to ensure that access to company systems, services, applications, and information is limited to authorised users and appropriate business purposes.

## Scope

This policy applies to employees, contractors, interns, third parties, and other authorised users who access Stark Industries systems or information.

It applies to:

- company laptops and endpoints;
- AWS cloud services;
- GitHub and development tools;
- CI/CD pipelines;
- SaaS platforms;
- internal systems and applications; and
- company information and data.

## Access Requirements

Users must:

- access only systems and information they are authorised to use;
- use company systems only for approved business purposes;
- follow password and MFA requirements;
- protect authentication credentials from disclosure;
- lock workstations when unattended; and
- report suspected unauthorised access or credential compromise.

Sharing credentials or using another person's account is prohibited.

## Access Based on Business Need

Access should be limited according to:

- job responsibilities;
- business need;
- information classification; and
- the sensitivity of the system or asset.

Sensitive and restricted information should only be available to authorised personnel.

## Privileged and Administrative Access

Administrative and privileged access must be restricted to authorised personnel who require it for their role.

Elevated access should be limited to the minimum level required to perform approved tasks.

Changes to permissions and privileged access should be logged and reviewed where appropriate.

## Cloud and Development Access

Access to AWS, GitHub, source code repositories, CI/CD pipelines, and production systems must be controlled.

Security requirements include:

- limiting repository and system permissions;
- protecting credentials and secrets;
- avoiding hardcoded credentials in source code;
- restricting access to production environments; and
- monitoring relevant access and permission changes.

## Third-Party Access

Third-party access must be controlled according to the supplier's role and level of risk.

Where suppliers require access to Stark Industries systems or information:

- access should be limited to what is required;
- appropriate contractual and security requirements should apply; and
- access must be removed when the relationship ends.

## Information Classification and Access

Access must reflect the classification of the information being handled.

Stark Industries uses the following classifications:

- Confidential
- Restricted
- Internal Use Only
- Public

Confidential and Restricted information must only be available to authorised personnel.

## Monitoring and Review

Access-related activity should be logged where appropriate.

This includes:

- successful and failed authentication attempts;
- user provisioning;
- permission changes;
- administrative access;
- production access; and
- relevant system or application changes.

Access and permissions should be reviewed as part of the ISMS monitoring process.

## Removal of Access

Access must be revoked when it is no longer required.

This includes:

- termination of employment or contracts;
- changes in job responsibilities;
- supplier offboarding; and
- removal of access to systems that are no longer needed.

## Responsibilities

Users are responsible for protecting their credentials and using access only for authorised purposes.

System and asset owners are responsible for making sure access is appropriate for the relevant system or information.

The Information Security Manager oversees access-control requirements as part of the ISMS.

## Review

This policy is reviewed annually and when significant changes occur to systems, roles, suppliers, or access requirements.

## Source Basis

This policy consolidates access-control requirements contained in Stark Industries' existing ISMS policies rather than replacing a standalone source policy.