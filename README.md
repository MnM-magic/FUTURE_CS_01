# FUTURE_CS_01
# 🔒 Google Gruyere - Vulnerability Assessment Report

## 📋 Overview

This repository contains a comprehensive vulnerability assessment conducted on **Google Gruyere**, a deliberately vulnerable web application designed for security training. The assessment used **passive, read-only techniques** to identify security weaknesses.

| **Detail** | **Information** |
|------------|-----------------|
| **Target** | https://google-gruyere.appspot.com/592188440301438694072179252835568480719/ |
| **IP Address** | 142.251.216.20 |
| **Assessment Date** | March 31, 2026 |
| **Methodology** | Passive / Read-Only |
| **Tools Used** | Nmap, Chrome DevTools, Firefox DevTools |

---

## 🎯 Scope & Methodology

### Allowed Activities
- ✅ Passive scanning only
- ✅ Public pages only
- ✅ Header analysis
- ✅ Cookie inspection
- ✅ Network monitoring

### Not Allowed
- ❌ No exploitation
- ❌ No login bypass attempts
- ❌ No Denial-of-Service
- ❌ No brute force attacks

---

## 📊 Executive Summary

A total of **8 vulnerabilities** were identified across the application:

| Severity | Count | Issues |
|----------|-------|--------|
| 🔴 **HIGH** | 4 | Insecure cookies, admin exposure, XSS, path traversal |
| 🟡 **MEDIUM** | 3 | Missing security headers, snippet exposure |
| 🟢 **LOW** | 1 | Information disclosure |

## 📄 Full Report
The complete vulnerability assessment report is available here:
👉 Vulnerability_Report.pdf

## 🔐 Ethical Statement
This assessment was conducted in accordance with ethical security testing guidelines:

✅ Passive, read-only techniques only

✅ No exploitation of discovered vulnerabilities

✅ No disruption of services

✅ All testing performed on a deliberately vulnerable training application

## 👤 Author
Mulumbwa Matimelo
https://github.com/MnM-magic
Cyber Security Task 1 (2026) - Future Interns

## 📚 References
- OWASP Top 10
- Google Gruyere Documentation
- Nmap Documentation
