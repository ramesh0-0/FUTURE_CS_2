# FUTURE_CS_2
# Phishing Detection & Awareness System (Task 2)

## 🔍 Overview
This repository contains a professional security analysis of phishing email samples. The goal is to demonstrate how to identify, analyze, and mitigate phishing threats using industry-standard tools.

## 🛠️ Tools Used
- **MXToolbox / Google Header Tool**: Analyzed email headers for SPF, DKIM, and DMARC compliance.
- **VirusTotal**: Scanned URLs for malicious signatures across 90+ security vendors.
- **URLScan.io**: Safely analyzed the behavior of malicious domains and origin IPs.
- **WeasyPrint**: Generated the professional PDF report.

## 📈 Analysis Approach
1. **Initial Screening**: Identifying social engineering triggers (urgency, fear, greed).
2. **Technical Inspection**: Extracting raw headers to find discrepancies in the sender's identity.
3. **Link Defanging**: Investigating URLs in a sandbox environment to prevent infection.
4. **Classification**: Categorizing the threat level based on technical evidence.

## 📁 Repository Structure
- `phishing_report.dox`: Detailed analysis and awareness guidelines.
- `evidence/`: Screenshots of header analysis and VirusTotal results (if applicable).

## 🚀 Key Findings
The analyzed sample used a **Shopify sub-domain** and a fresh **TLS certificate** to bypass basic user suspicion. The absence of a **DMARC** policy made the email spoofing successful.


## evdience 

<img width="1614" height="972" alt="imagephishing1" src="https://github.com/user-attachments/assets/58177edb-2256-4ae0-8247-fbbaba77da1a" />

