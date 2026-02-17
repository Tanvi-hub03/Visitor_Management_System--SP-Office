# 🏢 SP Office – Visitor Management System (VMS)

> 🔒 Live Client Project – Developed for SP Office
> 📍 Government Office Automation System
> 🖥️ Web-Based Secure Visitor Entry & Management Platform

---

## 📌 Project Overview

The **SP Office Visitor Management System (VMS)** is a live deployed web application developed for the Superintendent of Police Office to digitally manage visitor entries, approvals, and records.

The system replaces manual visitor registers with a secure, searchable, and report-friendly digital platform.

This solution improves:

* Security monitoring
* Visitor tracking
* Data accuracy
* Administrative efficiency
* Record maintenance & reporting

---

## 🎯 Project Objectives

* Digitize visitor entry process
* Maintain secure visitor records
* Enable officer-wise visit tracking
* Reduce manual paperwork
* Generate searchable and exportable reports
* Improve office security workflow

---

## 👥 User Roles

### 1️⃣ Admin

* Login authentication
* Manage users
* View all visitor records
* Generate reports
* Monitor system activity

### 2️⃣ Reception / Entry Operator

* Add new visitor entries
* Assign visiting officer
* Capture visitor details
* Update visit status

### 3️⃣ Officer (Optional Module)

* View assigned visitors
* Approve / reject visits
* Monitor daily appointments

---

## 🛠️ Technology Stack

| Layer     | Technology Used               |
| --------- | ----------------------------- |
| Frontend  | HTML, CSS, JavaScript         |
| Backend   | Python (Flask)                |
| Database  | MySQL                         |
| Hosting   | IIS / Local Server Deployment |
| Reporting | CSV Export                    |

---

## 🔐 Key Features

* Secure Login System
* Role-Based Dashboard
* Add / Edit / Delete Visitor Records
* Officer-wise Visitor Assignment
* Date-wise Filtering
* Search Functionality
* Visitor Status Tracking
* Data Export (CSV)
* Clean UI for Government Use
* Optimized for Desktop Usage

---

## 🗂️ System Modules

### 🔹 Authentication Module

* Admin Login
* Secure Session Handling

### 🔹 Visitor Entry Module

* Name
* Contact Details
* Address
* Purpose of Visit
* Visiting Officer
* Date & Time

### 🔹 Dashboard Module

* Total Visitors
* Daily Visitors
* Pending Visits
* Completed Visits

### 🔹 Reporting Module

* Filter by Date
* Officer-wise Report
* Export Records

---

## 💾 Database Structure (Overview)

Main Tables:

* `users`
* `visitors`
* `officers`
* `visit_status`

Relational database design ensures:

* Data consistency
* Secure storage
* Efficient querying

---

## 🚀 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/sp-office-vms.git
cd sp-office-vms
```

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Database

* Create MySQL database
* Import provided `.sql` file
* Update database credentials in `config.py`

### 4️⃣ Run Application

```bash
python app.py
```

Application runs on:

```
http://localhost:5000
```

---

## 🔒 Security Measures

* Session-based authentication
* Role-based access control
* Input validation
* Secure database connection
* Restricted admin access

---

## 📊 Benefits to SP Office

* Improved visitor tracking
* Reduced manual errors
* Faster record retrieval
* Digital audit trail
* Organized reporting system
* Professional digital workflow

---

## 📁 Project Status

✅ Live & Operational
✅ Client Deployed
✅ Actively Used in Office Environment

---

## 📜 License

This project is developed for client use (SP Office).
Unauthorized distribution or commercial reuse is not permitted without permission.

---
