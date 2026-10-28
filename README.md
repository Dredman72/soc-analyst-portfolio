# SOC Analyst Portfolio

Personal projects for practicing Security Operations Center (SOC) analyst skills and demonstrating them on a resume / in interviews.

**Author:** <!-- Your name -->  
**Background:** B.S. Cyber Security · studying CompTIA A+ and Security+  
**Focus:** Detection, investigation, documentation, and MITRE ATT&CK mapping

> These are **educational home-lab projects**, not production SOC work. Each project includes a build guide, evidence, and a written investigation report.

---

## Portfolio projects

| # | Project | Status | Stack / data | Folder |
|---|---------|--------|--------------|--------|
| 1 | **SIEM Monitoring Lab** | In progress / Complete | Splunk Enterprise (Trial → Free), Windows Event Logs, Boss of the SOC (BOTS) | [project1-splunk-siem-lab/](project1-splunk-siem-lab/) |
| 2 | **Single Alert Deep-Dive** | Planned | One high-fidelity alert (e.g., brute-force / 4625) → full case write-up | `project2-alert-investigation/` |
| 3 | **Threat Hunt (MITRE ATT&CK)** | Planned | Hypothesis-driven hunt mapped to ATT&CK tactics/techniques | `project3-threat-hunt/` |
| 4 | **Incident Response Simulation** | Planned | Tabletop + log-driven IR lifecycle (detect → contain → eradicate → recover → lessons) | `project4-ir-simulation/` |
| 5 | **Phishing Email Analysis** | Planned | Header/URL/attachment triage, IOC extraction, user-aware response notes | `project5-phishing-analysis/` |

---

## Project 1 — SIEM Monitoring Lab (current)

Stand up Splunk, ingest real Windows logs and a public BOTS dataset, run guided SPL investigations, build a dashboard and alert, and publish a report.

| Artifact | Description |
|----------|-------------|
| [GUIDE.md](project1-splunk-siem-lab/GUIDE.md) | Step-by-step build + investigation guide |
| [GUIDE.pdf](project1-splunk-siem-lab/GUIDE.pdf) | PDF copy of the guide |
| [REPORT_TEMPLATE.md](project1-splunk-siem-lab/REPORT_TEMPLATE.md) | Investigation report template to fill in |
| [RESUME_BULLETS.md](project1-splunk-siem-lab/RESUME_BULLETS.md) | Honest resume bullet templates |
| `screenshots/` | Evidence images (add after you run the lab) |
| `REPORT.md` | Your completed report (copy from the template) |

**Verified external resources**

- Splunk Enterprise trial: https://www.splunk.com/en_us/download/splunk-enterprise.html  
- BOTS v1: https://github.com/splunk/botsv1  
- BOTS v3: https://github.com/splunk/botsv3  
- MITRE ATT&CK: https://attack.mitre.org/

---

## How to use this repo

1. Complete Project 1 using `project1-splunk-siem-lab/GUIDE.md`.  
2. Fill `REPORT_TEMPLATE.md` → save as `REPORT.md` with screenshots.  
3. Update the status table above.  
4. Add resume bullets only after evidence exists.  
5. Repeat for Projects 2–5 as you build them.

---

## Skills demonstrated (target)

- SIEM deployment & log onboarding  
- SPL search / correlation  
- Windows Event Log analysis  
- Dashboarding & alerting concepts  
- MITRE ATT&CK mapping  
- Investigation report writing  
- IOC / timeline thinking  

---

## Disclaimer

Lab datasets (including BOTS) may contain offensive language from realistic incident recreations. Do not use these techniques on systems you do not own or lack permission to test. Redact personal information before publishing screenshots.

---

## License

Your write-ups: choose a license (e.g., MIT) for *your* documentation.  
Splunk software: subject to Splunk’s license terms.  
BOTS datasets: CC0 per Splunk’s dataset repositories — see each BOTS README.
