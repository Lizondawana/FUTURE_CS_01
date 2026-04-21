# FUTURE_CS_01 — Vulnerability Assessment Report for a Live Website

## Overview
This repository contains my submission for **Task 1** of the **Future Interns Cyber Security Internship (2026)**. The task required a **read-only vulnerability assessment** of a public website using ethical, non-destructive techniques.

## Target Website
- **Website:** http://demo.testfire.net
- **Application:** Altoro Mutual banking demo

## Scope
This assessment was limited to **passive, read-only analysis** only. No active exploitation, brute forcing, denial-of-service, or destructive testing was performed.

## Tools Used
- **Nmap 7.99** — port and service discovery
- **OWASP ZAP 2.17.0** — passive web vulnerability analysis
- **Browser DevTools** — HTTP response header and cookie inspection
- **Canva** — professional report design

## Repository Contents
- `report/` — final report PDF
- `evidence/` — screenshots and supporting tool output
- `README.md` — project overview and methodology

## Key Findings Summary
The assessment identified multiple security issues, including:
- Potential SQL Injection
- Missing Anti-CSRF protection
- Missing Content Security Policy (CSP)
- Missing anti-clickjacking protection
- Insecure session cookie settings
- Server version disclosure
- Missing browser security headers

## Risk Summary
- **High:** 1
- **Medium:** 5
- **Low:** 5
- **Informational:** 2

## Methodology
1. Performed basic exposure analysis with Nmap
2. Reviewed the website using OWASP ZAP in a passive/read-only manner
3. Inspected response headers and cookies using Browser DevTools
4. Documented findings in business-friendly language
5. Provided remediation recommendations for each issue

## Notes
This assessment was conducted for educational purposes as part of the Future Interns Cyber Security Internship. The target site is an intentionally vulnerable demo environment.

## Author
- **Name:**Lizo Ndawana
- **CIN ID:** FIT/MAR26/CS7183

## Internship
Future Interns — Cyber Security Track
