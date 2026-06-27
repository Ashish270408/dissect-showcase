# 🛡️ Dissect

<p align="center">
  <img src="assets/logo.png" alt="Dissect Logo" width="180">
</p>

<p align="center">
<b>Modern Web Vulnerability Scanner</b><br>
Professional • Educational • Security Focused
</p>

<p align="center">

![Version](https://img.shields.io/badge/version-v0.9--beta-blue)
![Status](https://img.shields.io/badge/status-Beta-success)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.x-black?logo=flask)
![License](https://img.shields.io/badge/license-MIT-green)

</p>

---

## 🌐 Live Demo

**https://dissect.up.railway.app/**

---

## 📖 Overview

Dissect is a web-based vulnerability scanner built to help developers, students, and security enthusiasts identify common security misconfigurations in web applications.

The scanner analyzes publicly accessible web resources and presents findings through two complementary reports:

* **Executive Report** – High-level security overview for quick assessment.
* **Technical Report** – Detailed findings with associated risks and recommendations.

The project focuses on providing meaningful security insights through a clean and intuitive interface rather than overwhelming users with raw scanner output.

---

# ✨ Features

## HTTP Security Analysis

* Detect missing security headers
* Analyze response headers
* Redirect analysis
* Response information collection

---

## Cookie Security

* Secure Flag validation
* HttpOnly detection
* SameSite analysis
* Session cookie inspection

---

## Form Analysis

* Login Forms
* Registration Forms
* Contact Forms
* Search Forms
* Password Reset Forms

---

## Risk Assessment

* Missing Header Detection
* Severity Classification
* Risk Explanation
* Security Recommendations

---

## Reporting

* Executive Report
* Technical Report
* Structured Findings
* Easy-to-read Security Summary

---

## User Interface

* Responsive Design
* Clean Modern UI
* Fast Scan Workflow
* Mobile Friendly

---

# 📸 Screenshots

## Home

![Homepage](screenshots/home.png)

---

## Executive Report

![Executive Report](screenshots/executive-report.png)

---

## Technical Report

![Technical Report](screenshots/technical-report.png)

---

# 🏗️ High-Level Architecture

```text
                    User
                      │
                      ▼
            Flask Web Application
                      │
                      ▼
               Scanning Engine
                      │
        ┌─────────────┼─────────────┐
        │             │             │
        ▼             ▼             ▼
   Header Scan   Cookie Scan   Form Analysis
        │             │             │
        └─────────────┼─────────────┘
                      ▼
              Risk Assessment
                      │
                      ▼
            Report Generation
                      │
        ┌─────────────┴─────────────┐
        ▼                           ▼
 Executive Report           Technical Report
```

---

# 🛠️ Technology Stack

| Category           | Technologies          |
| ------------------ | --------------------- |
| Backend            | Python, Flask         |
| Frontend           | HTML, CSS, JavaScript |
| HTTP Analysis      | Requests              |
| HTML Parsing       | BeautifulSoup         |
| Browser Automation | Playwright            |
| Parsing            | lxml                  |

---

# 🚀 Why Dissect?

Dissect was developed as a practical cybersecurity project to demonstrate modern web application security analysis through an intuitive interface and structured reporting.

Instead of acting as a penetration testing framework, Dissect emphasizes understanding common security issues and presenting them in a format that is accessible to both technical and non-technical audiences.

---

# 🗺️ Roadmap

## Version 1.0

* ✅ Security Header Analysis
* ✅ Cookie Analysis
* ✅ Form Analysis
* ✅ Executive Reports
* ✅ Technical Reports

---

## Planned Features

* SSL/TLS Certificate Analysis
* robots.txt Analysis
* sitemap.xml Analysis
* DNS Information
* WHOIS Information
* PDF Report Export
* Scan History
* User Dashboard
* Scheduled Scans

---

# ⚠️ Responsible Usage

Dissect is intended for educational purposes and authorized security assessments only.

Only scan systems that you own or have explicit permission to test.

The developers assume no responsibility for misuse of this software.

---

# 🔒 Source Code

The production source code is maintained in a private repository.

This public repository serves as the official project page containing documentation, updates, and information about Dissect.

---

# 📄 License

This project is licensed under the MIT License.

---

<p align="center">

Made with ❤️ for the cybersecurity community.

</p>
