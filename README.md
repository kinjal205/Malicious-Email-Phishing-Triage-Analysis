## 📧 Malicious Email (Phishing) Investigation & Triage Analysis 

## 📌 Project Overview

This project demonstrates the investigation and analysis of a suspected phishing email using industry-standard Security Operations Center (SOC) methodologies.

The investigation includes email header analysis, SPF/DKIM/DMARC verification, source IP extraction, IP reputation analysis, Indicators of Compromise (IOCs) extraction, and final risk assessment to determine whether the email is malicious.


## 🎯 Objectives

- Analyze a suspicious email.
- Perform email header analysis.
- Verify SPF, DKIM, and DMARC authentication.
- Extract Indicators of Compromise (IOCs).
- Analyze the reputation of the source IP.
- Assess phishing risk based on collected evidence.
- Document the complete investigation process.
  

## 🛠️ Tools Used

- MXToolbox Email Header Analyzer
- VirusTotal
- Any.Run
- Urlscan.io
- CyberChef
- EML Analyzer


## 🔍 Investigation Workflow:

### Step 1 – Email Collection
Collected the suspicious email in `.eml` format while preserving the original email headers and metadata.

### Step 2 – Email Header Analysis
Analyzed the email headers to identify the actual sender, return-path, originating IP address, and mail routing information.

### Step 3 – SPF, DKIM & DMARC Verification
Verified email authentication mechanisms to determine sender legitimacy.

### Step 4 – Source IP Extraction
Extracted the originating IP address from the email headers.

### Step 5 – IP Reputation Analysis
Analyzed the extracted IP address using VirusTotal to identify any malicious or suspicious activity.

### Step 6 – IOC Identification
Collected Indicators of Compromise (IOCs) including:
- Sender Email Address
- Return-Path
- Source IP Address
- Suspicious Domain

### Step 7 – Risk Assessment
Performed the final phishing assessment based on all collected evidence.


## 🚨 Key Findings

- Sender information mismatch
- Return-Path inconsistency
- SPF Authentication Failed
- DKIM Signature Missing
- DMARC Validation Failed
- Authentication Compliance Failed
- Suspicious Source IP Address
- Suspicious Domain Identified
- Email classified as a High-Risk Phishing Email


## 💻 Skills Demonstrated

- SOC Analysis
- Phishing Email Investigation
- Email Header Analysis
- IOC Extraction
- Threat Analysis
- Threat Hunting
- Email Authentication Analysis
- Incident Triage
- Risk Assessment
- Security Documentation


## 📂 Repository Structure

Malicious-Email-Phishing-Triage-Analysis/
│
├── README.md
├── Malicious_Email_(Phishing)_&_Triage_Analysis.pdf
└── LICENSE

## 📄 Project Report

The complete investigation report, methodology, screenshots, analysis, and findings are available in:

**Malicious_Email_(Phishing)_&_Triage_Analysis.pdf**


## ✅ Conclusion

The investigation identified multiple phishing indicators, including failed email authentication, suspicious sender infrastructure, malicious network artifacts, and phishing-related indicators.

Based on the collected evidence, the email was classified as a **High-Risk Phishing Email**, demonstrating the standard workflow followed by a SOC Analyst during phishing email triage and investigation.


## 👩‍💻 Author

**Kinjal Varmora**


## ⭐ Disclaimer

This project was created for educational purposes to demonstrate phishing email investigation and SOC analysis techniques. All analysis was performed in a controlled learning environment.**
