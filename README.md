# CS 305 – Software Security

## Project Overview

This repository contains the refactored SSL server project completed for CS 305 – Software Security. The project demonstrates secure software development practices including HTTPS implementation, SHA-256 cryptographic hashing, TLS configuration, and automated vulnerability scanning using OWASP Dependency-Check.

---

## Client Summary

The client for this project was Artemis Financial, a financial services company that required improved security for its public-facing web application. The primary concern was the lack of secure transport and modern cryptographic protections. The company required the application to be refactored to implement HTTPS, strengthen data integrity validation, and ensure known software vulnerabilities were identified and mitigated.

---

## Vulnerability Assessment and Secure Coding

During the vulnerability assessment process, I analyzed communication protocols and third party dependencies. A significant issue identified was unsecured HTTP communication, which exposed the application to interception risks. I refactored the application to enforce HTTPS using TLS with a PKCS12 keystore and RSA 2048 bit encryption.

Coding securely is critical because insecure applications expose organizations to data breaches, financial loss, legal liability, and reputational damage. Software security strengthens trust, protects sensitive data, and reduces long-term remediation costs.

---

## Layered Security Implementation

Security improvements included:

- Enforcing HTTPS using TLS encryption
- Configuring a PKCS12 keystore with RSA 2048-bit keys
- Implementing SHA-256 hashing for data integrity verification
- Integrating OWASP Dependency Check into the Maven build lifecycle
- Performing functional testing to validate stability after refactoring

This approach reflects a defense in depth strategy.

---

## Functional and Security Validation

After refactoring, the application was compiled and executed successfully using HTTPS on port 8443. Automated dependency scanning confirmed that no new vulnerabilities were introduced. This ensured that security enhancements did not degrade application functionality.

---

## Tools and Technologies Used

- Java 8
- Spring Boot
- TLS / RSA 2048
- SHA-256
- Maven
- OWASP Dependency-Check

---

## Portfolio Relevance

This project demonstrates my ability to perform vulnerability assessments, refactor code to enforce secure transport protocols, implement modern cryptographic standards, and integrate automated security testing into the development lifecycle. These skills are directly applicable to secure software engineering and cybersecurity roles.

---

## Author

Zander Taylor
