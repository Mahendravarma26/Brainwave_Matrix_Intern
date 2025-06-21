# 🛡️ Phishing URL Scanner

This repository contains all relevant files and documentation related to the **Phishing Link Analysis project** conducted during my **Cybersecurity Internship at Brainwave Matrix Solutions**. The task focused on identifying and analyzing phishing URLs using Python, heuristic analysis, and real-time threat intelligence.

---

## 🧪 Task Objective

Develop a command-line phishing scanner that analyzes a given URL for suspicious traits and verifies its reputation using third-party threat intelligence APIs. The goal was to simulate and detect phishing techniques programmatically and export a readable report of the findings.

---

## 🛠 Tools & Technologies Used

- Python 3.10+
- Requests – For handling HTTP and API requests
- tldextract – For domain parsing and cleaning
- VirusTotal API – To check domain age and reputation
- Command Prompt (Windows Terminal) – For executing the scanner
- UTF-8 Encoding – For safe and consistent report export

---

## 📁 Contents

- `phishing_scanner.py` – Main Python script with all detection logic
- `report.txt` – Generated output file with scan results
- `README.md` – Project documentation
- `screenshots/` – Visual evidence of project execution and analysis

---

## 🔍 Features & Detection Logic

The scanner checks the following indicators to identify phishing attempts:

- Has IP Address – Detects raw IPs used instead of domain names
- Contains @ Symbol – Flags use of `@` to disguise real links
- Is Long URL – Flags if the URL is unusually long
- Has Hyphen in Domain – Identifies use of hyphens in domain (often suspicious)
- Has SSL Certificate – Checks whether the site uses HTTPS
- New Domain Age – Identifies if a domain is newly registered
- VirusTotal Reputation – Uses VirusTotal API to check if the domain is flagged
- Uses URL Shortener – Detects if the URL is shortened using services like bit.ly, tinyurl, etc.

---

## 📊 Outcome

This scanner provides fast detection of potentially harmful URLs using both structural analysis and external reputation scoring. It successfully flags characteristics that are commonly associated with phishing attempts and helps simulate how security software might assess a link.

---

## ✅ Skills Gained

- Threat intelligence integration using VirusTotal API
- Heuristic phishing detection using Python
- URL structure and domain name analysis
- API usage and token authentication
- Writing and exporting formatted reports to `.txt` files
- Real-world simulation of phishing link assessments

---

## 🧾 What I Did

- Designed and implemented a Python-based phishing scanner from scratch
- Added multiple heuristics to analyze various characteristics of a URL
- Integrated the VirusTotal API to check both reputation and domain age
- Handled safe report generation with proper encoding
- Tested the tool with several sample phishing URLs to validate results
- Documented the project and structured it for GitHub release

---

## 📚 What I Learnt

- How phishing links are structured to deceive users
- Programmatic methods to detect suspicious URL patterns
- Use of third-party APIs (VirusTotal) in cybersecurity automation
- Importance of domain parsing and verification
- Real-world application of cybersecurity knowledge in a practical tool
- Troubleshooting encoding issues in file output and script execution

---

## 📎 Tags

`#CyberSecurity` `#PhishingScanner` `#Python` `#VirusTotalAPI` `#URLAnalysis` `#SecurityAutomation` `#InternshipProject`
 #Brainwave Matrix Solutions
