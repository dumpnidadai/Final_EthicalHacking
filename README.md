**Ethical Hacking Technical Report**

**Client:** https://adstudio.cloud/

**Date:** May 11, 2024

**Prepared by:** Sergio, Eladen Loma Agatha Ina : Evallar, Krizel Allen 


**Executive Summary:** This report presents the technical findings of the ethical hacking assessment conducted for adstudio.cloud. The assessment aimed to identify vulnerabilities within the organization's network infrastructure, applications, and systems. Through various testing methodologies, including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. This report provides detailed descriptions of these findings, along with actionable recommendations for remediation.

**Vulnerability Summary:**

1.  **Network Infrastructure:**
    
    -   **High:**   The firewall rules are set up incorrectly, allowing unrestricted access from external IP ranges to sensitive internal services
2.  **Web Applications:**
    
	- **Critical:** SQL Injection vulnerability in the login form of adstudio.cloud, potentially enabling an attacker to extract sensitive data from the database. 
	- **High:** Cross-Site Scripting (XSS) vulnerability in adstudio.cloud, allowing attackers to execute malicious scripts in users' browsers.
3.  **Operating Systems:**
    
	-   **High:** Weak password policies have been discovered on domain user accounts within the operating systems. This insufficient security measure allows brute-force attacks and unauthorized access, potentially risking critical data and system integrity.
4.  **Wireless Networks:**
    
    -   **Critical:** Wireless networks use weak encryption (WEP), which allows attackers to capture and decrypt wireless transmission, exposing sensitive data.
5.  **Social Engineering:**
    
    -   **High:** The employees divulges sensitive information to the attacker that pose as a trusted individual or authority figure. 

**Recommendations:**

1.  **Network Infrastructure:**
    
	- To mitigate the Remote Code Execution vulnerability, immediately update Apache Struts to the most recent version.  
	- Review and update firewall rules to restrict access using the principle of least privilege.
2.  **Web Applications:**
    
	- Perform a comprehensive code review and input validation to prevent SQL Injection and XSS attacks.  
	- Use security headers (such as Content Security Policy) to minimize XSS vulnerabilities.
3.  **Operating Systems:**
    
	- Develop a patch management technique for updating and protecting operating systems from known vulnerabilities.
	- Implement strong password restrictions and investigate multi-factor authentication for domain user accounts.
4.  **Wireless Networks:**
    
	   - Upgrade wireless network encryption to WPA2 or WPA3 to protect the confidentiality and integrity of wireless communications.
5.  **Social Engineering:**
    
    -   Conduct thorough background checks on employees and vendors who have access to sensitive information or systems. This can help mitigate the risk of insider threats and unauthorized access through pretexting.

**Conclusion:** The findings of the ethical hacking assessment reveal multiple serious vulnerabilities and security flaws in adstudio.cloud's infrastructure and applications. By taking the recommended remediation procedures, adstudio.cloud can improve its security posture and reduce the risk of cyber threats and data breaches.

Signature:

Sergio, Eladen Loma Agatha Ina

Evallar, Krizel Allen
