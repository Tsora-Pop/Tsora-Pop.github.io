---
layout: post
headimage: <img src= "assets/tenor.gif" class="card-img-top" alt="Header Image" width="300" height="100">
published: May 25, 2021
excerpt_separator: <!--more-->
tag: Study
---
## {{ page.title}}
{{ page.published }}

This is a list of security related questions for interviews. This is mostly for myself, but others
may find it useful. <!--more-->If anyone decides to use this, it is normal for people to blank on certain things. A technical interview is essentially a test for the interviewee with no study materials.
### General Security

1. Describe the CIA Triad.
2. False Positive vs a False Negative?
3. What is the MITRE ATT&CK framework?
4. Name some CIS Top 20 Security Controls.
5. Name some of the OWASP top ten web application security risks.
6. Describe Defense-In-Depth.

### Network Questions
1. How is UDP different from TCP?
2. Describe the TCP handshake.
3. What is NAT?
4. What is DHCP?
5. What is ARP?
6. How does DNS work?
7. HTTP port
8. DNS port
9. SMTP port
10. SNMP port
11. HTTPS port
12. SSH port
13. RDP port
14. SMB port
15. What is IDS and give an example?
16. How does IPS differ from IDS?
17. Describe firewall rules and name a few important example rules
18. What is a VLAN?
19. What is a VPN?
20. Explain which interfaces it is more worthwhile to have IDS/IPS on, WAN or LAN interfaces?

### Endpoint Questions
1. What are some windows events to be concerned about?
2. A malicious actor installed a backdoor on an endpoint. You have already isolated the device and evicted the actor. What are some additional steps to take?
3. What are possible actions to take when removing malicious software?

### Cloud Questions

### Security Operations Questions
1. You've identified an alert on your SIEM as a FP. What are your next steps?
2. Your console hasn't had any alerts in an hour. After checking some settings, you've identified that your SIEM is not working properly. What are your next steps?
3. You've identified a TP on an endpoint for malware calling back to a C2. What contain procedures should you take?
4. Your console is getting flooded with scanning alerts. You've identified the source of the traffic to come from a member of the Vulnerability Assessment team. They routinely perform these scans. What should you do?
5. What is a SIEM? Name a few examples.
6. What is a SOAR? Name a few examples.
7. What is an EDR? Name a few examples.
8. Are Sysmon or osquery EDRs?

### Incident Response Questions
1. Describe either the SANS or NIST Incident Response framework steps.
2. Describe the OODA loop.
3. What are some IOC categories to record?
4. What are actions to do during preparation phase?
5. What are actions to do during identification/Detection and Analysis phase?
6. What are actions to do during containment phase?
7. What are actions to do during eradication phase?
8. What are actions to do during recovery phase?
9. What are actions to do during lessons learned/Post-Incident phase?

### Forensics Questions

### Detection Engineering Questions
1. Compare a detection vs an alert vs an incident vs a rule.
2. Describe the different types of detections.
3. How would you handle a parsing issue?

### Programming Questions
1. tabs or spaces? :trollface:

### Vulnerability Management Questions

### Security Assessment Questions
1. Describe XSS
2. Describe SQL Injection
3. Describe CSRF
4. Describe a penetration test methodology
5. When would you use NMAP?
6. Differentiate between vulnerability scanning and a pentest.
7. Differentiate between a pentest and a Red Team engagement.
8. Differentiate between bug bounty hunting and a pentest.
9. You've identified a vulnerability in a web application, where can you find exploit proof of concept code?
10. What should be included in a pentest report?

### Governance, Compliance, and Risk Questions
1. What is Risk?
2. What is Compliance?
3. What is Governance?
4. What is an IT audit?
5. What are some key takeaways from the NIST Risk Management Framework? Name a few Special Publications in relation to this.
6. What are some Compliance laws and acts to be aware of?
