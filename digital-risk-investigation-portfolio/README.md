# Digital Risk Investigation Portfolio

## Overview

This project is a beginner-friendly digital risk investigation portfolio focused on phishing URL analysis, brand impersonation detection, public threat intelligence validation, and structured case reporting.

The purpose of this project is to practice entry-level Digital Risk Investigator skills, including identifying suspicious URLs, validating phishing reports, collecting evidence, reviewing technical indicators, and documenting investigation results in a clear and consistent format.

All suspicious URLs in this repository are defanged for safety.

## Objective

The main objectives of this project are to:

- Investigate phishing URLs from public threat intelligence sources
- Validate suspicious URLs using multiple tools
- Collect evidence such as screenshots, URL reputation results, DNS information, and scan results
- Identify brand impersonation indicators
- Classify URLs based on observed evidence
- Produce structured investigation reports similar to entry-level digital risk intelligence outputs

## Tools Used

The following tools were used consistently across the cases:

- PhishTank
- VirusTotal
- DNS Lookup
- URLScan.io

## Case Summary

| Case ID | Threat Type | Targeted Brand | Classification | Status |
|---|---|---|---|---|
| DRI-001 | Phishing URL / Brand Impersonation | Ledger | Phishing | Completed |
| DRI-002 | Phishing URL / Brand Impersonation | Ledger | Phishing | Completed |
| DRI-003 | Phishing URL / Brand Impersonation | Ledger | Phishing | Completed |

## Investigation Workflow

Each case follows the same basic investigation workflow:

1. Identify a suspicious or reported phishing URL from PhishTank.
2. Confirm the source status, such as Valid Phish and Online.
3. Defang the URL before documentation.
4. Check the URL reputation using VirusTotal.
5. Review DNS or IP information using DNS Lookup.
6. Analyze page behavior, screenshots, page title, hosting information, and indicators using URLScan.io.
7. Identify phishing indicators such as brand impersonation, suspicious subdomains, fake login/download/setup pages, and mismatched hosting.
8. Classify the case based on the collected evidence.
9. Document the findings in a structured Markdown report.

## Folder Structure

```text
digital-risk-investigation-portfolio/
├── README.md
├── case-summary.csv
├── cases/
│   ├── DRI-001-valid-phishing-url.md
│   ├── DRI-002-valid-phishing-url.md
│   └── DRI-003-valid-phishing-url.md
└── screenshots/
    ├── DRI-001-dnslookup.png
    ├── DRI-001-phishtank.png
    ├── DRI-001-urlscan.png
    ├── DRI-001-virustotal.png
    ├── DRI-002-dnslookup.png
    ├── DRI-002-phishtank.png
    ├── DRI-002-urlscan.png
    ├── DRI-002-virustotal.png
    ├── DRI-003-dnslookup.png
    ├── DRI-003-phishtank.png
    ├── DRI-003-urlscan.png
    └── DRI-003-virustotal.png digital-risk-investigation-portfolio
