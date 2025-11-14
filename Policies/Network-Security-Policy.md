# Network Security Policy

## 1. Purpose
This policy establishes the security requirements for protecting the company’s network infrastructure, cloud environments, and connected devices. The goal is to prevent unauthorized access, detect malicious activity, and maintain the confidentiality, integrity, and availability of systems and data.

## 2. Scope
This policy applies to:

- All corporate networks, cloud networks, and VPN services  
- All employees, contractors, interns, and third parties accessing the network  
- All devices connected to company systems (laptops, mobile devices, servers)  

## 3. Network Security Requirements

### 3.1 Network Segmentation
- Systems storing Confidential data must be isolated in restricted network segments.  
- Administrative systems must be separated from user networks.  
- Guest Wi-Fi must remain isolated from internal systems.

### 3.2 Firewall Rules
- Firewalls must be enabled on all network edges and devices.  
- Only necessary ports and services may be allowed.  
- Changes to firewall rules require approval through the Change Management process.  
- Logs must be retained for at least 90 days.

### 3.3 VPN Requirements
- Remote users must connect via a company-approved VPN.  
- Multi-factor authentication (MFA) must be enabled.  
- Split tunneling is disabled unless explicitly approved.

### 3.4 Intrusion Detection & Monitoring
- Network and cloud logs must be monitored for suspicious activity.  
- Alerts must be reviewed daily by the Security Lead or IT Administrator.  
- High-severity alerts must be investigated immediately.

## 4. Device Security Requirements

### 4.1 Endpoint Protection
All connected devices must have:
- Updated antivirus/anti-malware  
- Automatic updates enabled  
- Endpoint monitoring software installed  

### 4.2 Configuration Standards
- Default passwords must be changed immediately.  
- Devices must comply with security baselines before connecting to the network.  
- Unsupported or jailbroken devices are prohibited.

### 4.3 Network Access Control
- Only authorized devices may join the network.  
- Unknown devices must be blocked and reported.  
- Access must follow the least-privilege principle.

## 5. Wireless Security

### Corporate Wi-Fi
- WPA3 encryption must be used when available.  
- Hidden SSIDs are not considered a security control.  
- Passwords must be rotated at least every 180 days.

### Guest Wi-Fi
- Must be isolated from all corporate networks.  
- Bandwidth throttling may be enforced to preserve performance.

## 6. Cloud Network Security
- Cloud environments must use network security groups (NSGs), firewalls, or equivalent controls.  
- Unused services, ports, and public IPs must be disabled.  
- Cloud admin actions must be logged centrally.

## 7. Roles and Responsibilities

### IT Administrator
- Maintains firewalls, VPN, and network configurations  
- Monitors logs and responds to alerts  
- Tracks approved devices and enforces access rules  

### Security Lead
- Conducts risk assessments on network changes  
- Reviews high-severity alerts  
- Approves access to restricted network segments  

### Employees
- Follow secure network usage requirements  
- Report suspicious network behavior  
- Do not connect unauthorized devices  

## 8. Incident Handling
Network incidents must follow the Incident Response Plan, including:
- Identification  
- Containment  
- Eradication  
- Recovery  
- Lessons learned  

## 9. Enforcement
Violations of this policy may result in revoked access, disciplinary action, or termination. Severe violations may result in legal action.

