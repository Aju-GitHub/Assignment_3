# Cybersecurity Assignment_3 (Hack Yourself)

This repository contains a detailed penetration testing exercise on the deliberately insecure web application Hack Yourself First, on behalf of my Certified Cyber Security Analyst course from ICT Academy of Kerala. The main objective is to identify, analyze, and exploit common web application vulnerabilities, including SQL Injection (SQLi), Cross-Site Scripting (XSS), and Access Control weaknesses.

**Repository Structure:**

Hack_Your_Self_Assignment_3/

/- Assignment_3_Hack_Yourself.pdf - Contains main PDF

/- README.md                      - Documentation

# Key Objectives

- Understand and exploit SQL Injection vulnerabilities.

- Analyze reflective and stored XSS attacks.

- Identify access control misconfigurations and privilege escalation opportunities.

- Document findings, payloads, and mitigation recommendations.

# Tools & Environment

- Burp Suite Community Edition

- Mozilla Firefox (with proxy configuration)

- Burp Embedded Browser

- Kali Linux tools for payload crafting

- HTTPS interception with Burp Certificate installed

- Note: Burp Suite Repeater “Render” section was unavailable; testing was performed via Burp’s embedded browser.

# Vulnerabilities Explored

1. SQL Injection (SQLi)

- Exploited user input on “Cars By Cylinders” page.

- Discovered unsanitized backend input leading to exposure of sensitive user data.

3. Cross-Site Scripting (XSS)

- Tested search fields, login, registration, and commenting sections.

- Reflected XSS blocked via input sanitization and WAF.

- Stored XSS observed in existing comments/votes.

4. Access Control Misconfiguration

- Explored hidden directories via robots.txt.

- Discovered publicly accessible admin endpoints.

- Demonstrated role tampering to escalate privileges and access admin panel.

# Observations & Learnings

- Importance of input validation, output encoding, and parameterized queries.

- The critical role of access control and session management.

- How deliberate insecure applications can be used to practice ethical hacking skills safely.

**Rights and Usage:**

All reports, documentation, and related artifacts are the intellectual property of Ajmal M S.

Shared resources are provided solely as a record of my involvement, competencies, and learning outcomes.

No content from this repository may be copied, altered, shared, or reused without explicit permission.

© Ajmal M S, 2025
