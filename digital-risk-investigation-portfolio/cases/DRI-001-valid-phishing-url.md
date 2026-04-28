# Case Report: DRI-001 - Valid Phishing URL Investigation

## 1. Case Information

| Field | Details |
|---|---|
| Case ID | DRI-001 |
| Date Collected | 2026-04-28 |
| Source | PhishTank |
| PhishTank ID | 9406932 |
| Source Status | Valid Phish |
| Online Status | Online |
| Platform | Website |
| URL | hxxps://hub-leddgerstrtcom[.]weebly[.]com/ |
| Threat Type | Phishing URL / Brand Impersonation |
| Classification | Phishing |
| Targeted Brand | Ledger |

## 2. Tools Used

- PhishTank
- VirusTotal
- DNS Lookup
- URLScan.io

## 3. Investigation Summary

This case involves a URL listed by PhishTank as a valid phishing URL. The URL is hosted on a Weebly subdomain and appears to impersonate Ledger by presenting Ledger-related onboarding or crypto wallet content.

The URL was reviewed using PhishTank, VirusTotal, DNS Lookup, and URLScan.io. PhishTank identified the URL as a valid phish and online. VirusTotal showed multiple security vendors flagging the URL as malicious or phishing. URLScan.io also marked the website as potentially malicious and identified Ledger as the targeted brand.

The investigation focused on source validation, URL structure, domain and IP information, vendor detections, page title, page screenshot, and visible brand impersonation indicators.

## 4. Evidence Collected

| Evidence Type | Details |
|---|---|
| PhishTank | Listed as Valid Phish and Online |
| VirusTotal | 14/91 security vendors flagged the URL as malicious |
| URLScan.io Verdict | Potentially Malicious |
| URLScan Activity | Malicious Activity |
| DNS Lookup / Current DNS A Record | 74.115.51.9 |
| Hosting / ASN | WEEBLY - Weebly, Inc., US |
| Contacted Infrastructure | 6 IPs in 2 countries across 3 domains |
| HTTP Transactions | 34 HTTP transactions |
| Targeted Brand | Ledger |
| Page Title | Ledger.com/Start® \| Getting started – Ledger |
| Screenshots | Stored in the screenshots folder |

## 5. Indicators Observed

- The URL is listed by PhishTank as a valid phishing URL.
- The website was online at the time of review.
- VirusTotal showed 14/91 security vendors flagging the URL as malicious.
- Several vendors classified the URL as phishing, including BitDefender, ESET, Fortinet, Kaspersky, Phishtank, and others.
- URLScan.io marked the website as potentially malicious.
- URLScan.io identified the targeted brand as Ledger.
- The page title contains Ledger-related terms such as “Ledger.com/Start” and “Getting started”.
- The page screenshot shows content imitating Ledger-related onboarding or crypto wallet content.
- The URL uses a Weebly subdomain instead of an official Ledger-owned domain.
- The domain name contains a suspicious variation of the Ledger brand name: `leddgerstrtcom`.
- The DNS A record resolves to Weebly infrastructure, which may indicate abuse of a legitimate website-building platform.
- The URL structure and page content suggest brand impersonation and phishing activity.

## 6. Assessment

Based on the PhishTank valid phishing status, VirusTotal vendor detections, URLScan.io potentially malicious verdict, DNS/IP information, suspicious domain naming, and visible Ledger impersonation indicators, this URL is classified as phishing.

The use of a Weebly subdomain, the Ledger-like domain naming, and the Ledger-themed page title strongly suggest that the website was created to impersonate Ledger and deceive users into interacting with a fake onboarding or crypto wallet-related page.

## 7. Recommended Action

- Escalate the case for blocking and takedown review.
- Add the defanged URL and domain to internal watchlists.
- Monitor for similar Ledger-themed Weebly subdomains.
- Monitor for typosquatting patterns related to Ledger, such as `ledger`, `leddger`, `ledger-start`, or `ledgerstrt`.
- Warn users not to enter credentials, wallet recovery phrases, personal information, or download files from this website.

## 8. Safety Note

The URL has been defanged for safe documentation. No credentials were entered, no files were downloaded, and no direct interaction was performed with the phishing website.

## 9. Screenshot References

| Screenshot | Description |
|---|---|
| screenshots/DRI-001-phishtank.png | PhishTank result showing Valid Phish and Online status |
| screenshots/DRI-001-virustotal.png | VirusTotal result showing 14/91 vendor detections |
| screenshots/DRI-001-dnslookup.png | DNS lookup result showing current DNS A record and hosting information |
| screenshots/DRI-001-urlscan.png | URLScan.io result showing potentially malicious verdict, targeted brand, IP, page title, and screenshot | screenshots/DRI-001-urlscan.png | URLScan.io result showing potentially malicious verdict and page screenshot |
