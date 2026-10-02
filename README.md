# NETWORKWALKS-B083-WK4-PM-FINAL-PENETRATION-TESTING
# Networkwalks Cybersecurity Internship – Week 4

## Penetration Testing – Mediroza General Hospital

This repository contains my work and documentation for **Week 4** of the Networkwalks Cybersecurity Internship.

The task involved performing an authorized **black-box penetration test** against the Mediroza General Hospital web application in a controlled educational environment.

## Objective

The objective of the assessment was to identify security weaknesses that could allow unauthorized access to restricted files or sensitive information, demonstrate their impact, and document the findings with appropriate remediation recommendations.

## Activities Performed

* Tested the application's login functionality for SQL injection vulnerabilities.
* Obtained access to restricted laboratory report PDF files.
* Analyzed the protection applied to the recovered PDF files.
* Recovered the passwords required to access the encrypted PDF files.
* Examined the target website's `robots.txt` file.
* Discovered an exposed database backup.
* Analyzed the database structure and identified sensitive staff and shareholder information.
* Documented the findings, evidence, risk ratings, and remediation recommendations.

## Tools Used

* Kali Linux
* OnlineHashCrack
* Networkwalks Network Cracker

## Key Findings

The assessment identified the following security issues:

1. **SQL Injection in Login Functionality**
   The application's authentication mechanism was vulnerable to SQL injection, resulting in unauthorized access to restricted laboratory reports.

2. **Weak Protection of Encrypted PDF Files**
   The passwords protecting the recovered PDF files were successfully recovered, allowing access to their contents.

3. **Exposed Database Backup**
   A database backup was accessible through the target website and contained sensitive staff and shareholder information.

## Risk Assessment

The identified findings included **Critical** and **High** risk issues due to their potential to result in unauthorized access and exposure of confidential information.

## Remediation

The report includes recommendations covering:

* Secure SQL query handling using parameterized queries.
* Improved protection of sensitive files.
* Stronger password and encryption practices.
* Proper access controls for database backups.
* Removal of sensitive files from publicly accessible web directories.
* Regular security testing and exposure reviews.

## Report

The complete penetration testing report is included in this repository.

> **Note:** Sensitive information and confidential evidence obtained during the authorized assessment have not been publicly uploaded.

## Disclaimer

This assessment was performed as part of an authorized cybersecurity internship project in a controlled educational environment. The techniques and activities documented in this repository were conducted only against the authorized target and within the defined scope.
