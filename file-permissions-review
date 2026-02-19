# Sensitive File Permission Review

## /etc/passwd

Permissions:
-rw-r--r--

Ownership:
- Owner: root
- Group: root

Observation:
The file is world-readable, which is expected behavior. Password hashes are not stored in this file.

## /etc/shadow

Permissions:
-rw-r-----

Ownership:
- Owner: root
- Group: shadow

Observation:
Password hashes are stored in /etc/shadow and are properly restricted to privileged users only.

## Risk Assessment

No misconfiguration identified. Credential separation is correctly implemented.
