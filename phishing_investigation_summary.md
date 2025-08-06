# 🔐 Phishing Attack Investigation – Summary

**Date:** 05 August 2025  
**Analyst:** [Your Name]

---

## 🧪 Attack Vector:
Email with spoofed Microsoft support domain.

## 🧭 Path of Execution:
1. Victim received and opened phishing email.
2. Clicked on the embedded link → Fake login page.
3. Entered credentials → Exfiltration.
4. PowerShell script triggered → Downloaded malware.

---

## 🧰 Detection:
- Detected failed logins in Windows Event Viewer.
- Matched email in O365 logs using Splunk.
- Observed suspicious PowerShell events.

---

## ✅ Recommendation:
- Block the domain on gateway.
- Force password reset.
- Train user on phishing awareness.
