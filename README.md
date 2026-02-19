# Linux Security Audit Project
![Platform](https://img.shields.io/badge/Platform-Ubuntu_ARM64-orange)
![Focus](https://img.shields.io/badge/Type-Security_Audit-blue)
![Status](https://img.shields.io/badge/Remediation-Implemented-success)
## Project Overview
This project documents a structured security audit of a simulated Ubuntu Linux system deployed in a virtualized environment. The objective was to evaluate system security posture, identify misconfigurations, and recommend hardening measures aligned with industry best practices. The assessment identified configuration weaknesses affecting privilege management and network exposure. Remediation actions were implemented to reduce overall system risk.

## Environment
- Host System: Apple Silicon (M4)
- Virtualization Platform: Oracle VirtualBox
- Guest Operating System: Ubuntu ARM64
- Deployment Type: Simulated non-production environment

## Audit Scope
The assessment focused on:

- User and privilege management
- Password and authentication policies
- Network service exposure
- Firewall configuration
- Logging and monitoring
- File system permissions and system hardening

## Methodology
The audit leveraged native Linux administrative utilities to enumerate system configuration, validate security controls, and identify misconfigurations. Findings were documented, risk-rated based on impact and likelihood, and remediated where appropriate.

## Remediation Status
- Host firewall enabled with default deny inbound policy
- Unnecessary service exposure reviewed and restricted
- Firewall configuration validated post-implementation
- Risk ratings documented and formal recommendations provided

## Skills Demonstrated
- Linux security auditing and system enumeration
- Privilege and access control analysis
- Authentication and password policy assessment
- Network service exposure analysis
- Log and authentication monitoring review
- Risk identification, rating, and remediation
- Technical reporting and documentation

