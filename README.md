# 🏥 Hospital Management System – Java + MySQL

A **console-based Hospital Management System** built using **Java** and **MySQL** with **JDBC** for seamless database operations.  
The system allows you to manage **patients, doctors, and appointments** with an intuitive, menu-driven interface.

---

## 📋 Features

### **1. Patient Management**
- Add new patient records to the database.
- View all registered patients in a formatted table.
- Check if a patient exists by their **Patient ID** (for appointment validation).

### **2. Doctor Management**
- View all available doctors and their specializations.
- Check if a doctor exists by their **Doctor ID** (for appointment validation).

### **3. Appointment Booking**
- Book an appointment by selecting:
  - Patient ID
  - Doctor ID
  - Appointment date
- Validates:
  - Both doctor and patient exist in the system.
  - The doctor is available on the selected date.
- Saves confirmed appointments to the database.

---

## 🛠 Technologies Used

- **Java (JDK 8 or above)** – Core programming language
- **MySQL** – Relational database
- **JDBC (Java Database Connectivity)** – For database interaction
- **IntelliJ IDEA** – IDE for development
- **MySQL Workbench** – For database design and testing
- **PreparedStatement** – Secure SQL execution (prevents SQL injection)
- **Scanner** – For console-based user input

---
