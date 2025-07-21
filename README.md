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

| Object                | Key Fields                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| HandsMen Customer     | Name, Email, Phone, Loyalty_Status__c, Preferred_Style__c                  |
| HandsMen Order        | Order_Date__c, Product__c, Quantity__c, Total_Amount__c, Order_Status__c    |
| HandsMen Product      | Product_Name__c, Fabric_Type__c, Price__c, Size__c, Availability_Status__c  |
| Inventory             | Product__c, Stock_Quantity__c, Stock_Status__c, Warehouse_Location__c       |
| Marketing_Campaign    | Campaign_Name__c, Start_Date__c, End_Date__c, Target_Audience__c, Campaign_Type__c |

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

| **Field**          | **Details**                                           |
| ------------------ | ----------------------------------------------------- |
| **Name**           | Vedhanath Reddy M                                     |
| **Email**          | [224g1a32b0@srit.ac.in](mailto:224g1a32b0@srit.ac.in) |
| **Role**           | Salesforce Developer                                  |
| **Project Status** | ✅ Completed                                           |




