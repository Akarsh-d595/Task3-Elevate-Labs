# Vulnerability Scan Report

*Scanner Used:* OpenVAS  
*Date of Scan:*2025-09-25 
*Target:* Localhost (192.168.29.207)  

---

## 1. Summary of Findings
- Total vulnerabilities found: 13  
- Critical: 2  
- High: 7
- Medium: 3  
- Low:  1 

---

## 2. Critical Vulnerabilities
| ID | Vulnerability | Severity | Description | Suggested Fix |
|----|---------------|----------|-------------|---------------|
| 1  |  OpenSSH Outdated Version | Critical | Running OpenSSH 7.2p2, known flaws | Update OpenSSH to latest stable version |
| 2  |  SMB Signing Disabled | High | SMB traffic not signed, risk of MITM attacks | Enable SMB signing in settings |

---

## 3. Screenshots
Screenshots of scan results are saved in the screenshots/ folder. Example:  
![Scan Screenshot](screenshots_scan1.png)

---

## 4. Suggested Mitigations
- Apply system updates and patches regularly.  
- Disable unused services/ports.  
- Enable firewall and secure configurations.  
- Re-run scans monthly to ensure compliance.  

---

## 5. Conclusion
The scan identified common vulnerabilities on the system. Addressing the critical and high-risk issues will significantly improve system security.
