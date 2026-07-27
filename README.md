# 📧 Email Threat Investigation & Analysis

> A Security Operations Center (SOC)-style investigation into suspicious emails using email header analysis, threat intelligence, and OSINT techniques.

![Project](https://img.shields.io/badge/Project-Cybersecurity-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Case File](https://img.shields.io/badge/Case%20File-CA--ETI--01-orange)

---

## 📖 Overview

Email remains one of the most common attack vectors used by cybercriminals. This project documents the investigation of **13 suspicious emails** to determine whether they were legitimate, phishing attempts, Business Email Compromise (BEC), spam, or malicious campaigns.

Each email was examined using a structured investigation process that included:

- Email Header Analysis
- Authentication Checks (SPF, DKIM, DMARC)
- Sender Reputation Analysis
- Reply-To Validation
- IOC Extraction
- OSINT Investigations
- Threat Classification
- Risk Assessment
- Security Recommendations

This project demonstrates the analytical workflow and documentation style commonly used by Security Operations Center (SOC) analysts.

---

## 🎯 Objectives

- Investigate suspicious emails using industry-standard methodologies.
- Validate sender authenticity.
- Detect phishing and Business Email Compromise (BEC) attacks.
- Identify Indicators of Compromise (IOCs).
- Produce a professional incident investigation report.

---

## 🛠️ Skills Demonstrated

- Email Security Analysis
- Email Header Investigation
- Phishing Detection
- Business Email Compromise (BEC) Analysis
- Threat Intelligence
- Open Source Intelligence (OSINT)
- IOC Identification
- Incident Response Documentation
- Risk Assessment
- Technical Report Writing

---

## 🔧 Tools Used

| Tool | Purpose |
|------|----------|
| VirusTotal | File, URL & Domain Reputation |
| MXToolbox | Email Authentication & DNS Analysis |
| WHOIS Lookup | Domain Ownership Investigation |
| Hunter.io | Email Verification |
| Email Header Analyzer | Email Header Parsing |
| Google OSINT | Infrastructure & Threat Research |

---

## 🔍 Investigation Workflow

```text
Suspicious Email
        │
        ▼
Header Analysis
        │
        ▼
SPF / DKIM / DMARC Validation
        │
        ▼
Reply-To & Sender Verification
        │
        ▼
IOC Extraction
        │
        ▼
Threat Intelligence Lookup
        │
        ▼
Risk Assessment
        │
        ▼
Incident Classification
        │
        ▼
Recommendations
```

---

## 🚨 Threats Identified

The investigation identified multiple attack techniques, including:

- Phishing
- Business Email Compromise (BEC)
- Credential Harvesting
- Lottery Scams
- Recruitment Scams
- Brand Impersonation
- Malicious URLs
- Suspicious Domains

---

## 📊 Key Findings

- Investigated **13 suspicious email samples**.
- Verified SPF, DKIM, and DMARC authentication records.
- Identified suspicious Reply-To mismatches.
- Extracted and documented Indicators of Compromise (IOCs).
- Distinguished between technically authenticated emails and socially engineered attacks.
- Produced actionable security recommendations.

---

## 📂 Repository Structure

```text
Email-Threat-Investigation/
│
├── README.md
├── Email_Threat_Investigation_Report.pdf
├── Screenshots/
│   ├── sample1.png
│   ├── sample2.png
│   └── sample3.png
└── LICENSE
```

---

## 📄 Report

The complete investigation report is available in this repository:

**📄 Email_Threat_Investigation_Report.pdf**

---

## 📚 Lessons Learned

This project reinforced the importance of:

- Looking beyond SPF, DKIM, and DMARC results.
- Investigating Reply-To inconsistencies.
- Combining technical evidence with contextual analysis.
- Using multiple OSINT sources before reaching conclusions.
- Documenting investigations in a structured SOC report.

---

## 🚀 Future Improvements

- Automate email header analysis using Python.
- Integrate VirusTotal API for automated reputation checks.
- Develop IOC extraction scripts.
- Build an automated phishing detection workflow.
- Visualize findings using a SOC dashboard.

---

## 👨‍💻 About Me

I'm **Chinedu Okoli**, an aspiring SOC Analyst passionate about Blue Team operations, Threat Detection, Incident Response, and Security Operations.

I'm continuously building hands-on cybersecurity projects to strengthen my technical skills and prepare for a career in cybersecurity.

**GitHub:** https://github.com/chinedu-okoli07

**LinkedIn:** *(Add your LinkedIn profile here)*

---

## ⭐ Support

If you found this project helpful or interesting, consider giving the repository a ⭐ and feel free to connect with me as I continue documenting my cybersecurity journey.
