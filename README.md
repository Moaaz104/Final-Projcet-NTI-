# Web Penetration Testing Report

## 📌 Overview
This repository contains our **Web Penetration Testing Report** completed for the NTI (National Telecommunication Institute) training program.  
The project demonstrates security testing methodologies on web applications through various hands-on labs, highlighting vulnerabilities, exploitation methods, and mitigation techniques.

## 👥 Team Members
- Moaaz Mahmoud Fathy  
- Mayson Mohamed Ahmed  
- Abdelkreem Ahmed Elghareb  
- Mostafa Hosny Elshoura  
- Zeyad Ashraf  
- Hany Mamdouh  

**Supervised by:** Eng. Samar Ibrahim  

## 🔍 Topics Covered
The report includes practical testing and exploitation of the following vulnerabilities:

- **SQL Injection (SQLi)**
  - Error-based
  - Union-based
  - Blind (Boolean/Time-based)
  - Out-of-Band

- **CORS Misconfigurations**
  - Basic origin reflection
  - Null origin trust
  - Insecure subdomain protocols

- **Server-Side Request Forgery (SSRF)**
  - Localhost exploitation
  - Internal network targeting
  - Blacklist bypass

- **Path Traversal**
  - Arbitrary file read
  - Bypass blocked traversal sequences
  - Double/recursive decode attacks

- **File Upload Vulnerabilities**
  - Web shell upload
  - Content-Type restriction bypass
  - Extension blacklist bypass
  - Path traversal during file upload

- **Access Control Issues**
  - Unprotected admin panels
  - Role escalation via cookies
  - Profile modification privilege escalation

## 🛡️ Security Recommendations
- Use parameterized queries (prepared statements) to prevent SQL injection.
- Whitelist trusted domains and enforce strict CORS policies.
- Implement SSRF protection by restricting internal/external network requests.
- Sanitize and validate file upload inputs with strict MIME/type checks.
- Enforce role-based access control (RBAC) and secure sensitive endpoints.
- Regularly audit configurations and perform penetration testing.

## 📂 Project Structure
- `Report Web Pentest.pdf` → Full detailed penetration testing report.

## 🎯 Purpose
This project serves as:
- A **learning resource** for understanding and exploiting common web vulnerabilities.
- A **reference guide** for developers and security engineers to apply mitigation best practices.
- A **practical training project** for NTI Web Security module.

---
