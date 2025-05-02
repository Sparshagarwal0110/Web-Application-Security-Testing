# 🛡️ FUTURE_CS_01 – Web Application Security Testing

## 📚 Internship Task – Future Interns (Cyber Security Track)

### 🔍 Objective:
Conduct a web application security assessment on OWASP Juice Shop to identify and report vulnerabilities like:
- SQL Injection
- Cross-Site Scripting (XSS)
- Broken Authentication

---

## 🛠️ Tools Used:
- Burp Suite
- OWASP ZAP
- SQLMap
- Kali Linux
- OWASP Juice Shop (Standalone)

---

## ✅ Vulnerabilities Identified:
| Vulnerability       | Location          | Severity | Description                          |
|---------------------|-------------------|----------|--------------------------------------|
| SQL Injection       | Login Form        | High     | Bypassed login using `' OR 1=1 --`    |
| Stored XSS          | Feedback Form     | Medium   | `<img src=x onerror=alert(1)>` executed |
| JWT Role Tampering  | JWT Token         | High     | Changed role to admin manually       |
| Sensitive Data Leak | Login API Response| Medium   | Exposed user info in plaintext       |

---

## 📄 Deliverables:
- [`Task1_Report.pdf`](./Task1_Report.pdf) – Full security assessment with steps, screenshots & mitigations

---

## 📝 Author:
**Sparsh** – Cyber Security Intern  
[LinkedIn](https://www.linkedin.com/in/sparsh-agarwal0110/)  
[Future Interns](https://www.linkedin.com/company/future-interns/)

---

> 🚀 Task 1 Completed. Task 2 in progress...

