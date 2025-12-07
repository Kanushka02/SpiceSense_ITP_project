# 🌶️ SpiceSense – Inventory Management System  
### **My Role: Supplier Management & Product Handling Module (MERN Stack)**

SpiceSense is a MERN-stack inventory management system developed as a group project for the IT Project module (Y2S2) at SLIIT.  
The system helps spice companies manage products, suppliers, stock levels, expiry dates, and real-time alerts.

This repo section highlights the features I developed.

---

## 🔧 My Contribution

### **1. Supplier Product Management (CRUD)**
- Implemented full Create, Read, Update, Delete operations for supplier products.
- Designed clean and responsive product forms (Add / Update).
- Added backend validation and secure API logic.
- Synced product changes instantly using MongoDB collections.

---

### **2. Real-Time Order Processing**
- Developed the supplier-side interface for handling incoming orders.
- Implemented status transitions:  
  `Pending → Accepted / Rejected → Preparing → Completed`
- Integrated REST API endpoints for real-time updates.
- Ensured consistent backend–frontend state sync.

---

### **3. Delivery Assignment Workflow**
- Built delivery assignment logic after an order is prepared.
- Added options for:
  - Assigning delivery personnel  
  - Marking as self-delivery  
- Synced delivery status updates:
  `Out for Delivery → Delivered`
- Triggered alerts/notifications on status changes.

---

### **4. Transaction History Module**
- Created a detailed activity log for suppliers.
- Logged:
  - Product updates
  - Order processing steps
  - Delivery status changes
- Added filters for:
  - Date range
  - Product type
  - Order status
- Designed a simple UI for browsing records.

---

### **5. Advanced Search & Filtering System**
- Implemented rapid search for products/orders using:
  - Name
  - Category
  - Product ID
- Added multi-level filtering:
  - Delivery status
  - Order status
  - Product availability
  - Date ranges
- Optimized MongoDB queries for fast results.

---

## 🛠️ Tech Stack (My Work)

**Frontend:** React.js  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Additional Tools:** REST APIs, Custom filtering algorithms

---

## 📌 Summary
I developed the **Supplier Management Module**, which includes product CRUD operations, order processing, delivery workflows, transaction logs, and advanced search/filter features.  
My work ensured smooth and efficient supplier operations within the entire inventory system.

