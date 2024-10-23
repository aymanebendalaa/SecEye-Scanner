# SecEye-Scanner
Sysmon and IP Reputation Analysis Tool

Overview:
This tool automates the collection and analysis of logs generated by Sysmon, aiming to identify potentially malicious IP addresses and domains. By integrating with the VirusTotal API, it checks the reputation of both IP addresses and domains, offering a streamlined approach to bolster network security and threat detection.

Functionality:
Log Retrieval: The tool retrieves logs generated by Sysmon, specifically focusing on network activity and process creation events.

IP and Domain Extraction: It extracts unique IP addresses and domains from the Sysmon logs, ensuring that each is checked only once, even if it appears multiple times.

VirusTotal API Integration: Using up to 11 free VirusTotal API keys, the tool checks the reputation of each IP and domain against VirusTotal's comprehensive threat intelligence database. The rotation of API keys ensures the tool runs continuously without exceeding API rate limits.

Output Files:
All IPs and Domains: A file containing the complete list of IPs and domains retrieved from the Sysmon logs.
Malicious IPs and Domains: A separate file listing any IPs or domains flagged as malicious by VirusTotal, providing clear visibility into potential threats.

Installation:
To install the tool and get started, follow the detailed instructions available on my Medium article.

Conclusion:
This tool is perfect for network administrators and security analysts, automating the process of Sysmon log analysis and improving cybersecurity. By efficiently utilizing VirusTotal, it enhances the ability to detect and respond to threats in real-time.
