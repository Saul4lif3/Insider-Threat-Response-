# Incident Report
## Scenario: Insider Threat Response at a University

### 1. Overview
The university’s finance department detected suspicious late-night logins to the payroll system using an internal staff account. These access attempts occurred outside normal business hours and were made from an unrecognized device, triggering a security alert.

### 2. Incident Description
Multiple failed login attempts were observed, followed by a successful login. The staff member associated with the account confirmed they were not online at the time. The event suggested potential credential compromise or insider misuse.

### 3. Investigation Findings
- The account showed unusual after-hours access.
- Password hygiene practices were poor (sticky notes, reused passwords).
- No multi-factor authentication (MFA) was enabled.
- Potential exposure to phishing or social engineering attempts.

### 4. Root Cause
The probable root cause was compromised staff credentials due to weak password practices or phishing attacks. The absence of MFA allowed unauthorized access using stolen credentials.

### 5. Impact
- **Confidentiality Risk:** Payroll data contains SSNs, banking info, salaries.
- **Integrity Risk:** Possibility of unauthorized data manipulation.
- **Availability Impact:** Payroll system was temporarily restricted during investigation.

### 6. Actions Taken
- Locked the compromised account.
- Reset passwords for finance users.
- Initiated a detailed log and network traffic review.
- Verified data integrity.
- Introduced temporary monitoring and access restrictions.

### 7. Conclusion
Unauthorized access was likely caused by credential compromise. Stronger access control, employee training, and MFA enforcement are required to prevent recurrence.
