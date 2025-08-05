
# 🛡️ Security Audit Lab: Botium Toys

## 📌 Objective
Conduct an internal security audit to identify risks, threats, and vulnerabilities that may impact Botium Toys’ business continuity and critical assets.

---

## 🏢 Company Scenario

**Botium Toys** is a small U.S. company that designs and sells toys. It operates from a single physical location that includes offices, a storefront, and a warehouse. Due to growing online demand, the IT department is now under pressure to support global operations.

The IT manager has initiated a security audit to ensure the organization can continue to scale safely, remain compliant with U.S. and E.U. standards, and protect sensitive data.

---

## 🎯 Scope and Goals

### **Scope**
The entire security program at Botium Toys, including internal systems, devices, software, network infrastructure, and physical security.

### **Goals**
- Evaluate existing IT assets and current security posture.
- Complete a controls and compliance checklist.
- Identify gaps and recommend solutions to enhance compliance and mitigate risks.

---

## 💾 Assets Managed by IT

- On-premises employee equipment (desktops, laptops, smartphones, workstations, etc.)
- Retail and warehouse inventory (online and physical)
- Core systems: accounting, telecommunication, security, ecommerce, inventory, etc.
- Internal network and internet access
- Data storage and retention systems
- Legacy systems requiring manual maintenance

---

## ⚠️ Risk Assessment Summary

| **Category** | **Details** |
|--------------|-------------|
| **Asset Management** | Incomplete and lacks classification |
| **Controls** | Many essential controls not in place |
| **Compliance** | Gaps in U.S. and E.U. regulations (PCI DSS, GDPR, SOC) |
| **Risk Score** | 8/10 (High) |
| **Potential Impact** | Medium due to uncertainty around asset exposure |
| **Fines/Data Risk** | High due to lack of compliance and controls |

---

## ✅ Controls Assessment Checklist

| Control | In Place | Explanation |
|--------|:--------:|-------------|
| Least Privilege | ❌ | All employees have access to customer data. |
| Disaster Recovery Plans | ❌ | No plans in place. |
| Password Policies | ❌ | Requirements are weak and outdated. |
| Separation of Duties | ❌ | CEO handles payroll and operations. |
| Firewall | ✅ | Active and rules are well defined. |
| Intrusion Detection System (IDS) | ❌ | Not implemented. |
| Backups | ❌ | No backup strategy in place. |
| Antivirus Software | ✅ | Installed and actively monitored. |
| Legacy System Monitoring | ❌ | Maintained without a regular schedule. |
| Encryption | ❌ | Not in use. |
| Password Management System | ❌ | Not implemented. |
| Physical Locks | ✅ | Sufficient physical security. |
| CCTV Surveillance | ✅ | Operational. |
| Fire Detection/Prevention | ✅ | Up-to-date systems installed. |

---

## ⚖️ Compliance Checklist

### **PCI DSS**

| Best Practice | In Place | Explanation |
|---------------|:--------:|-------------|
| Restricted access to credit card info | ❌ | All employees have access. |
| Secure processing/storage of card data | ❌ | Unencrypted and poorly managed. |
| Use of encryption for credit card data | ❌ | Not implemented. |
| Secure password policies | ❌ | No enforcement or central management. |

### **GDPR**

| Best Practice | In Place | Explanation |
|---------------|:--------:|-------------|
| Protect E.U. customer data | ❌ | Encryption not used. |
| 72-hour breach notification | ✅ | Plan exists. |
| Data classification and inventory | ❌ | Assets listed, not classified. |
| Enforced privacy policies | ✅ | Implemented across teams. |

### **SOC Type 1 & 2**

| Best Practice | In Place | Explanation |
|---------------|:--------:|-------------|
| User access policies | ❌ | Least Privilege and SoD not in place. |
| Data confidentiality (PII/SPII) | ❌ | No encryption. |
| Data integrity | ✅ | Ensured through IT systems. |
| Data access control | ❌ | Access not restricted based on roles. |

---

## 💡 Recommendations

To improve Botium Toys’ security and compliance posture:

- Implement controls: **Least Privilege**, **Separation of Duties**, **Encryption**, **Disaster Recovery**, and **Password Management**.
- Establish a **structured monitoring schedule** for legacy systems.
- Enforce **password complexity policies**.
- Classify IT assets and apply **role-based access control (RBAC)**.
- Ensure encryption is used for storing and transmitting sensitive customer data.
- Conduct regular audits and train employees on privacy best practices.
