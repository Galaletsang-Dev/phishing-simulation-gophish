# phishing-simulation-gophish
A complete phishing simulation project using GoPhish on Kali Linux

# Phishing Simulation Using GoPhish on Kali Linux

## 📌 Project Overview

A comprehensive phishing simulation campaign conducted in a controlled lab environment using **GoPhish** on **Kali Linux**. The campaign achieved a **100% success rate**, capturing credentials from all targets within 25 minutes.

## 🎯 Objective

To demonstrate proficiency in threat simulation by creating and executing a realistic phishing campaign to analyze user susceptibility and identify areas for security improvement.

## 🛠️ Tools Used

- **Kali Linux 2025.2** - Attack platform
- **GoPhish** - Phishing framework
- **Postfix 3.11.4** - SMTP email server
- **VirtualBox** - Virtualization
- **SQLite3** - Database

## 📊 Campaign Results

| Metric | Result |
|--------|--------|
| **Emails Sent** | 2 |
| **Email Open Rate** | 100% |
| **Link Click Rate** | 100% |
| **Credential Capture** | 100% |
| **Time to Complete** | 25 minutes |

### Captured Credentials

| Email | Password |
|-------|----------|
| `te**s*p***@***s.com` | `h*******kf` |
| `vi*******0@e****.**m` | `bh******5j` |

## 🔧 Technical Execution

### 1. Environment Setup
- Kali Linux configured on VirtualBox
- System updated and Postfix installed as SMTP server

### 2. Email Template
- Microsoft 365 branded security alert
- Urgent "Unusual Sign-in Activity" theme
- Personalization using `{{.FirstName}}`
- "Verify Your Account" call-to-action

### 3. Landing Page
- Pixel-perfect Microsoft 365 login clone
- Email and password capture fields
- Security warning after submission (educational)

### 4. Sending Profile
- Local Postfix server on `1**.0.*.*:**`
- From: `se******@m***8****.com`

### 5. Campaign Execution
- URL: `http://**.0.2.**`
- Targets: Temporary email addresses from Temp-Mail
- Successfully captured all credentials

## 📁 Project Files

- `/email_template.html` - Phishing email HTML
- `/landing_page.html` - Microsoft 365 clone HTML
- `/campaign_results.csv` - Raw campaign data

## 📸 Screenshots

Screenshots documenting the full process are available in the `/screenshots` folder.

## 📝 Skills Demonstrated

- Social Engineering & Phishing Simulation
- Kali Linux Administration
- Email Infrastructure (Postfix)
- Web Development (HTML/CSS)
- Security Awareness Assessment
- Technical Documentation

## 🧠 AI-Assisted Development

As a beginner in web development, AI tools were leveraged to assist with HTML/CSS coding for the email templates and landing pages. All AI-generated code was reviewed, tested, and customized to meet the specific requirements of the project.

## 📄 Full Report

A comprehensive PDF report with detailed analysis, timeline, and all 20+ screenshots is available in this repository.

## ⚠️ Disclaimer

This project was conducted in a **controlled lab environment** with **explicit consent** from all participants. It is intended for educational purposes only to demonstrate security vulnerabilities and the importance of cybersecurity awareness.

---

**Report Generated:** July 7, 2026  
**Prepared By:** Galaletsang Mpye
