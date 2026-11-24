# Cybersecurity Security Assessment Report

## Project Overview

This repository contains a practical cybersecurity assessment covering web application security testing, network traffic analysis, and vulnerability assessment.

The project focuses on identifying potential security weaknesses, analyzing network traffic, documenting security findings, evaluating risks, and recommending appropriate remediation measures.

This work was completed as part of a Cybersecurity Internship.

## Objectives

- Understand common web application security vulnerabilities.
- Perform practical security testing in authorized training environments.
- Analyze network traffic using Wireshark.
- Inspect HTTP requests, responses, and security headers.
- Identify security risks and recommend defensive measures.
- Document findings with supporting screenshots and reports.

## Tools and Technologies

- **Wireshark** – Network traffic analysis.
- **OWASP Juice Shop** – Web application security testing.
- **Burp Suite Community Edition** – HTTP request inspection and testing.
- **Google Chrome Developer Tools** – DOM and HTTP response inspection.
- **PortSwigger Web Security Academy** – Practical security training labs.

## Project Activities

### 1. Web Security Fundamentals

Completed practical exercises covering:

- Two-Factor Authentication (2FA) bypass.
- Broken Access Control.
- File Path Traversal.

### 2. Network Security Analysis

Performed network traffic analysis using Wireshark.

Activities included:

- Packet capture and protocol analysis.
- TCP connection analysis.
- TCP retransmission and reset inspection.
- DNS query and response analysis.
- UDP conversation inspection.

The recorded capture contained 5,446 packets.

### 3. Web Application Security Assessment

Performed testing on a locally hosted OWASP Juice Shop training application.

Activities included:

- Login Admin challenge.
- Score Board challenge.
- Search functionality and DOM inspection.
- HTTP response header inspection.
- Security configuration review.

## Key Security Findings

| Security Area | Finding |
|---|---|
| Authentication | 2FA bypass demonstrated in a training lab |
| Access Control | Unprotected administrative functionality in a training lab |
| Path Traversal | File path traversal demonstrated in a training lab |
| HTTP Headers | Selected response headers inspected |
| CORS | Wildcard origin observed in a selected response |
| Network Security | TCP and DNS traffic observations documented |

**Evidence limitations:** SQL Injection and Cross-Site Scripting were not confirmed by the supplied evidence. Further UDP, QUIC, and TLS analysis remains pending verification against the original packet capture.

## Repository Structure

```text
Cybersecurity-Security-Assessment-Report/
│
├── README.md
├── SWYNEX_Security_Assessment_Report_Task4_Final.pdf
│
└── Evidence/
    ├── Task1_PortSwigger/
    ├── Task2_Wireshark/
    └── Task3_Web_Security/
```

## Recommendations

- Implement strong authentication mechanisms.
- Enforce server-side access control.
- Validate file paths and user inputs.
- Use parameterized database queries.
- Configure appropriate HTTP security headers.
- Monitor and analyze network traffic.
- Follow security best practices and conduct regular assessments.

## Conclusion

This project provided practical exposure to cybersecurity concepts, web application security testing, network traffic analysis, vulnerability identification, and security documentation.

It strengthened my understanding of common security weaknesses and the importance of implementing effective defensive security measures.

## Disclaimer

All practical testing activities described in this repository were conducted using authorized training environments and a locally hosted vulnerable application. This project is intended for educational and defensive cybersecurity purposes only.

---

**Domain:** Cybersecurity  
**Project Type:** Security Assessment  
**Tools:** Wireshark, OWASP Juice Shop, Burp Suite, Chrome Developer Tools
