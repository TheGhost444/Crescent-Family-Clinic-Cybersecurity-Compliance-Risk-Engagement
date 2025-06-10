# Google Workspace Security Audit Template
**Organization:** Crescent Family Clinic  
**Document Title:** Google Workspace Security Audit Checklist  
**Prepared By:** Cybersecurity Consultant  
**Effective Date:** June 2025  

---

## Purpose
To ensure Crescent Family Clinic’s Google Workspace environment adheres to best security practices for HIPAA compliance, data integrity, and operational resilience.

---

## Audit Checklist
| Category | Checkpoint | Status | Notes |
|----------|------------|--------|-------|
| **Access Management** | MFA enabled for all users | ✅ | Enforced via Admin Console |
| | OAuth app access restricted | ✅ | Limited to approved apps only |
| | Review of inactive accounts | 🔄 | Scheduled monthly |
| **Data Protection** | Drive sharing restricted to org domain | ✅ | External sharing disabled |
| | DLP policies enabled for PHI detection | 🔲 | In planning phase |
| | Encryption at rest & transit | ✅ | Managed by Google by default |
| **Audit & Monitoring** | Admin audit log enabled | ✅ | Logs retained for 180 days |
| | Alert center configured | ✅ | Alerts forwarded to IT Admin |
| | Email forwarding rules audited | 🔄 | Monthly reviews scheduled |
| **App Control** | 3rd-party marketplace apps reviewed | ✅ | Reviewed quarterly |
| | Chrome browser extension policy set | 🔲 | Needs review and enforcement |
| **Incident Response** | Security alert routing set up | ✅ | Routed to cybersecurity consultant |
| | User-reported phishing workflow tested | ✅ | Via Gmail Report Phishing button |

---

## Audit Frequency
- Full audit conducted **quarterly**.
- Monthly spot checks for email and access logs.

---

*Based on Google Workspace Admin Best Practices and NIST 800-53 Controls.*
