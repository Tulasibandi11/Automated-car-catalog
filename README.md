# 🚗 Automated Car Catalog System for Enhanced Showroom Management

## 📌 Overview
The **Automated Car Catalog System** is a ServiceNow-based application designed to streamline showroom operations by automating the management of car catalogs, customer requests, approvals, and fulfillment tasks.  
This project leverages **Service Catalog** and **Workflow Designer** to enhance efficiency, reduce manual intervention, and improve customer satisfaction.

---

## 🛠 Skills & Tools Used
- ServiceNow (Service Catalog, Workflow Designer, Tables, Notifications)
- User, Role & Group Management
- Email Notifications
- Service Portal Integration

---

## 🎯 Problem Statement
Car showrooms and dealerships often struggle with:
- Manual catalog and request handling
- Delays in approvals and fulfillment
- Inefficient tracking of customer requests
- Reduced customer satisfaction  

This project automates the **entire request lifecycle** from ordering cars to approval, fulfillment, and notification.

---

## ✅ Features
1. **Service Catalog**
   - Catalog: `Mahendra`
   - Categories: `Sudden`, `XUV`, `Sports`
   - Catalog Items:
     - **Volkswagen Polo** – Compact Hatchback  
     - **Mahindra Thar** – Rugged Off-Road SUV  
     - **Mahindra XUV700** – Premium SUV  

2. **Security Setup**
   - User: Salesperson (`emp1` role)  
   - Group: `Showroom` (Manager: Abraham Lincoln)  

3. **Custom Table**
   - **Cars Fulfillment** (extended from Task Table)

4. **Workflow**
   - Multi-level approvals (Salesperson → Supervisor)  
   - Automatic Task Creation (Car Fulfillment)  
   - Notifications for approval/rejection with HTML templates  

5. **Service Portal**
   - Customers can search cars (e.g., `Thar`)  
   - Place orders directly via Service Portal  
   - Receive **request numbers, delivery dates, and email notifications**  

---

## 🔄 Workflow Steps
1. Customer requests a car from the Service Portal  
2. Workflow triggers approval (Salesperson → Supervisor)  
3. On approval:
   - Fulfillment tasks are created in the `Cars Fulfillment` table  
   - Notification email sent to customer & manager  
4. On rejection:
   - Rejection notification sent  

---

## 📧 Notifications
- **Booking Notification (Approved)** – HTML email with car details and status  
- **Car Reject Notification (Rejected)** – Simple rejection email  

---

## 📊 Results
- Cars visible and orderable in Service Portal  
- Requests automatically approved/rejected via workflow  
- Tasks auto-created and tracked in ServiceNow  
- Notifications sent dynamically based on status  

---

## 🏁 Conclusion
The **Automated Car Catalog System** improves showroom management by:
- Organizing cars in a structured catalog  
- Automating approvals & fulfillment  
- Enhancing transparency and customer satisfaction  

This project demonstrates ServiceNow’s ability to digitize traditional business processes for **car dealerships and showrooms**.

---

## 📂 Project Structure

Automated-Car-Catalog-System/
│── README.md
│── Documentation.pdf (Full Project Report)
│── Screenshots/ (UI & Workflow images)
│── ServiceNow_Config/ (Exported config files if applicable)


---

## 🚀 Future Enhancements
- Integration with **Inventory & Finance Systems**  
- Automated **CRM updates** for customer relationship management  
- Analytics dashboard for tracking sales & orders  

---

👨‍💻 **Author:** Bandi Tulasi Lakshmi 
📅 **Year:** 2025  
📍 **Platform:** ServiceNow
