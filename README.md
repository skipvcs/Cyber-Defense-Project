# Cyber-Defense-Project
This repository contains example workflows and exercises for analyzing network intrusions, investigating malware incidents, and performing forensic analysis on compromised systems. Each section includes steps, file references, and tools that can be used for real-world incident analysis.

<h2>Description</h2>

This Project includes the following tasks:

1. Analyze a Remote Intrusion Attempt:
- Examine evidence of a password cracking attempt within a critical network. This involves analyzing packet capture files and event logs in a Security Information and Event Management (SIEM) system (e.g., Splunk) to determine if passwords were compromised or if the network was breached.
  
2. Investigate an Incident Using a SIEM:
- Analyze a potential “watering hole” attack, where users may have clicked a malicious link embedded in a legitimate website. The exploit kit may deploy malware such as a banking Trojan. Use SIEM data to trace the attack chain and identify affected systems.
  
3. Compile Indicators of Compromise (IOCs):
- Use a file hash of suspected malware to perform research via VirusTotal, online sandboxes, and open-source intelligence (OSINT). The resulting indicators of compromise can guide forensic analysis of memory dumps and disk images from infected devices.
  
4. Examine a Compromised Host’s Memory:
- Perform forensic analysis on memory images from compromised systems to identify sophisticated malware that resides in volatile memory.
  
5. Conduct a Forensic Disk Examination:
- Analyze disk images from infected systems to identify malware, reconstruct attack timelines, and determine the scope of the compromise.
  
6. Document Findings:
- Compile the investigation results, including a detailed timeline and key findings, into a report suitable for both technical and non-technical audiences.


<br />

<h2>Objectives Accomplished</h2>

- Analyze network traffic.
- Analyze network and system logs using a security information and event monitoring system.
- Cross-correlate log information and network packet traffic
- Use online sandboxes for static and dynamic analysis of malicious executable files to identify indicators of compromise.
- Use threat intelligence.
- Identify malware.
- Perform memory forensics.
- Perform disk forensics.
- Compile a comprehensive timeline of a cyber-attack.
- Report appropriately to technical and non-technical stakeholders



<br />

<h2>🛠 Tools Used</h2>

- Wireshark (network traffic analysis)
- Splunk (log analysis)
- VirusTotal (malware analysis)
- HybridAnalysis (malware analysis)
- Any.run (malware analysis)
- Volatility (memory forensics)
- Autopsy (disk forensics)
- Linux operating system


<h2>Description of files</h2>

1. The CISO.GUIDE FINAL REPORT:
   This is the SBAR created for the project

2. The Task 6 Technical Appendix:
   This the actual step by step actions I took to complete the project from beginning to end. These are not instructions but the actual steps I took. Doing screen shots as I went along.
   I would go back time and time again making sure I captured all my work...hence Rev D.

3. The Timeline is the beginning to end of the simulated project as the incident occured identifying the process of the attack.
