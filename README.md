# PrestaShop Security Assessment and Hardening

This project documents the deployment, security assessment, attack simulation, hardening, and validation of a Dockerized PrestaShop e-commerce application.

The objective was to evaluate the application's security posture by identifying vulnerabilities, validating security findings, implementing defensive controls, and verifying the effectiveness of those controls.

## Key Activities

- Deployed PrestaShop using Docker and MySQL
- Conducted vulnerability assessment using Nikto
- Identified clickjacking and information disclosure risks
- Validated findings through manual testing
- Implemented Apache security headers
- Developed ModSecurity-compatible WAF rules
- Performed post-remediation security validation
- Produced security assessment and attack simulation reports

## Technologies Used

- Kali Linux
- Docker
- PrestaShop
- Apache
- MySQL
- Nikto
- ModSecurity (Rule Development)

## Key Findings

- Missing X-Frame-Options Header
- Missing X-Content-Type-Options Header
- INSTALL.txt Information Disclosure
- robots.txt Information Disclosure

## Security Improvements

- X-Frame-Options: DENY
- X-Content-Type-Options: nosniff
- Content-Security-Policy (CSP)
- Referrer-Policy
- Custom WAF Rules

This project demonstrates the complete application security lifecycle: deployment, assessment, attack simulation, remediation, validation, and documentation.
