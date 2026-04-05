# 💡 Doing Good Rewards (DGR) – System Analysis & Design

A complete business and system design for a **transaction-based donation platform** integrating payments, discounts, and charitable contributions into a single digital ecosystem.

---

## 📌 Overview
The Doing Good Rewards (DGR) platform enables users to contribute to charities through everyday purchases by automatically converting part of their spending into donations.

This project focuses on **end-to-end system analysis and design**, including:
- Business requirements
- Process modelling
- Data architecture
- System workflows
- UX-level thinking

---

## ❗ Business Problem
Traditional donation systems face several key limitations:
- Lack of transparency in how funds are used
- Low user engagement and incentives
- Disconnection from everyday financial activities

DGR addresses these challenges by embedding donations into **transaction flows**, allowing users to:
- Earn discounts
- Donate seamlessly
- Track their social impact in real time

---

## 🎯 Objectives
- Design a scalable system for transaction-based donations  
- Integrate payment processing with Open Banking systems  
- Automate discount and donation calculations  
- Provide transparency across customers, merchants, and charities  
- Ensure data consistency and system integrity  

---

## 🧠 Key Features
- Secure payment processing and validation  
- Invoice upload and verification (merchant-side)  
- Automated discount and donation calculation  
- Open Banking integration for transaction matching  
- Donation tracking and history  
- Admin dashboard for system monitoring and reporting  

---

## 👥 Key Actors
- Customer (Registered / Unregistered)  
- Participating Merchant  
- System Administrator  
- Charity Organisation  
- Open Banking Provider  
- Payment Gateway  
- Email Notification Service  

---

## 🏗️ System Architecture
The DGR platform acts as a central system connecting multiple external services:

- **Frontend**: Customer, Merchant, Admin interfaces  
- **Backend**: DGR Platform (core business logic)  
- **External Systems**:
  - Open Banking APIs  
  - Payment Gateway  
  - Email Delivery Services  

---

## 🔄 End-to-End Process Flow
1. Customer makes a purchase (online or in-store)  
2. Payment is processed via Payment Gateway  
3. Merchant uploads invoice  
4. Open Banking verifies transaction data  
5. System performs payment matching  
6. Discount is calculated  
7. Donation amount is derived  
8. Refund/benefit is issued to customer  
9. Donation is transferred to charity  
10. Notifications are sent to all stakeholders  

---

## 📊 System Models & Diagrams

### Context Diagram
![Context](assets/context-diagram.jpg)

### Use Case Diagram
![Use Case](assets/use-case-diagram.jpg)

### Entity Relationship Diagram (ERD)
![ERD](assets/erd.jpg)

### Payment Processing (DFD)
![Payment](assets/payment-dfd.jpg)

### Invoice Management (DFD)
![Invoice](assets/invoice-dfd.jpg)

### Discount & Donation Flow (DFD)
![Donation](assets/donation-dfd.jpg)

---

## 🗄️ Database Design
Designed a **relational database schema (3NF)** to ensure:
- Data consistency  
- Reduced redundancy  
- Strong relational integrity  

### Core Entities:
- Customer  
- Merchant  
- Invoice  
- Discount  
- Donation  
- Charity  
- Payment Methods  

---

## 🔐 Security & Compliance
- Secure transaction handling aligned with **PCI DSS principles**  
- Open Banking integration for validated financial data  
- Role-based access control (Admin / Merchant / Customer)  
- Secure data storage and communication  

---

## 📱 UI / UX Considerations
Designed interface concepts for:

### Customer Application:
- Transaction tracking  
- Donation history  
- Charity selection

![Customer1](assets/customer/customer1.png)

<p align="center">
  <img src="assets/customer/customer2.png" width="30%" />
  <img src="assets/customer/customer3.png" width="30%" />
  <img src="assets/customer/customer4.png" width="30%" />
</p>

<p align="center">
  <img src="assets/customer/customer5.png" width="30%" />
  <img src="assets/customer/customer6.png" width="30%" />
  <img src="assets/customer/customer7.png" width="30%" />
</p>

### Merchant Platform:
- Invoice upload  
- Payment tracking

![Customer1](assets/merchant/merchant1.png)

<p align="center">
  <img src="assets/merchant/merchant2.png" width="30%" />
  <img src="assets/merchant/merchant3.png" width="30%" />
</p>

<p align="center">
  <img src="assets/merchant/merchant4.png" width="30%" />
  <img src="assets/merchant/merchant5.png" width="30%" />
</p>

### Admin Dashboard:
- User management  
- System monitoring  
- Reporting  

<p align="center">
  <img src="assets/admin/admin1.png" width="30%" />
  <img src="assets/admin/admin2.png" width="30%" />
  <img src="assets/admin/admin3.png" width="30%" />
</p>

<p align="center">
  <img src="assets/admin/admin4.png" width="30%" />
  <img src="assets/admin/admin5.png" width="30%" />
  <img src="assets/admin/admin6.png" width="30%" />
</p>

---

## 📈 Business Impact
- Improves user engagement through reward-based donations  
- Provides transparency in donation tracking  
- Enables merchants to participate in social impact initiatives  
- Supports a scalable, multi-stakeholder ecosystem  

---

## 🛠️ Tools & Techniques
- System Analysis & Design  
- Use Case Modelling  
- Data Flow Diagrams (DFD)  
- Entity Relationship Diagram (ERD)  
- Database Normalisation (3NF)  
- Agile Methodology (Scrum)  

---

## 📂 Repository Structure

'''
DGR-System-Analysis-and-Design/
│
├── README.md
│
├── diagrams/
│   ├── context-diagram.png
│   ├── use-case-diagram.png
│   ├── erd.png
│   ├── payment-dfd.png
│   ├── invoice-dfd.png
│   ├── donation-dfd.png
│
├── documents/
│   ├── MIS605_A1.pdf
│   ├── MIS605_A2.pdf
│   ├── MIS605_A3.pdf
│
├── prototype/
│   ├── customer-ui.png
│   ├── merchant-ui.png
│   ├── admin-ui.png
'''

---

## 🚀 How to Explore This Project

1. Start with the **Overview and Business Problem** to understand the purpose of the system  
2. Review the **System Architecture and End-to-End Flow**  
3. Explore the **Diagrams**:
   - Context Diagram → system ecosystem
   - Use Case Diagram → user interactions
   - DFDs → process flows
   - ERD → data structure  
4. Review the **Database Design (3NF)**  
5. Check the **UI/UX concepts** in the prototype folder

---

## 💼 Key Skills Demonstrated

- Business Analysis & Requirements Engineering  
- Process Modelling (Use Case, DFD, BPMN thinking)  
- Data Modelling (ERD, 3NF Normalisation)  
- System Thinking & Architecture Design  
- Stakeholder-Oriented Solution Design  
- Financial System Integration (Open Banking concepts)

---

## 📈 Key Learnings

- Designing end-to-end systems requires aligning business logic with technical feasibility  
- Data modelling is critical for ensuring scalability and system integrity  
- Financial systems require strict validation, security, and process accuracy  
- Clear process flows improve both user experience and operational efficiency

---

## 🚀 Author
**Wasupon (Petch) Arpornpattana**  
Business Analyst | Systems & Data Enthusiast  
