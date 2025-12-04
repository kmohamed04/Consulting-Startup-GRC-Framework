# Startup Compliance Framework

This repository provides a complete, real-world Governance, Risk, and Compliance (GRC) framework designed for **Cyverra Consulting**, a hypothetical IT consulting startup. It includes risk management, compliance tracking, security policies, governance documentation, and Power BI dashboards that visualize risk and compliance trends.

The framework aligns with:
- **NIST Cybersecurity Framework (CSF)**
- **CIS Controls v8**


---

## 📁 Repository Structure

```
Startup-Compliance-Framework/
│
├── Risk-Register/
│   └── Risk Register.xlsx
│
├── PowerBI-Dashboards/
│   ├── Risk Dashboard.pbix
│   └── Compliance Dashboard.pbix
│
├── Control-Mapping/
│   ├── NIST-Control-Mapping.xlsx
│   ├── CIS-Control-Mapping.xlsx
│   └── README.md
│
├── Compliance-Checklist/
│   ├── Compliance Checklist.xlsx
│   └── README.md
│
├── Policies/
│   ├── Access-Control-Policy.md
│   ├── Acceptable-Use-Policy.md
│   ├── Asset-Management-Policy.md
│   ├── Backup-and-Recovery-Policy.md
│   ├── Change-Management-Policy.md
│   ├── Data-Classification-Policy.md
│   ├── Incident-Response-Policy.md
│   ├── Incident-Response-Plan.md
│   ├── Network-Security-Policy.md
│   ├── Password-Policy.md
│   ├── Remote-Work-and-Device-Security-Policy.md
│   ├── Risk-Management-Policy.md
│   └── Vendor-Management-Policy.md
│
└── Governance/
    ├── Governance-Charter.md
    ├── Roles-and-Responsibilities.md
    └── Audit-and-Review-Schedule.md
```

---

## 📊 Power BI Dashboards

### **Risk Dashboard**
Shows:
- Risk heatmap (Likelihood × Impact)
- Total risks by category
- Risk owners
- Overall risk score distribution

### **Compliance Dashboard**
Shows:
- % of controls completed
- Compliance by framework (NIST vs CIS)
- Compliance by owner
- Status categories (Not Started, In Progress, Complete)

Both dashboards use the Risk Register and Compliance Checklist as data sources.

---

## 🛡️ Security Policies

The `/Policies` directory contains all core policies required for a functional small-business security program, including:

- Access Control  
- Password Requirements  
- Incident Response  
- Data Classification  
- Remote Work  
- Backup & Recovery  
- Vendor Management  
- Network Security  
- Acceptable Use  
- Risk Management  
- Change Management  
- Asset Management  

These policies support audit readiness and provide structure for daily operations.

---

## 🔐 Control Mapping

The `/Control-Mapping` directory maps internal controls to:
- **NIST CSF** (Identify, Protect, Detect, Respond, Recover)
- **CIS Controls v8** (18 control families)

Each control includes:
- Requirement  
- Owner  
- Status  
- Evidence placeholder  

This ensures full traceability across frameworks.

---

## ✔️ Compliance Checklist

The `/Compliance-Checklist` directory contains the master compliance tracker that consolidates NIST + CIS requirements into one Excel workbook.  
It is designed to support:
- Internal audits  
- Evidence collection  
- Progress tracking  
- Executive reporting  

The checklist feeds the **Compliance Dashboard**.

---

## 🧭 Governance Documents

The `/Governance` folder contains the foundational documents for the program:

- **Governance Charter** – defines governance authority and structure  
- **Roles & Responsibilities** – ownership across all functions  
- **Audit & Review Schedule** – outlines frequencies for control testing, policy updates, and assessments  

These documents establish accountability and long-term sustainability of the GRC program.

---

## 🎯 Purpose of This Project

This framework demonstrates a full end-to-end GRC implementation suitable for:
- Small businesses  
- Consulting startups  
- Portfolio demonstration  
- Interview discussions  
- Real-world governance structure  
- SOC 2 or ISO 27001 readiness (foundational level)  

---

## 📌 How to Use This Repository

1. Review the **Risk Register** to understand organizational risks.  
2. Open **Power BI Dashboards** to view visualized insights.  
3. Explore **Policies** to see the foundational security program.  
4. Use **Control Mapping** + **Compliance Checklist** for audits.  
5. Review **Governance** docs for program management structure.

---

## 📅 Version
**Version 1.0 — Completed GRC Framework**

Future versions may include:
- Evidence repository  
- SOPs (Playbooks)  
- Automated dashboards  
- Third-party security questionnaires  

---



