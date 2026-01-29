# Task 9 – Network Vulnerability Scanning

## Objective
The objective of this task is to understand how network vulnerability scanning works, how open ports and running services expose security risks, and how tools like Nmap help in identifying weak points in a network.

---

## Tools Used
- Nmap (Primary Tool)
- Masscan (Alternative)
- Local test network environment

---

## What is Network Vulnerability Scanning?
Network vulnerability scanning is the process of identifying open ports, running services, and system information on a network that could be exploited by attackers. It is a key step in network security assessment and penetration testing.

---

## Purpose of Port Scanning
Port scanning helps in:
- Discovering active hosts
- Identifying open ports
- Detecting running services
- Finding misconfigurations
- Understanding network exposure

---

## Scanning Methodology

The following steps are followed in network scanning:

1. Scan the local network to identify active hosts  
2. Identify open and closed ports  
3. Detect services running on open ports  
4. Identify operating system information  
5. Analyze potential vulnerabilities  
6. Save scan results  
7. Interpret risks  
8. Document findings  

This methodology follows the mini guide provided in the task sheet. fileciteturn7file0

---

## Types of Nmap Scans Used

| Scan Type | Purpose |
|--------|--------|
| Basic Scan | Identify open ports |
| Service Detection | Identify services and versions |
| OS Detection | Identify operating system |
| Aggressive Scan | Combines multiple detections |

---

## Observations
From network scanning, the following information can be discovered:
- Which ports are open
- Which services are running
- Potential outdated services
- Exposed system information

These details help attackers if left unprotected and must be secured.

---

## Risk Interpretation

| Finding | Risk |
|------|------|
| Open unnecessary ports | Increases attack surface |
| Outdated services | Vulnerable to exploits |
| Unknown devices | Possible unauthorized access |

---

## Security Importance
Network scanning is important because:
- It identifies weak points before attackers do
- It helps in proactive defense
- It supports network hardening
- It improves system visibility

---

## Ethical Considerations
All scans are performed:
- Only on authorized networks
- In local or lab environments
- For educational purposes only  

Scanning real networks without permission is illegal and unethical.

---

## Summary
This task helped in understanding:
- How Nmap scans networks
- Importance of port scanning
- How services expose vulnerabilities
- Why regular network audits are necessary

---

## Final Outcome
Developed strong network reconnaissance and vulnerability identification skills.

---

## Sources & References

1. Nmap Official Documentation  
https://nmap.org/book/man.html  

2. Nmap Reference Guide  
https://nmap.org/book/  

3. OWASP – Network Scanning  
https://owasp.org/www-community/Vulnerability_Scanning  

4. SANS Institute – Network Scanning Basics  
https://www.sans.org/white-papers/  

5. Rapid7 – What is Port Scanning  
https://www.rapid7.com/fundamentals/port-scanning/
