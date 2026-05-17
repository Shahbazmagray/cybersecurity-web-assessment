# cybersecurity-web-assessment
Beginner-level web application security assessment performed on OWASP Juice Shop using Kali Linux and OWASP ZAP.
# Cybersecurity Web Application Assessment

## Overview

This repository contains a beginner-level cybersecurity assessment performed on the OWASP Juice Shop web application. The assessment was conducted as part of a cybersecurity internship task using Kali Linux and OWASP ZAP.

---

## Objectives

* Understand the structure of a web application
* Perform vulnerability assessment
* Test for common web vulnerabilities
* Use OWASP ZAP for automated scanning
* Document findings and recommendations

---

## Application Tested

OWASP Juice Shop

---

## Tools Used

* Kali Linux
* OWASP ZAP
* Browser Developer Tools
* Node.js & npm
* OWASP Juice Shop

---

## Security Testing Performed

### Manual Testing

* Cross-Site Scripting (XSS)
* SQL Injection Testing
* Input Validation Testing

### Automated Testing

* OWASP ZAP Automatic Scan
* Security Header Analysis
* Information Disclosure Detection

---

## Vulnerabilities Identified

* Content Security Policy (CSP) Header Not Set
* Missing Anti-clickjacking Header
* X-Content-Type-Options Header Missing
* Information Disclosure
* Session ID in URL Rewrite
* Private IP Disclosure

---

## Example XSS Payload Tested

```html
<iframe src="javascript:alert(1)">
```

---

## Screenshots

The repository includes screenshots of:

* OWASP Juice Shop homepage
* XSS payload testing
* SQL injection testing
* OWASP ZAP scan results
* Vulnerability alerts

---

## Learning Outcomes

This project helped develop practical understanding of:

* Web application vulnerability assessment
* OWASP Top 10 risks
* Cross-Site Scripting (XSS)
* SQL Injection concepts
* Security misconfigurations
* Automated vulnerability scanning using OWASP ZAP

---

## Disclaimer

This assessment was performed in a controlled local environment for educational and authorized internship purposes only.
