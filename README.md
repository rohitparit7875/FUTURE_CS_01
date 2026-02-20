🔐 Task Title

Vulnerability Assessment Report for a Live Website

🎯 Objective

The objective of this task is to perform a basic vulnerability assessment on a live website using OWASP ZAP (Passive Scan) and browser developer tools.
The goal is to identify common web security issues, classify their risk levels, and provide clear remediation recommendations in a business-friendly and professional manner.

🌐 Target Website
http://testphp.vulnweb.com

⚠️ This is a deliberately vulnerable test website used only for learning and educational purposes.

🛠️ Tools Used

OWASP ZAP (Passive Scan)

Browser Developer Tools (Chrome/Firefox DevTools)

Canva (for professional report design)

GitHub (for documentation and submission)

🐞 Summary of Vulnerabilities
Vulnerability	Risk Level	Description
Missing Content Security Policy (CSP) Header	Medium	Allows potential XSS and data injection attacks
X-Frame-Options Header Missing	Medium	Website may be vulnerable to clickjacking
Cookie Without HttpOnly Flag	Medium	Cookies can be accessed via client-side scripts
Server Information Disclosure	Low	Server details exposed in HTTP response headers

📌 Vulnerability Assessment Report (PDF):

https://github.com/rohitparit7875/FUTURE_CS_01.git
https://github.com/rohitparit7875/FUTURE_CS_01/blob/main/2026-02-20-ZAP-Report-testphp.vulnweb.com.html
