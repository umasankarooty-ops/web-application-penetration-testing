# Web Application Penetration Testing

## Overview

This project documents an authorized web application security testing lab using an Azure Ubuntu VM, Damn Vulnerable Web Application (DVWA), Nikto, OWASP ZAP, and TryHackMe training rooms.

## Objectives

- Explore DVWA security levels: Low, Medium and High.
- Understand common OWASP Top 10 vulnerability categories.
- Perform automated scanning with Nikto and OWASP ZAP.
- Manually verify findings and identify false positives.
- Document testing methodology, evidence and remediation.

## Environment

- Cloud platform: Microsoft Azure
- Operating system: Ubuntu Server
- Vulnerable application: DVWA
- Server scanner: Nikto
- Application scanner: OWASP ZAP
- Training platform: TryHackMe

## Testing Methodology

1. Set up an isolated lab environment.
2. Complete the available DVWA challenges at each security level.
3. Record behavioral differences between security levels.
4. Run Nikto and OWASP ZAP against the authorized lab.
5. Manually validate scanner alerts.
6. Test input validation, sessions, file uploads and information disclosure.
7. Document confirmed findings and remediation recommendations.

## Results

Add actual findings, scanner comparison results, screenshots and challenge completion notes after testing.

## Safety

All testing is intended for authorized lab environments. DVWA is intentionally vulnerable and must not be exposed publicly. Do not commit passwords, private keys, session tokens or other secrets.

## Remediation

See `remediation/recommendations.md` for defensive guidance and corrective actions.
