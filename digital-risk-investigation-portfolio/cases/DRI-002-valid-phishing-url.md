# Case Report: DRI-002 - Valid Phishing URL Investigation

## 1. Case Information

| Field | Details |
|---|---|
| Case ID | DRI-002 |
| Date Collected | 2026-04-28 |
| Source | PhishTank |
| PhishTank ID | 9407017 |
| Source Status | Valid Phish |
| Online Status | Online |
| Platform | Website |
| URL | hxxps://download-us-en[.]wixstudio[.]com/enus |
| Threat Type | Phishing URL / Brand Impersonation |
| Classification | Phishing |
| Targeted Brand | Ledger |

## 2. Tools Used

- PhishTank
- VirusTotal
- DNS Lookup
- URLScan.io

## 3. Investigation Summary

This case involves a URL listed by PhishTank as a valid phishing URL. The URL is hosted on a Wix Studio subdomain and appears to impersonate Ledger by presenting Ledger-related download or onboarding content.

The URL was reviewed using PhishTank, VirusTotal, DNS Lookup, and URLScan.io. PhishTank identified the URL as a valid phish and online. VirusTotal showed multiple security vendors flagging the URL as malicious or phishing. URLScan.io also marked the website as potentially malicious and identified Ledger as the targeted brand.

The investigation focused on source validation, URL structure, domain and IP information, vendor detections, page title, page screenshot, and visible brand impersonation indicators.

## 4. Evidence Collected

| Evidence Type | Details |
|---|---|
| PhishTank | Listed as Valid Phish and Online |
| VirusTotal | 3/91 security vendors flagged the URL as malicious |
| URLScan.io Verdict | Potentially Malicious |
| URLScan Activity | Malicious Activity |
| DNS Lookup / Current DNS A Record | 34.144.206.118 |
| Hosting / ASN | GOOGLE-CLOUD-PLATFORM - Google LLC, US |
| Contacted Infrastructure | 7 IPs in 1 country across 6 domains |
| HTTP Transactions | 77 HTTP transactions |
| Targeted Brand | Ledger |
| Page Title | Ledger® Live: Download® — Getting Started \| official Ledger™ |
| Screenshots | Stored in the screenshots folder |

## 5. Indicators Observed

- The URL is listed by PhishTank as a valid phishing URL.
- The website was online at the time of review.
- VirusTotal showed 3/91 security vendors flagging the URL as malicious.
- Vendors including alphaMountain.ai, Forcepoint ThreatSeeker, and Webroot flagged the URL as malicious or phishing.
- URLScan.io marked the website as potentially malicious.
- URLScan.io identified the targeted brand as Ledger.
- The page title contains Ledger-related terms such as “Ledger Live”, “Download”, “Getting Started”, and “official Ledger”.
- The page screenshot shows content imitating a Ledger download or onboarding page.
- The URL uses a Wix Studio subdomain instead of an official Ledger-owned domain.
- The DNS A record resolves to Google Cloud Platform infrastructure, which may indicate abuse of a legitimate website-building or hosting platform.
- The URL structure and page content suggest brand impersonation and phishing activity.

## 6. Assessment

Based on the PhishTank valid phishing status, VirusTotal vendor detections, URLScan.io potentially malicious verdict, DNS/IP information, and visible Ledger impersonation indicators, this URL is classified as phishing.

The use of a Wix Studio subdomain, Ledger-themed page title, and download-related wording strongly suggest that the website was created to impersonate Ledger and deceive users into interacting with a fake download or onboarding page.

Although the VirusTotal detection ratio is lower than Case DRI-001, the PhishTank valid phishing status and URLScan.io brand impersonation evidence provide strong support for the phishing classification.

## 7. Recommended Action

- Escalate the case for blocking and takedown review.
- Add the defanged URL and domain to internal watchlists.
- Monitor for similar Ledger-themed Wix Studio subdomains.
- Monitor for typosquatting or suspicious naming patterns related to Ledger download/setup pages.
- Warn users not to download files, enter credentials, wallet recovery phrases, personal information, or crypto wallet data from this website.

## 8. Safety Note

The URL has been defanged for safe documentation. No credentials were entered, no files were downloaded, and no direct interaction was performed with the phishing website.

## 9. Screenshot References

| Screenshot | Description |
|---|---|
| screenshots/DRI-002-phishtank.png | PhishTank result showing Valid Phish and Online status |
| screenshots/DRI-002-virustotal.png | VirusTotal result showing 3/91 vendor detections |
| screenshots/DRI-002-dnslookup.png | DNS lookup result showing current DNS A record and hosting information |
| screenshots/DRI-002-urlscan.png | URLScan.io result showing potentially malicious verdict, targeted brand, IP, page title, and screenshot | screenshots/DRI-002-https-lookup.png | MXToolbox HTTPS lookup showing certificate and HTTP 200 OK |
