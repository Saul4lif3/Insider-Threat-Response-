# Risk and Incident Response Plan
## University Insider Threat Scenario – Finance Department

### 1. Purpose
This plan outlines the steps to identify, contain, respond to, and recover from unauthorized access to the university payroll system.

### 2. Scope
Applies to:
- Finance staff
- Payroll systems
- IT & Security teams
- Internal staff accounts

---

## 3. Risk Assessment

### 3.1 Threats
- Insider misuse
- Credential theft
- Brute-force attempts
- Social engineering or phishing

### 3.2 Vulnerabilities
- Weak passwords
- No MFA in place
- Passwords written on sticky notes
- Lack of monitoring/alerts
- No training on phishing

### 3.3 Impact (CIA Triad)
| Area | Risk | Description |
|------|------|-------------|
| Confidentiality | High | Exposure of payroll data |
| Integrity | Medium | Unauthorized changes possible |
| Availability | Medium | System disruptions during containment |

**Overall Risk Level: High**

---

## 4. Response Plan (NIST Lifecycle)

### 4.1 Detection
- Log alerts flagged late-night access
- Verified staff member was not online
- Investigated failed login attempts and IP behavior

### 4.2 Containment
- Locked affected account
- Reset passwords campus-wide for finance
- Disabled remote access until MFA enabled
- Blocked suspicious IPs/devices

### 4.3 Eradication
- Removed unauthorized sessions
- Scanned endpoints for malware
- Eliminated stored credential notes
- Activated monitoring rules for unusual behavior

### 4.4 Recovery
- Restored payroll access
- Enabled MFA for all users
- Verified data integrity
- Implemented updated access controls

### 4.5 Lessons Learned
- Enforce password hygiene
- Require MFA everywhere
- Expand user training
- Improve automated alerting
- Conduct periodic audits

---

## 5. Preventive Controls

### Access Control
- Strong passwords (12+ characters)
- MFA required
- Least privilege enforcement
- Quarterly access reviews

### Network Controls
- SIEM monitoring
- IDS/IPS deployment
- After-hours alerting

### Training
- Semesterly phishing awareness training
- Credential protection guidelines

### Policies
- Updated Access Control Policy
- Updated Password Policy
- After-hours access logging rules

---

## 6. Summary
This plan reduces unauthorized access risk by strengthening access controls, improving user behavior, and enforcing continuous security monitoring.
