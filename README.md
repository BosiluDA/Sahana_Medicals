# PPA – Sahana Medicals

A full pharmacy management system for handling medicine inventory, orders, prescriptions, billing and reporting.

---

## Why

### Purpose
- **Customer**: Browse medicines, order online, submit prescriptions, manage profile and orders  
- **Admin**: Inventory, suppliers, purchase orders, order handling, prescription approval, payments, staff, and reports  
- **Business**: Stock monitoring, revenue tracking, and exportable reports (PDF/Excel)

### Goals
- Simplify pharmacy operations from ordering to stock control  
- Support prescription-based orders with review and approval  
- Provide clear reports for management decisions  

---

## Tech

### Backend
- **PHP 7.4+** session-based auth, server logic
- **MySQL / MariaDB** – database storage
- **PDO** – database access
- **bcrypt** – password hashing

### Frontend
- **HTML5, CSS3**
- **Bootstrap 5.3**
- **Font Awesome 6**
- **Vanilla JavaScript**

### Export & Reporting
- **html2pdf.js** – PDF generation
- **SheetJS (xlsx)** – Excel export

### Server
- **Apache** 
- **PHP extensions**: PDO, PDO_MySQL, JSON, mbstring, fileinfo

---

## How

### Prerequisites
- PHP 7.4+
- MySQL 5.7+ / MariaDB 10.3+
- Apache (or Nginx) with PHP enabled
- `uploads/` and `uploads/prescriptions/` writable

   
