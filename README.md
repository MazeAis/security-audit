# Security Audit Lab – Botium Toys

## Objective
You will conduct an internal security audit  
(*Audits help ensure that security checks are made, to monitor for threats, risks, or vulnerabilities that can affect an organization’s business continuity and critical assets*)

---

## Scenario
This scenario is based on a fictional company:

**Botium Toys** is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.  
The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The IT manager starts by implementing the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)**, establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment.  
**The goal of the audit** is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

---

## Assessment:
### Botium Toys: Scope, Goals, and Risk Assessment Report

#### Scope and Goals of the Audit

- Scope: The entire security program at Botium Toys including employee equipment/devices, internal network, and systems.  
- Goals: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve security posture.

---

## Current Assets

- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras  
- Storefront products for retail sale (onsite and online); stored in an adjoining warehouse  
- Systems/software/services: accounting, telecommunication, database, security, ecommerce, and inventory management  
- Internet access  
- Internal network  
- Data retention and storage  
- Legacy system maintenance: end-of-life systems requiring human monitoring  

---

## Risk Assessment

Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 
Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

---

## ✅ Controls Assessment Checklist

| Control | In Place | Explanation |
|--------|:--------:|-------------|
| **Least Privilege** | ❌ No | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
| **Disaster Recovery Plans** | ❌ No | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
| **Password Policies** | ❌ No | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data. |
| **Separation of Duties** | ❌ No | Needs to be implemented to reduce the risk of fraud; the CEO currently handles daily operations and payroll. |
| **Firewall** | ✅ Yes | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| **Intrusion Detection System (IDS)** | ❌ No | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
| **Backups** | ❌ No | The IT department needs to have backups of critical data to ensure business continuity in case of a breach. |
| **Antivirus Software** | ✅ Yes | Antivirus software is installed and monitored regularly by the IT department. |
| **Legacy System Monitoring** | ❌ No | Legacy systems are monitored and maintained, but without a regular schedule or clear procedures, which increases breach risk. |
| **Encryption** | ❌ No | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
| **Password Management System** | ❌ No | There is no password management system in place; implementing one would improve IT and employee productivity. |
| **Physical Locks** | ✅ Yes | The store’s offices, storefront, and warehouse are protected with sufficient locks. |
| **CCTV Surveillance** | ✅ Yes | CCTV is installed and functioning at the physical location. |
| **Fire Detection/Prevention** | ✅ Yes | Fire alarms and sprinkler systems are functional at Botium Toys’ location. |

---

## ⚖️ Compliance Checklist

### **Payment Card Industry Data Security Standard (PCI DSS)**

| Best Practice | In Place | Explanation |
|--------------|:--------:|-------------|
| Only authorized users have access to customers’ credit card information. | ❌ No | Currently, all employees have access to the company’s internal data. |
| Credit card data is processed/stored in a secure environment. | ❌ No | Credit card info is not encrypted and all employees can access it. |
| Data encryption procedures are in place. | ❌ No | The company does not use encryption for customer financial data. |
| Secure password management policies adopted. | ❌ No | Password policies are minimal and there’s no password management system. |

### **General Data Protection Regulation (GDPR)**

| Best Practice | In Place | Explanation |
|--------------|:--------:|-------------|
| E.U. customers’ data is secured. | ❌ No | The company does not currently use encryption to protect customer data. |
| Data breach notification plan (72 hrs). | ✅ Yes | There is a plan to notify E.U. customers within 72 hours of a breach. |
| Data is properly classified/inventoried. | ❌ No | Assets have been listed but not classified. |
| Privacy policies/procedures enforced. | ✅ Yes | Policies are developed and enforced among IT staff and other employees. |

### **System and Organization Controls (SOC 1 & SOC 2)**

| Best Practice | In Place | Explanation |
|--------------|:--------:|-------------|
| User access policies are established. | ❌ No | Least Privilege and Separation of Duties are not in place. |
| PII/SPII is kept confidential. | ❌ No | Encryption is not used to protect sensitive information. |
| Data integrity is ensured. | ✅ Yes | Data integrity is in place (consistent, accurate, and validated). |
| Data availability is restricted to authorized users. | ❌ No | All employees currently have access to internal data. |

---

## 💡 Recommendations

To strengthen Botium Toys' security and compliance posture:

- Implement controls such as **Least Privilege**, **Separation of Duties**, **Encryption**, and a **Password Management System**.
- Introduce **Disaster Recovery Plans**, **IDS**, and **structured legacy system maintenance**.
- Enforce **secure password policies** and adopt encryption protocols for sensitive customer data.
- Classify assets and enforce access control based on user roles.
- Align practices with **PCI DSS**, **GDPR**, and **SOC 1/2** standards to mitigate risk and ensure compliance.

---

## 📁 Project Purpose

This checklist demonstrates my ability to assess an organization’s current state of controls and compliance, identify gaps, and make clear, actionable recommendations to reduce risk and improve security posture.

---
