# Logging & Monitoring Review

## Log Directory Permissions

The /var/log directory contains system and service logs with appropriate ownership and permission structures.

## Authentication Log Review

The authentication log (/var/log/auth.log) is configured with the following permissions:

-rw-r-----

Ownership:
- Owner: syslog
- Group: adm

## Risk Assessment

Authentication logs are not world-readable, limiting unauthorized visibility into login attempts and system authentication activity.

## Observation

Log file permissions align with standard Linux security practices.
