# Password Policy

## 1. Purpose
This policy establishes requirements for creating, managing, and protecting passwords used to access company systems, applications, and cloud services.

## 2. Scope
This policy applies to:

- All employees, interns, and contractors
- All systems, SaaS applications, and cloud services
- Any device used to access company resources

## 3. Password Requirements

### Complexity
All user passwords must meet the following minimum requirements:

- At least 12 characters long  
- Must include at least three of the following:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters  
- Must not contain personal information (name, birthday, username)

### Reuse
- Passwords must not be reused across company systems.  
- Passwords must not match the last 5 previously used passwords.

### Expiration
- Passwords must be changed every 180 days.  
- High-privilege accounts (admin, root, security roles) must be changed every 90 days.

### Default Passwords
- Default passwords must be changed immediately upon first login.  
- Systems with unchanged default credentials must not be placed into production.

## 4. Multi-Factor Authentication (MFA)
- MFA is required for all cloud services, VPN access, and critical systems.  
- High-privilege accounts must use MFA at all times.

## 5. Password Storage

### Users
- Passwords must not be written down or stored in plain text.  
- Employees must use the approved company password manager.

### Systems
- Passwords stored by systems must be hashed using modern algorithms such as bcrypt, scrypt, or Argon2.  
- Passwords must never be stored or logged in clear text.

## 6. Account Lockout
To reduce brute-force attempts:

- Accounts must lock after 10 failed login attempts.  
- Lockout duration: 15 minutes or until reset by IT Administrator.

## 7. Roles and Responsibilities

### IT Administrator
- Enforces password policies in all systems.  
- Monitors login failures and suspicious activity.

### Security Lead
- Reviews and updates this policy annually.  
- Approves exceptions when necessary.

### Employees
- Follow all password requirements.  
- Report compromised accounts immediately.

## 8. Enforcement
Policy violations may lead to disciplinary action, including access removal or termination.

