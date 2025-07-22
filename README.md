# HandsMen Threads: Salesforce CRM for Premium Men's Fashion

## 🔍 Project Overview

**HandsMen Threads** is a tailor-made Salesforce CRM solution built for a luxury men's fashion brand. It automates key business workflows such as order processing, customer engagement, inventory management, and campaign execution using Salesforce's declarative and programmatic tools.

---

## 🎯 Objectives

- Automate tasks like order confirmations and loyalty updates
- Enhance efficiency across Sales, Inventory, and Marketing
- Minimize data entry errors using Flows and Validation Rules
- Provide scalable and real-time business insights

---

## 🧩 Salesforce Implementation

### ✅ Custom Objects

- `HandsMen_Customer__c`: Customer profiles and loyalty tracking
- `HandsMen_Product__c`: Product catalog with price, size, and availability
- `HandsMen_Order__c`: Links customers with products and status
- `Inventory`: Tracks stock levels, warehouse location, and alerts
- `Marketing_Campaign__c`: Campaign type, schedule, and target group

### 🗂️ Tabs & App

- **Tab**: HandsMen Customer (quick access to customer records)
- **App**: HandsMen Threads (centralized Lightning App for all objects)

---

## 🧾 Fields Summary

| **Object**             | **Key Fields**                                                                                                                          |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **HandsMen Customer**  | Name (Record Name), Email (Email), Phone (Phone), Loyalty\_Status\_\_c (Picklist: Bronze, Gold, Silver), Total\_Purchases\_\_c (Number) |
| **HandsMen Product**   | Name (Record Name), SKU (Text), Price (Currency), Stock\_Quantity\_\_c (Number)                                                         |
| **HandsMen Order**     | Order\_Number (Record Name), Status (Picklist: Pending, Confirmed, Rejection), Quantity\_\_c (Number), Total\_Amount\_\_c (Number)      |
| **Inventory**          | Auto Number (Record Name), Warehouse (Text), Stock\_Quantity\_\_c (Number)                                                              |
| **Marketing Campaign** | Campaign\_Name (Record Name), Start\_Date (Date), End\_Date (Date)                                                                      |

---

## 🛡️ Security & Access

- **Profiles**: Sales (limited object access)
- **Roles**: Sales, Inventory Manager, Marketing Manager
- **Permission Sets**: `Permission_Platform_1` – extends field/object access
- **Sample Users**: Niklaus, Kol, Loretta Daniel

---

## 📧 Email Templates & Alerts

- **Order Confirmation**: Sent after successful order creation
- **Loyalty Notification**: Alerts customers about loyalty tier changes
- **Low Stock Alert**: Notifies managers about critical inventory
- **Automation Alerts**: Triggered via Flows

---

## 🔄 Flows

- `Stock Alert Flow`: Detects low stock and sends alerts
- `Loyalty Status Flow`: Updates customer loyalty levels
- `Order Confirmation Flow`: Sends email immediately after order placement

---

## ⚙️ Apex Automation

- `OrderTriggerHandler`: Apex class handling order logic
- `OrderTrigger`: Apex trigger linked to HandsMen_Order__c
- `InventoryBatchJob`: Batch job for inventory scanning and alerting
- `Scheduled Job`: Runs InventoryBatchJob periodically

---

## 🚀 Deployment & Versioning

- Managed via Salesforce CLI + SFDX
---

## ✅ Conclusion

HandsMen Threads CRM provides a powerful, automated platform that elevates operational excellence for luxury fashion. Built with scalability, automation, and user experience at its core, it sets a benchmark for digital transformation in the retail space.

---
👨‍💻 Developer & Contact
| **Field**          | **Details**                                           |
| ------------------ | ----------------------------------------------------- |
| **Name**           | Vedhanath Reddy M                                     |
| **Email**          | [224g1a32b0@srit.ac.in](mailto:224g1a32b0@srit.ac.in) |
| **Role**           | Salesforce Developer                                  |
| **Project Status** | ✅ Completed                                           |




