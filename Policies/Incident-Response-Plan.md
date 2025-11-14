# Incident Response Plan (IRP)

## 1. Purpose
This plan provides detailed steps for detecting, reporting, analyzing, containing, eradicating, and recovering from cybersecurity incidents. The goal is to minimize damage, restore operations quickly, and support effective communication.

## 2. Scope
This plan applies to:

- All employees, contractors, and interns  
- All systems, cloud services, and devices  
- Any security event impacting confidentiality, integrity, or availability  

## 3. Incident Response Team (IRT)

### Security Lead – Incident Commander
- Coordinates incident response  
- Makes containment decisions  
- Communicates with leadership  
- Directs investigation activities  

### IT Administrator – Technical Operator
- Performs system isolation, account disabling, and log collection  
- Executes recovery and restoration steps  
- Supports evidence gathering  

### Compliance Manager – Documentation Lead
- Ensures incident documentation is completed  
- Oversees regulatory and client notifications  
- Tracks remediation actions  

### Department Managers – Business Impact Support
- Provide operational information  
- Assist in restoring affected processes  

## 4. Incident Categories

### Category 1 – High Severity
- Data breach or confirmed unauthorized access  
- Ransomware or major malware outbreak  
- Critical system outage due to malicious activity  

### Category 2 – Medium Severity
- Suspicious login attempts  
- Phishing compromise  
- Localized malware infection  

### Category 3 – Low Severity
- Policy violations  
- Minor misconfigurations  
- Non-critical user errors  

## 5. Incident Response Process

### 5.1 Identification
- Detect suspicious system activity through logs, alerts, or user reports  
- Verify the event and classify its severity  
- Document the initial findings  

### 5.2 Containment
Short-term:
- Disable compromised accounts  
- Disconnect affected devices  
- Block malicious IPs or domains  

Long-term:
- Apply temporary firewall rules  
- Add identity-based restrictions  
- Increase logging and monitoring  

### 5.3 Eradication
- Remove malware, backdoors, or rogue user accounts  
- Patch vulnerabilities  
- Reset compromised credentials  
- Validate that no additional malicious activity is present  

### 5.4 Recovery
- Restore systems from backups  
- Re-enable normal network access  
- Monitor systems for re-infection  
- Validate system integrity  

### 5.5 Lessons Learned
Within **5 business days** of closing the incident:
- Document root cause  
- Identify control failures  
- Update policies and procedures  
- Conduct a short review meeting with team leads  

## 6. Communication Guidelines
- Only the Security Lead or executive leadership may communicate externally  
- Internal communication must be limited to individuals involved  
- Sensitive details must not be shared outside the IRT  

## 7. Evidence Handling
- Preserve logs, screenshots, email headers, and system images  
- Store evidence securely in a restricted-access folder  
- Maintain chain-of-custody documentation when applicable  

## 8. Reporting and Documentation
A full incident report must include:

- Date/time of detection  
- Incident classification  
- Systems and accounts affected  
- Actions taken during each phase  
- Root cause analysis  
- Recommendations for improvement  

## 9. Enforcement
Failure to follow this plan may result in disciplinary action or removal of access privileges.

