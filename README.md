\# Advanced Network Security Assessment-Metasploitable-project



\## Project Overview

This project presents a full penetration testing assessment conducted against the Metasploitable2 vulnerable lab machine within a controlled environment.



The objective was to identify exposed services, detect outdated software versions, map known vulnerabilities (CVEs), assess risk levels, and provide remediation recommendations.



---



\## Tools Used

\- Kali Linux

\- Nmap

\- Searchsploit

\- Metasploitable2



---



\## Methodology



1\. Host Discovery  

2\. Full Port Scanning  

3\. Service \& Version Detection  

4\. Vulnerability Identification  

5\. CVE Mapping  

6\. Risk Assessment  

7\. Remediation Planning  



---



\## Key Findings



| Service    | Version | Vulnerability                | Severity |

|------------|---------|------------------------------|----------|

| vsftpd     | 2.3.4   | Backdoor RCE (CVE-2011-2523) | Critical |

| UnrealIRCd | 3.2.8.1 | Backdoor RCE (CVE-2010-2075) | Critical |

| Samba      | 3.0.20  | Remote Code Execution        | High     |



---



\## Screenshots



\### Host Discovery

!\[Host Discovery](Screenshots/01\_host\_discovery.png)



\### Full Port Scan

!\[Full Port Scan](Screenshots/02\_full\_port\_scan.png)



\### Service Version Scan

!\[Service Scan](Screenshots/03\_service\_version\_scan.png)



---



\## Remediation Summary



\- Upgrade all outdated services immediately

\- Disable unnecessary services

\- Restrict network exposure

\- Implement patch management

\- Conduct regular security assessments



---



\## Conclusion



The assessment revealed multiple critical vulnerabilities that could allow full system compromise. Immediate remediation and continuous monitoring are strongly recommended.



