# Case Report: DRI-003 - Valid Phishing URL Investigation

## 1. Case Information

| Field | Details |
|---|---|
| Case ID | DRI-003 |
| Date Collected | 2026-04-28 |
| Source | PhishTank |
| PhishTank ID | REPLACE_PHISHTANK_ID |
| Source Status | Valid Phish |
| Online Status | Online |
| Platform | Website |
| URL | hxxps://started-ledegar[.]wixstudio[.]com/en-com |
| Threat Type | Phishing URL / Brand Impersonation |
| Classification | Phishing |
| Targeted Brand | Ledger |

## 2. Tools Used

- PhishTank
- VirusTotal
- DNS Lookup
- URLScan.io

## 3. Investigation Summary

This case involves a suspicious URL hosted on a Wix Studio subdomain. The page appears to impersonate Ledger by presenting Ledger-related setup or onboarding content.

The URL was reviewed using PhishTank, VirusTotal, DNS Lookup, and URLScan.io. URLScan.io marked the website as potentially malicious and identified Ledger as the targeted brand. VirusTotal also showed multiple security vendors flagging the URL as malicious or phishing.

The investigation focused on public phishing validation, URL structure, domain and IP information, vendor detections, page title, page screenshot, and visible brand impersonation indicators.

## 4. Evidence Collected

| Evidence Type | Details |
|---|---|
| PhishTank | Listed as Valid Phish and Online |
| VirusTotal | 13/91 security vendors flagged the URL as malicious |
| URLScan.io Verdict | Potentially Malicious |
| URLScan Activity | Malicious Activity |
| DNS Lookup / Current DNS A Record | 34.144.206.118 |
| Hosting / ASN | GOOGLE-CLOUD-PLATFORM - Google LLC, US |
| Contacted Infrastructure | 8 IPs in 1 country across 7 domains |
| HTTP Transactions | 78 HTTP transactions |
| Targeted Brand | Ledger |
| Page Title | Official® \| Ledger.com/Start® \| Getting Started™ |
| Detected Technologies | Wix, Sentry, Bootstrap, Onsen UI, Lodash |
| Screenshots | Stored in the screenshots folder |

## 5. Indicators Observed

- The URL is listed by PhishTank as a valid phishing URL.
- The website was online at the time of review.
- VirusTotal showed 13/91 security vendors flagging the URL as malicious.
- Several vendors classified the URL as phishing, including BitDefender, ESET, Fortinet, Kaspersky, Phishtank, Sophos, VIPRE, and others.
- URLScan.io marked the website as potentially malicious.
- URLScan.io identified the targeted brand as Ledger.
- The page title contains Ledger-related terms such as “Ledger.com/Start” and “Getting Started”.
- The page screenshot shows content imitating a Ledger setup guide.
- The URL uses a Wix Studio subdomain instead of an official Ledger-owned domain.
- The domain name contains a suspicious misspelling of Ledger: `ledegar`.
- The DNS A record resolves to Google Cloud infrastructure, which may indicate abuse of a legitimate cloud or website-building platform.
- The URL structure and page content suggest brand impersonation and phishing activity.

## 6. Assessment

Based on the PhishTank valid phishing status, VirusTotal vendor detections, URLScan.io potentially malicious verdict, DNS/IP information, suspicious domain naming, and visible Ledger impersonation indicators, this URL is classified as phishing.

The use of a Wix Studio subdomain, the misspelled Ledger-like domain name, and the Ledger-themed page title strongly suggest that the website was created to impersonate Ledger and deceive users into interacting with a fake setup or onboarding page.

## 7. Recommended Action

- Escalate the case for blocking and takedown review.
- Add the defanged URL and domain to internal watchlists.
- Monitor for similar Ledger-themed Wix Studio subdomains.
- Monitor for typosquatting patterns related to Ledger, such as `ledger`, `ledegar`, `ledgar`, or `ledger-start`.
- Warn users not to enter credentials, wallet recovery phrases, personal information, or download files from this website.

## 8. Safety Note

The URL has been defanged for safe documentation. No credentials were entered, no files were downloaded, and no direct interaction was performed with the phishing website.

## 9. Screenshot References

| Screenshot | Description |
|---|---|
| screenshots/DRI-003-phishtank.png | PhishTank result showing Valid Phish and Online status |
| screenshots/DRI-003-virustotal.png | VirusTotal result showing 13/91 vendor detections |
| screenshots/DRI-003-dnslookup.png | DNS lookup result showing current DNS A record and hosting information |
| screenshots/DRI-003-urlscan.png | URLScan.io result showing potentially malicious verdict, targeted brand, IP, page title, and screenshot |
