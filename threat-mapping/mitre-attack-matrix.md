# MITRE ATT&CK Threat Mapping
**Organization:** Crescent Family Clinic  
**Document Title:** Threat Mapping to MITRE ATT&CK Framework  
**Prepared By:** Cybersecurity Consultant  
**Date:** June 2025

---

## Purpose
To map common threats identified during the security assessment of Crescent Family Clinic to the MITRE ATT&CK Framework, helping prioritize detection, response, and SIEM use cases.

---

## Threat Scenarios & ATT&CK Mapping

### 1. **Phishing Attack Leading to Credential Theft**
| ATT&CK Tactic | Technique | ID | Description |
|---------------|-----------|----|-------------|
| Initial Access | Phishing | T1566 | Use of deceptive emails to trick staff into clicking malicious links. |
| Credential Access | Valid Accounts | T1078 | Stolen login credentials reused to access email or EHR. |

### 2. **Unauthorized USB Device Usage**
| ATT&CK Tactic | Technique | ID | Description |
|---------------|-----------|----|-------------|
| Execution | User Execution | T1204 | Staff plugging in personal USB drives with potential malware. |
| Collection | Data Staged | T1074 | Potential data staging prior to exfiltration. |

### 3. **Suspicious Remote Access from Foreign IP**
| ATT&CK Tactic | Technique | ID | Description |
|---------------|-----------|----|-------------|
| Initial Access | Valid Accounts | T1078 | Remote attacker uses stolen credentials. |
| Command and Control | Remote Access Software | T1219 | Use of software like AnyDesk or TeamViewer. |

### 4. **EHR Misuse by Internal Staff**
| ATT&CK Tactic | Technique | ID | Description |
|---------------|-----------|----|-------------|
| Impact | Data Manipulation | T1565.001 | Changing patient records or notes inappropriately. |
| Credential Access | Abuse Elevation Control Mechanism | T1548 | Unauthorized privilege escalation. |

### 5. **Ransomware Attack Attempt**
| ATT&CK Tactic | Technique | ID | Description |
|---------------|-----------|----|-------------|
| Execution | Command and Scripting Interpreter | T1059 | Use of scripts for payload execution. |
| Impact | Data Encrypted for Impact | T1486 | Encrypting files to demand ransom. |
| Persistence | Boot or Logon Autostart Execution | T1547 | Establishing malware persistence. |

---

## Application
These mappings are intended to:
- Inform SIEM alert logic
- Support future MDR/XDR integrations
- Enhance tabletop exercises
- Prioritize training and phishing simulations

---

*Source: [MITRE ATT&CK Navigator](https://attack.mitre.org/). This mapping reflects common healthcare threats based on HIPAA breach data and small clinic risk assessments.*
