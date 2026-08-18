# Organization Context

## Company Overview

Stark Industries Inc. is a small technology company that develops and operates a cloud-based SaaS marketing platform for small and medium-sized businesses.

The platform is developed and managed by an internal team and hosted mainly on AWS. The company also relies on services such as GitHub and other SaaS tools for software development and day-to-day operations.

For this portfolio project, Stark Industries is a fictional company used to demonstrate how I would build and maintain an Information Security Management System (ISMS) based on ISO/IEC 27001:2022.

## Business Activities

The main activities relevant to the ISMS are:

- developing and maintaining the SaaS platform;
- managing the AWS cloud environment;
- managing application deployments and the CI/CD pipeline;
- maintaining source code in GitHub;
- supporting customers and the production service;
- managing employee laptops and user access;
- monitoring systems and security events; and
- managing suppliers that support the SaaS platform.

## Internal Issues

### Small team

Stark Industries operates with a relatively small team. Security responsibilities may therefore be shared between employees rather than handled by a large dedicated security department.

This creates a need for clear ownership of security tasks and risks.

### Limited security budget

The company has limited resources available for security tools, training, testing, and other improvements.

Security controls therefore need to be selected based on risk and business priorities.

### Cloud-based operations

Most of the company's important systems are cloud based. AWS hosts the production environment, while services such as GitHub support software development.

Configuration errors, excessive permissions, exposed credentials, or cloud service outages could affect the security or availability of the SaaS platform.

### Software development

The SaaS platform is regularly changed and updated.

Weak development practices could introduce vulnerabilities into production, so secure coding, code review, testing, and controlled deployment are important parts of the ISMS.

### Dependence on key personnel

Some systems and processes may depend on a small number of technical employees.

This could create problems if an employee leaves the company or is unavailable during an incident.

## External Issues

### Cyber threats

As an internet-facing SaaS provider, Stark Industries is exposed to threats such as phishing, credential theft, malware, exploitation of application vulnerabilities, and attacks against cloud services.

### Customer security expectations

Customers expect the SaaS platform to be secure, reliable, and available.

A serious security incident or extended outage could affect customer trust and the company's reputation.

### Third-party services

Stark Industries depends on external providers such as AWS, GitHub, and other SaaS suppliers.

A security incident or service failure affecting one of these providers could also affect Stark Industries.

### Changing vulnerabilities and technology

The threat landscape changes regularly. New vulnerabilities may affect operating systems, software libraries, cloud services, and applications used by the company.

The company therefore needs to review its risks and controls as the environment changes.

## ISMS Approach

Stark Industries uses an ISO/IEC 27001:2022-based ISMS to manage information security in a structured way.

The ISMS is intended to help the company:

- identify important information assets;
- understand security threats and vulnerabilities;
- assess and prioritise risks;
- select appropriate security controls;
- assign security responsibilities;
- monitor whether controls are working;
- respond to incidents and weaknesses; and
- improve security over time.

The ISMS focuses on protecting the confidentiality, integrity, and availability of information and systems supporting the SaaS platform.