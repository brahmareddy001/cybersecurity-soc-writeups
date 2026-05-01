# SOC Investigation Write-ups

Personal documentation of SOC analyst investigations completed on TryHackMe as part of my preparation for SOC / Blue Team roles. Each write-up covers a real room I solved end-to-end: the scenario, my investigation steps, the specific queries and tools I used, and the IOCs I extracted.

These write-ups are living notes — I update them as I learn cleaner techniques.

## About me

I'm Brahma Reddy Chandragiri, an M.Sc. Enterprise & IT Security student at Hochschule Offenburg, Germany. I'm building toward a SOC / GRC Werkstudent role and full-time entry-level position after graduation in February 2027.

- TryHackMe: [Top 5%, 93 rooms, 17 badges](https://tryhackme.com/p/brahmareddy.chan)
- LinkedIn: [linkedin.com/in/brahma-reddy-chandragiri](https://www.linkedin.com/in/brahma-reddy-chandragiri/)

## Write-ups in this repository

| # | Room | Path | Type | Skills demonstrated |
|---|------|------|------|---------------------|
| 1 | [Splunk: Exploring SPL](./01-splunk-exploring-spl.md) | SOC Level 1 — SIEM | Walkthrough | Splunk SPL, search optimization, transforming commands |
| 2 | [ItsyBitsy](./02-itsybitsy-elk-investigation.md) | SOC Level 1 — SIEM | **Challenge** | ELK Stack, KQL, log correlation, C2 detection |
| 3 | [The Greenholt Phish](./03-greenholt-phish.md) | Phishing Analysis | **Challenge** | Email header analysis, IOC extraction, phishing triage |

## Tools & techniques I use repeatedly

- **SIEM / log analysis:** Splunk SPL, Elastic Stack (Kibana, KQL)
- **Network forensics:** Wireshark, Nmap
- **Email analysis:** raw header parsing, SPF/DKIM/DMARC validation, IOC extraction
- **Threat intel:** VirusTotal, AbuseIPDB, URLscan.io, Talos
- **Frameworks:** MITRE ATT&CK, Cyber Kill Chain, NIST CSF

## What I'm working on next

- Finishing the SOC Level 1 path (currently 47%)
- Adding Wireshark and incident-response challenge write-ups
- Publishing an ISO 27001 / NIST CSF sample gap analysis (separate repo, in progress)

---
*Each write-up below is independent — read whichever you find most relevant.*
