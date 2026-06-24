# 🏥 Ivor Paine Memorial Hospital Management System

A comprehensive Hospital Management System developed as part of the Database Systems Laboratory course. The project aims to digitize and streamline hospital operations through an efficient database-driven platform that manages patients, doctors, nurses, wards, consultants, treatments, complaints, and administrative records.

---

## 📌 Overview

Hospitals generate and manage large amounts of data daily. Manual record management can lead to inefficiencies, data redundancy, and difficulties in tracking patient history.

The Ivor Paine Memorial Hospital Management System provides a centralized solution for managing hospital information through a structured relational database integrated with a web-based interface.

The system enables hospital administrators and staff to efficiently maintain records, monitor patient care, manage hospital resources, and generate meaningful reports.

---

## ✨ Features

### 👨‍⚕️ Patient Management
- Register new patients
- View patient profiles
- Maintain patient medical records
- Track treatments and consultations

### 🩺 Doctor Management
- Manage doctor information
- Assign doctors to patients
- Track specializations
- Maintain consultant records

### 👩‍⚕️ Nurse Management
- Store nurse details
- Assign nurses to wards
- Track nursing staff responsibilities

### 🏥 Ward Administration
- Manage hospital wards
- Track ward occupancy
- Allocate patients to wards
- Monitor ward capacity

### 📋 Treatment Records
- Store treatment history
- Monitor patient progress
- Record prescribed treatments

### ⚠️ Complaint Management
- Register complaints
- Track complaint status
- Maintain complaint resolution records

### 📊 Reporting & Analytics
- Generate operational reports
- Perform advanced database queries
- Analyze hospital statistics

---

## 🗄️ Database Design

The project implements a normalized relational database schema to ensure:

- Data Consistency
- Data Integrity
- Reduced Redundancy
- Efficient Query Processing
- Better Scalability

### Core Entities

- Patients
- Doctors
- Consultants
- Nurses
- Wards
- Treatments
- Complaints
- Admissions
- Hospital Staff

---

## 📚 Database Concepts Implemented

This project demonstrates practical implementation of major Database Management System concepts:

### ✔ Entity Relationship Modeling
- ER Diagram Design
- Relationship Mapping
- Cardinality Analysis

### ✔ Relational Database Design
- Table Creation
- Schema Design
- Relationship Enforcement

### ✔ Normalization
- 1NF
- 2NF
- 3NF

### ✔ Constraints
- Primary Keys
- Foreign Keys
- NOT NULL Constraints
- Referential Integrity

### ✔ SQL Queries
- Joins
- Nested Queries
- Aggregate Functions
- Group By Operations
- Ordering & Filtering
- Data Retrieval Queries

### ✔ Advanced Database Operations
- Reporting Queries
- Multi-table Operations
- Data Analysis Queries

---

## 💻 Tech Stack

### Frontend
- HTML5
- CSS3

### Backend
- PHP

### Database
- Microsoft SQL Server

### Development Tools
- SQL Server Management Studio (SSMS)
- Visual Studio Code

---

## 📂 Project Structure

```text
Hospital-Management-System/
│
├── Database/
│   ├── Schema.sql
│   ├── Tables.sql
│   ├── SampleData.sql
│   └── Queries.sql
│
├── Frontend/
│   ├── HTML
│   ├── CSS
│
├── Backend/
│   ├── PHP Files
│   ├── Database Connection
│   └── CRUD Operations
│
├── Documentation/
│   ├── ER Diagram
│   ├── Relational Schema
│   └── Project Report
│
└── README.md
```

---

## 🚀 Installation Guide

### Prerequisites

- PHP 8+
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Web Server (XAMPP/WAMP)

### Setup Steps

#### 1. Clone Repository

```bash
git clone https://github.com/yourusername/hospital-management-system.git
```

#### 2. Create Database

```sql
CREATE DATABASE HospitalManagementSystem;
```

#### 3. Import SQL Scripts

Execute:

- Schema.sql
- Tables.sql
- SampleData.sql

#### 4. Configure Database Connection

Update connection settings:

```php
$serverName = "localhost";
$database = "HospitalManagementSystem";
$username = "your_username";
$password = "your_password";
```

#### 5. Run Project

Start Apache and SQL Server, then open:

```text
http://localhost/HospitalManagementSystem
```

---

## 📊 Sample Functionalities

### Patient Registration
Allows administrators to register and maintain patient records.

### Doctor Assignment
Assign doctors based on specialization and availability.

### Ward Allocation
Manage patient admissions and ward occupancy.

### Complaint Tracking
Record and monitor complaints raised by patients.

### Treatment Monitoring
Maintain treatment history and progress tracking.

---

## 🔍 Learning Outcomes

Through this project we gained hands-on experience in:

- Database Design
- SQL Development
- ER Modeling
- Relational Schema Design
- Normalization
- Backend Development
- Database Connectivity
- CRUD Operations
- Real-world System Design

---

## 🎓 Academic Context

This project was developed as part of the:

**Database Systems Laboratory (DB Lab)**

FAST National University of Computer and Emerging Sciences (FAST-NUCES)

The project focuses on applying database theory to solve real-world healthcare management problems through efficient system design and implementation.

---

## 👥 Team Members

- Muhammad Sarim
- Abdullah Junaid
- Kasim Zeeshan
---

## 📄 License

This project is developed for academic and educational purposes.

---

## ⭐ Future Improvements

- Authentication & Authorization
- Role-Based Access Control
- Appointment Scheduling
- Billing & Payment Module
- Prescription Management
- Real-Time Dashboard
- Data Visualization & Analytics
- Cloud Database Deployment

## View
<img width="1362" height="660" alt="dashboard" src="https://github.com/user-attachments/assets/492e45b8-8363-4728-90ce-820126866873" />
<img width="1365" height="636" alt="sampleReport" src="https://github.com/user-attachments/assets/680b43d8-79ec-49d6-98d8-4e6b3dffea73" />
<img width="1361" height="635" alt="reportTypes" src="https://github.com/user-attachments/assets/b145c94c-d03a-4db4-8902-f8987d1f7c99" />
<img width="1365" height="646" alt="report2" src="https://github.com/user-attachments/assets/25835bbf-3db5-4928-8fba-4165f2aae11f" />
<img width="1365" height="636" alt="sampleReport" src="https://github.com/user-attachments/assets/ed801b49-07d3-4a55-a9ee-123556919715" />
<img width="1361" height="645" alt="form2" src="https://github.com/user-attachments/assets/e38309a7-8277-4335-b88e-7f8358f62dbb" />


---

### 📬 Contact

For suggestions, improvements, or collaboration opportunities, feel free to connect through LinkedIn or GitHub.

If you found this project helpful, don't forget to ⭐ the repository.
