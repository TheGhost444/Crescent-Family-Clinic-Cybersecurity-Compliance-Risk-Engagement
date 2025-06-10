# SIEM Alert Dashboard Mockup
**Organization:** Crescent Family Clinic  
**Document Title:** Mock SIEM Alert Dashboard Overview  
**Prepared By:** Cybersecurity Consultant  
**Effective Date:** June 2025  

---

## Purpose
To provide a visual and textual mockup of a Security Information and Event Management (SIEM) dashboard tailored for a small healthcare clinic, used to monitor and respond to security incidents.

---

## Mock Dashboard Overview

### 👁️ Real-Time Alerts (Past 24 Hours)
| Alert Type | Severity | Count | Status |
|------------|----------|-------|--------|
| Failed Logins (EHR) | Medium | 18 | Investigating |
| Suspicious File Behavior | High | 4 | Contained |
| Unauthorized USB Usage | High | 2 | Escalated |
| Login From Foreign IP | Critical | 1 | Open |
| Admin Privilege Abuse Attempt | High | 1 | Mitigated |

---

### 📊 Top 5 Threat Sources
| Source IP | Location | Alert Type | Attempts |
|-----------|----------|------------|----------|
| 193.56.12.77 | Germany | Foreign Login | 1 |
| 172.16.4.22 | Internal | Failed Logins | 11 |
| 10.0.2.5 | Internal | USB Alert | 2 |
| 45.88.23.90 | Russia | Port Scanning | 7 |
| 66.249.64.12 | USA | Malware Hash Match | 3 |

---

### 🧩 System Status Summary
- **SIEM Engine:** Active
- **Log Sources Monitored:** EHR System, Email Server, Cloud Storage, Endpoint Devices
- **Alerts Triage SLA:** 4 hours (internal), 1 hour (critical)

---

### 📍 Next Actions
- Block external IP 193.56.12.77 at firewall
- Investigate elevated privileges attempt from 10.0.4.99
- Force password reset for users with repeated failed logins
- Export logs related to ransomware hash match for forensic review

---

*This mockup demonstrates a basic SIEM layout for clinic monitoring purposes. Based on industry frameworks like MITRE ATT&CK and NIST CSF.*
