# Cybersecurity Portfolio 1 (P1) — Homelab Build, Telemetry, and Case Files

## Overview
This portfolio shows the cybersecurity lab I have built and the work that comes from it. It includes:
- network segmentation with Proxmox and pfSense
- centralized Windows logging with WEF and Sysmon
- investigation-style case files and detection notes using Splunk, Elastic, and Wazuh

## Sanitization Note
This portfolio uses sample hostnames and internal IP ranges. Public-facing details such as WAN IPs, domains, DDNS, VPN settings, and secrets are removed or redacted. The overall design and workflow still reflect the real lab.

---

## Featured Projects

### 1) Proxmox Segmentation Lab
**Repo:** `P1-1-proxmox-segmentation-lab`  
**What it is:** A segmented Proxmox and pfSense lab with VM inventory, firewall boundaries, and safe publishing guidelines.  
**Why it’s included:** This is the foundation for the rest of the portfolio.
- Key artifacts: architecture diagram, bridges, firewall rules, IP plan, and VM inventory

Repo: https://github.com/kvntynito/P1-1-proxmox-segmentation-lab

---

### 2) Telemetry Pipeline
**Repo:** `P1-2-wef-sysmon-to-wazuh-elastic-splunk`  
**What it is:** A lab project focused on collecting Windows telemetry and reviewing it across multiple SIEM platforms.  
**Why it’s included:** It shows how I centralize logs and validate visibility across different tools.

Repo: https://github.com/kvntynito/P1-2-wef-sysmon-to-wazuh-elastic-splunk

---

### 3) Incident Investigation Case Files
**Repo:** `P1-3-incident-investigation-casefiles`  
**What it is:** A collection of investigation templates, detections, and case notes tied to activity generated in the lab.  
**Why it’s included:** It shows how I document alerts, review evidence, and build repeatable investigation workflows.

Repo: https://github.com/kvntynito/P1-3-incident-investigation-casefiles

---

## How the Projects Connect
- **P1-1** is the lab foundation. It covers the network layout, firewall boundaries, and VM design.
- **P1-2** builds on that foundation by centralizing Windows telemetry with WEF and Sysmon.
- **P1-3** uses that telemetry to document investigations, detections, and case findings.

## Current Status
P1-1 is currently in progress. Screenshots, configuration notes, and implementation details will be added as each milestone is completed in the homelab.
