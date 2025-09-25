## Task-3

1. What is Nessus?
 - Nessus is a commercial vulnerability assessment and management tool developed by Tenable that identifies security flaws, missing patches, malware, and misconfigurations in network devices, applications, operating systems, and cloud services.
 
 - How it Works
 1. Scanning for Vulnerabilities:
    Nessus performs in-depth scans across networks and systems to detect security weaknesses, such as software flaws or missing updates. 
 2. Identification of Risks:
    The tool runs thousands of checks to identify potential vulnerabilities that could allow unauthorized access or harm a system. 
 3. Reporting and Prioritization:
    Nessus generates detailed reports on its findings, including assigning severity ratings to vulnerabilities, which allows security professionals to prioritize their efforts and allocate resources effectively. 
 4. Remediation Guidance:
    The reports also provide recommendations on how to fix or mitigate the identified security issues. 


2. Install OpenVAS or Nessus Essentials.
 - Nessus can be downloaded via official website https://www.tenable.com/downloads/nessus?loginAttempted=true

3. Vulnerability found: HTTp TRACE / TRACK Methods Allowed
 - What is it??
   enabling TRACE on production servers creates a Cross-Site Tracing (XST) vulnerability, allowing attackers to Session Hijacking, Cross-Site Scripting (XSS), Information Disclosure

 - How to mitigate??
   Apache:
   You can disable TRACE by adding the line TraceEnable Off to your httpd.conf file. 
