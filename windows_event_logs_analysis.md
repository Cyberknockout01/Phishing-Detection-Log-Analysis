# 📝 Windows Event Logs Analysis

### 🚩 Key Events:

- **Event ID 4625** – Failed login attempts at odd hours
- **Event ID 4688** – Suspicious process spawned (`powershell.exe` running script from temp folder)
- **Event ID 4720** – New user account created (possible persistence)
- **Event ID 4104** – PowerShell script block logging (enabled)

### 🔎 Investigation Summary

- Timestamps matched the phishing email open time.
- PowerShell was used to download payload.
- User clicked on a malicious link from email.
