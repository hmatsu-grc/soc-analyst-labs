# SOC Analyst Labs

This repository contains hands-on cybersecurity investigations and defensive security exercises focused on SOC operations, alert triage, log analysis, and incident response.

## Featured Investigation

### LetsDefend SOC170 — Possible Local File Inclusion Attack

A step-by-step investigation of a suspicious web request attempting to access `/etc/passwd` through directory traversal.

The walkthrough covers:

- Alert validation
- Source IP log filtering
- HTTP request and response analysis
- Local File Inclusion identification
- Artifact collection
- Playbook decisions
- Alert closure and escalation reasoning

[View the SOC170 walkthrough](alert-triage/letsdefend-soc170-lfi/)

## Skills Demonstrated

- SOC alert triage
- Web attack analysis
- Log investigation
- Indicator and artifact collection
- True-positive classification
- Incident escalation decisions
- Technical documentation

## Tools and Platforms

- LetsDefend
- Web server logs
- Threat intelligence resources
- GitHub Markdown

## Repository Structure

```text
soc-analyst-labs/
└── alert-triage/
    ├── README.md
    └── letsdefend-soc170-lfi/
        ├── README.md
        └── images/
