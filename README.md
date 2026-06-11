# PrestaShop Security Assessment and Hardening

## Overview

This project documents the deployment, security assessment, hardening, and validation of a Dockerized PrestaShop e-commerce application.

The objective was to evaluate the application's security posture by identifying vulnerabilities, implementing defensive controls, and validating remediation effectiveness.

## Skills Demonstrated

- Web Application Security
- Vulnerability Assessment
- Docker Deployment
- Linux Administration
- Security Hardening
- Apache Configuration
- WAF Development
- Security Validation
- Technical Documentation

## Environment

- Kali Linux
- Docker
- PrestaShop
- MySQL
- Apache
- Nikto

## Findings

| Finding | Risk |
|----------|----------|
| Missing X-Frame-Options | Medium |
| Missing X-Content-Type-Options | Medium |
| INSTALL.txt Exposure | Low |
| robots.txt Disclosure | Low |

## Mitigations

- Implemented X-Frame-Options
- Implemented X-Content-Type-Options
- Added Content Security Policy
- Added Referrer Policy
- Created ModSecurity-compatible WAF Rules

## Validation

Validation was performed using:

```bash
curl -I http://localhost:8080
```

The implemented controls were successfully verified.

## Repository Contents

- Reports
- Screenshots
- WAF Rule File
- Security Assessment Documentation

## Lessons Learned

This project demonstrated the importance of:

- Secure deployment practices
- Vulnerability identification
- Risk assessment
- Defensive security controls
- Validation and documentation
