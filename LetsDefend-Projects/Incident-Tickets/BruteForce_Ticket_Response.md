# 🛡️ Brute Force Attack - Ticket Analysis

**📅 Date:** 2025-05-16  
**🔎 Analyst:** Yanis Deriche  
**🎯 Case Type:** Unauthorized Login Attempt (Brute Force)  
**🔍 Platform:** LetsDefend

---

## 🧠 Summary

A brute force login attempt was detected targeting the internal mail server.  
Thousands of login attempts from suspicious IPs triggered SIEM alerts.

---

## 📊 Key Indicators

- 🚨 Excessive failed login attempts from IP: `192.0.2.66`
- 🕒 Spike in traffic at `03:45 UTC`
- 📁 Target system: `mail.internal.corp`

---

## 🛠️ Tools Used

- SIEM (LetsDefend)
- MITRE ATT&CK Mapping
- IP Lookup (AbuseIPDB)
- WHOIS

---

## 🎯 Response Actions

- Blocked IP `192.0.2.66` via firewall
- Reset credentials for targeted accounts
- Reviewed login security policy

---

## 🧬 MITRE Mapping

| Tactic            | Technique               | ID         |
|-------------------|--------------------------|------------|
| Credential Access | Brute Force              | T1110.001  |
| Initial Access    | Valid Accounts           | T1078      |



---

## ✅ Resolution

- Ticket Closed
- User accounts monitored
- Logs archived

