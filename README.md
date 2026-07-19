# The Art of Network Penetration Testing — Lab Reports

Chapter-by-chapter technical lab reports written against *The Art of Network Penetration Testing* by Royce Davis (Manning Publications, 2020), documenting a full Internal Network Penetration Test (INPT) against the Capsulecorp lab environment (VMware Workstation 17 Pro, subnet 10.0.10.0/24).
These are my personal lab notes/write-ups from working through The Art of Network Penetration Testing by Royce Davis (Manning Publications, 2020). This repo is not affiliated with or endorsed by the author or publisher.
Each of Labs 1–5 covers two chapters and is split here into two standalone reports.

## Contents

| Lab | Chapters | Reports |
|---|---|---|
| Lab 1 | 1–2 | [Chapter 1 — Network Penetration Testing](Chapter-01-Network-Penetration-Testing/report.md) · [Chapter 2 — Discovering Network Hosts](Chapter-02-Discovering-Network-Hosts/report.md) |
| Lab 2 | 3–4 | [Chapter 3 — Discovering Network Services](Chapter-03-Discovering-Network-Services/report.md) · [Chapter 4 — Discovering Network Vulnerabilities](Chapter-04-Discovering-Network-Vulnerabilities/report.md) |
| Lab 3 | 5–6 | [Chapter 5 — Attacking Vulnerable Web Services](Chapter-05-Attacking-Vulnerable-Web-Services/report.md) · [Chapter 6 — Attacking Vulnerable Database Services](Chapter-06-Attacking-Vulnerable-Database-Services/report.md) |
| Lab 4 | 7–8 | [Chapter 7 — Attacking Unpatched Services](Chapter-07-Attacking-Unpatched-Services/report.md) · [Chapter 8 — Windows Post-Exploitation](Chapter-08-Windows-Post-Exploitation/report.md) |
| Lab 5 | 9–10 | [Chapter 9 — Linux and UNIX Post-Exploitation](Chapter-09-Linux-and-Unix-Post-Exploitation/report.md) · [Chapter 10 — Controlling the Entire Network](Chapter-10-Controlling-the-Entire-Network/report.md) |
| Lab 6 | Capstone | [Final Engagement Report](Final-Engagement-Report/report.md) |

## About the Final Engagement Report

Chapter 12 of the book ("Writing your report") is a report-writing tutorial rather than a hands-on technical chapter, so it was not turned into its own chapter report. Instead, its guidance on structuring a professional pentest deliverable (executive summary, methodology, attack narrative, technical observations, and appendices) was used as the structural template for the [Final Engagement Report](Final-Engagement-Report/report.md), which consolidates the entire Capsulecorp engagement — from initial reconnaissance through full Active Directory domain compromise — into a single client-facing deliverable.

## Structure

Each chapter directory contains:
- `report.md` — the chapter's technical report (objective, tools, methodology, findings, references)
- `images/` — screenshots/figures referenced in that report, extracted from the original lab submissions

## Environment

All labs were conducted against the **Capsulecorp** simulated enterprise network (10.0.10.0/24), deployed in VMware Workstation 17 Pro, consisting of domain-joined Windows servers/workstations, Linux/Ubuntu hosts, and supporting network infrastructure.
