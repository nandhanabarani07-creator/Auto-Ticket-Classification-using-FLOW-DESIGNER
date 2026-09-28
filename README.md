# Auto Ticket Classification using Flow Designer

## 📌 Project Overview

The **Auto Ticket Classification using Flow Designer** project is designed for a School IT Helpdesk.

It automatically classifies IT support tickets based on keywords in the Short Description. The system assigns the appropriate **Category** and **Subcategory** without manual intervention.

The project is developed using **ServiceNow Flow Designer** with a no-code approach.

---

## 🎯 Objectives

- Automatically classify IT incidents when they are created.
- Reduce manual effort for IT support staff.
- Improve ticket routing efficiency.
- Automatically assign Category and Subcategory.
- Send email notification to the caller.
- Provide an easy-to-maintain and scalable solution.

---

## 🏫 Business Use Case

The School IT Helpdesk receives different types of support requests such as:

- Wi-Fi issues
- Projector problems
- Password/Login issues
- Slow computer problems

Normally, IT staff manually review each ticket and select the correct Category and Subcategory.

This project automates this process using **ServiceNow Flow Designer**.

---

## 🛠️ Technologies Used

- ServiceNow
- Flow Designer
- Update Sets
- Custom Tables
- Choice Fields
- Reference Fields
- Email Notifications
- No-Code Automation

---

## ⚙️ Ticket Classification

| Keyword / Issue | Category | Subcategory |
|---|---|---|
| WiFi / Network | Network | Wi-Fi |
| Projector | Hardware | Projector |
| Password / Login | Access | Forgot Password |
| Slow / Hanging | Performance | Slow Computer |

---

## 🔄 Workflow

1. User creates an IT support ticket.
2. The ticket contains a Short Description.
3. Flow Designer is triggered when the record is created.
4. The system checks the Short Description.
5. The appropriate Category is identified.
6. The corresponding Subcategory is assigned.
7. An email notification is sent to the caller.
8. The ticket is stored in the system.

---

## 🔧 Main Modules

### 1. Requirement Analysis
Defines the business requirements and helpdesk use case.

### 2. Update Set Configuration
A project update set is created to manage and transport configuration changes.

### 3. Custom Table
A custom Incident Workflow table is created to store ticket records.

### 4. Field Configuration
Fields such as Caller, Category, Subcategory, Short Description, Description, State, Assigned Group and Assigned To are configured.

### 5. Category and Subcategory Dependency
Subcategory choices depend on the selected Category.

### 6. Flow Designer Automation
Flow Designer automatically classifies tickets based on predefined keywords.

### 7. Email Notification
An automated confirmation email is sent to the caller after ticket creation.

### 8. Testing and Validation
Different ticket scenarios are tested to verify automatic classification and email notification.

---

## 🧪 Sample Test Cases

### Test Case 1 – Wi-Fi Issue

**Short Description:**
`WiFi not working in library`

**Expected Result:**
- Category → Network
- Subcategory → Wi-Fi
- Email notification → Sent

### Test Case 2 – Projector Issue

**Short Description:**
`Projector not turning on`

**Expected Result:**
- Category → Hardware
- Subcategory → Projector
- Email notification → Sent

---

## 📧 Email Notification

After ticket creation and classification, an automated email notification is sent to the caller.

**Subject:**
`Your Request for the issue has been submitted.`

---

## 📦 Deployment

The completed project configuration can be managed using a ServiceNow Update Set.

The Update Set can be changed from **In Progress** to **Complete** and exported as an XML file for sharing or deployment.

---

## 🚀 Future Enhancements

- Automatic assignment to support teams
- SLA tracking
- Advanced ticket classification
- Predictive intelligence
- More IT issue categories
- Improved reporting and analytics

---

## 👥 Project

**Project Title:** Auto Ticket Classification using Flow Designer

**Platform:** ServiceNow

**Approach:** No-Code Automation

**Domain:** School IT Helpdesk

---

## 📄 Conclusion

The project automates IT ticket classification using ServiceNow Flow Designer. It reduces manual classification work by automatically assigning Category and Subcategory based on ticket descriptions.

The solution provides a structured, maintainable and scalable approach for managing school IT helpdesk requests.
