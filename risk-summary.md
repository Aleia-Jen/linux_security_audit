# Risk Summary

## Executive Overview

This security audit evaluated system configuration, access controls, authentication policies, network exposure, and logging practices on a simulated Ubuntu Linux environment.

While core system protections were properly configured, several hardening opportunities were identified.

---

## Findings Overview

| Category | Finding | Risk Level | Status |
|-----------|----------|------------|---------|
| Privileged Access | Primary user has full sudo privileges | Medium | Observed |
| Password Policy | Password expiration effectively disabled (PASS_MAX_DAYS = 99999) | Medium | Observed |
| Host Firewall | UFW installed but inactive | Medium | Observed |
| Log Protection | Authentication logs properly restricted | Low (Strength) | Secure |
| Credential Separation | /etc/shadow properly protected | Low (Strength) | Secure |

---

## Risk Rating Methodology

Risk levels were assigned based on:

- Potential impact if exploited
- Likelihood in default configuration
- Exposure scope
- Alignment with enterprise security baselines

---

## Overall Assessment

The system is securely configured at the core operating system level, with proper credential separation and restricted log access. However, several default configurations reduce hardening posture when evaluated against enterprise security standards.

Primary improvement areas include:

- Enabling host-based firewall enforcement
- Implementing password expiration controls
- Applying least privilege principles to administrative access
