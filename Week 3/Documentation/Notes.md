SOC Investigation Notes — Week 3
Objective

Perform advanced SOC monitoring, analyze security events, integrate threat intelligence, and respond to simulated cyber incidents across the full incident lifecycle.

Environment

Windows Virtual Machine (monitored endpoint)
Ubuntu Attacker VM
Metasploitable2 Target VM
Wazuh SIEM Server
Elastic Security Platform
TheHive Incident Response Platform
CrowdSec Security Engine
Velociraptor Forensics Tool
FTK Imager

Activities

Advanced log analysis
Threat intelligence integration
Threat hunting
Incident escalation simulation
Alert triage and validation
Evidence collection and preservation
Capstone attack simulation

Log Analysis Tasks

Correlation of authentication failures with network activity
Detection of abnormal data transfers
GeoIP-based log enrichment
Identification of suspicious outbound connections

Threat Intelligence Tasks

Import of threat indicators from AlienVault OTX
Reputation analysis of IP addresses
Validation of indicators using VirusTotal
Hunting for credential misuse (MITRE T1078)

Incident Management Tasks

Creation of high-priority cases in TheHive
Escalation to Tier-2 analysts
Preparation of Situation Reports (SITREPs)
Automation of response workflows

Alert Triage Tasks

Analysis of suspicious PowerShell activity
Classification based on severity and risk
Correlation with threat intelligence sources
Determination of investigation priority

Evidence Preservation Tasks

Collection of volatile network data
Memory acquisition from affected systems
Hash generation using SHA-256 for integrity verification
Secure storage of collected artifacts

Capstone Simulation Tasks

Execution of exploit against vulnerable service
Detection of malicious activity in Wazuh
Containment through IP blocking using CrowdSec
Escalation and case management in TheHive
Documentation and reporting of incident response actions

Outcome

Demonstrated end-to-end SOC operations including detection, analysis, containment, escalation, and reporting within a controlled lab environment.
