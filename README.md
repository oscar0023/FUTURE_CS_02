# Phishing Email Detection & Awareness Project

## Overview

This project focuses on the **detection and analysis of phishing emails** and the development of **user awareness guidelines** to reduce phishing risks.

Phishing attacks remain one of the most common cyber threats. This project demonstrates how suspicious emails can be analyzed using technical indicators such as **email headers, domain inspection, and authentication mechanisms**.

The goal is to identify phishing attempts and classify email risks while promoting cybersecurity awareness.

---

## Project Objectives

* Analyze real or simulated phishing emails
* Identify phishing indicators
* Perform email header analysis
* Classify emails according to risk level
* Provide prevention and awareness guidelines

---

## Methodology

The analysis process follows these main steps:

1. **Email Collection**
   A dataset containing both phishing and legitimate emails was gathered for analysis.

2. **Email Header Analysis**
   Email headers were examined to identify:

   * Sender IP address
   * SMTP servers
   * Message transmission path

3. **Domain and Link Inspection**
   Suspicious links and domains were analyzed to detect:

   * fake or recently registered domains
   * typosquatting attempts
   * malicious URLs

4. **Phishing Indicator Identification**
   Indicators such as urgency, impersonation, and suspicious links were identified.

5. **Risk Classification**
   Emails were classified into three categories:

   | Risk Level | Description        |
   | ---------- | ------------------ |
   | Low        | Legitimate email   |
   | Medium     | Suspicious email   |
   | High       | Confirmed phishing |

---

## Tools Used

The following tools were used during the analysis:

* MXToolbox – Email header analysis
* Google Admin Toolbox Messageheader – Header parsing
* VirusTotal – Domain and URL reputation analysis
* GitHub – Project documentation and evidence storage

---

## Key Phishing Indicators Identified

| Indicator                 | Description                                    |
| ------------------------- | ---------------------------------------------- |
| Suspicious domains        | Domains impersonating legitimate organizations |
| Authentication failures   | SPF, DKIM, or DMARC errors                     |
| Urgency language          | Messages encouraging immediate action          |
| Typosquatting             | Domains similar to legitimate ones             |
| Suspicious infrastructure | Unusual message headers or sending servers     |

---

## Example Findings

Some analyzed emails showed strong phishing indicators such as:

* domain impersonation (e.g. fake Microsoft domains)
* missing email authentication (SPF, DKIM, DMARC)
* urgent financial or security alerts
* suspicious sender infrastructure

These indicators suggest phishing attempts targeting users.

---

## Prevention & Awareness Guidelines

To reduce phishing risks, organizations should implement:

### Technical Measures

* Email filtering systems
* Multi-Factor Authentication (MFA)
* Automated email threat detection

### User Awareness

* Regular phishing awareness training
* Phishing simulation exercises
* Clear procedures for reporting suspicious emails

---

## Conclusion

This project highlights how **email analysis techniques and cybersecurity awareness** can help detect phishing attacks and protect users from credential theft and fraud.

Combining **technical detection methods and user education** is essential for reducing phishing risks.

---

## Author

Oscar Alotchéwou ALIDJINOU
Cybersecurity Student
