# Week 3 Workflow — SOC Monitoring and Incident Response

## Objective
To simulate detection, analysis, response, and reporting of cyber incidents within a SOC environment.

---

## Step 1 — Advanced Log Analysis
- Ingest logs into Elastic Security
- Correlate authentication failures with network activity
- Detect anomalies such as high data transfer
- Enrich logs using GeoIP data

---

## Step 2 — Threat Intelligence Integration
- Import AlienVault OTX threat feeds into Wazuh
- Match events against known malicious indicators
- Perform threat hunting for credential misuse (T1078)

---

## Step 3 — Incident Escalation Practice
- Create incident case in TheHive
- Escalate high-severity alerts to Tier 2
- Generate SITREP report
- Automate escalation workflow

---

## Step 4 — Alert Triage
- Analyze suspicious alerts in Wazuh
- Validate indicators using VirusTotal and OTX
- Prioritize investigation

---

## Step 5 — Evidence Preservation
- Collect volatile data using Velociraptor
- Acquire memory dump using FTK Imager
- Verify integrity using SHA-256 hash

---

## Step 6 — Capstone Simulation
- Simulate attack using Metasploit
- Detect activity using Wazuh
- Contain attacker using CrowdSec
- Escalate via TheHive
- Document incident and produce report

---

## Outcome
Demonstrates end-to-end SOC incident response lifecycle.
