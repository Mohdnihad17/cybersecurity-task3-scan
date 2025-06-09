#  Task 3: Basic Vulnerability Scan on My PC

##  Tools Used
- Nessus Essentials
- Operating System: Windows 11
- Target: Localhost (127.0.0.1)

---

##  Objective
To perform a basic vulnerability scan on my PC using Nessus Essentials, identify common vulnerabilities, and understand their severity and mitigation.

---

## Vulnerability Summary

| Severity | Count |
|----------|-------|
| Critical | 0 |
| High     | 0 |
| Medium   | 1 |
| Low      | 0 |
| Info     | 22+ |

---

##  Top 3 Vulnerabilities

### 1️ SMB Signing not required
- **Severity**: Medium
- **CVSS Score**: 5.3
- **Description**: The SMB server does not require message signing. This could allow an attacker to perform man-in-the-middle (MITM) attacks.
- **Possible Fix**: Configure SMB server to require SMB signing to ensure message integrity and mitigate MITM risks.

### 2️ SSL (Multiple Issues)
- **Severity**: Info
- **CVSS Score**: Not provided
- **Description**: The SSL/TLS configuration on the host has multiple issues such as support for weak ciphers or old protocols.
- **Possible Fix**: Disable weak ciphers and outdated SSL/TLS versions in the server configuration.

### 3️ SMB (Multiple Issues)
- **Severity**: Info
- **CVSS Score**: Not provided
- **Description**: The SMB service has multiple informational issues detected which may include support for outdated protocols or lack of security best practices.
- **Possible Fix**: Update SMB services to the latest secure version and apply recommended configurations.

---

##  Summary
This task gave me hands-on experience with vulnerability scanning using Nessus Essentials. Although no Critical or High vulnerabilities were found, one Medium vulnerability and multiple Info findings were identified. This helps in understanding potential security improvements and the importance of proactive scanning.

---

##  Submitted By
**Name**: Mohammed Nihad  
**Institution**: Royal College of Engineering and Technology
