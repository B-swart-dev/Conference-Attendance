# 📋 Attendance Register System

## Overview
A desktop application built with Java and Java Swing to manage attendee registrations for a business conference.

The system allows users to capture attendee details, store them in a MySQL database, and display records in a table interface.

---
## 🖼️ Layout
<img width="565" height="434" alt="image" src="https://github.com/user-attachments/assets/46771982-b84c-476e-9c95-09140d9318e3" />

---

## 🚀 Features
- Capture attendee information:
  - Name
  - Surname
  - Email
  - Phone number
  - Company
- Input validation:
  - Required field checks
  - Character length limits
  - Numeric-only phone input
- Insert records into a MySQL database
- View stored records in a table (JTable)
- Simple and user-friendly GUI

---

## 🧠 Functionality
- Uses JDBC to connect to a MySQL database
- Inserts data using Prepared Statements
- Retrieves and displays data using SQL queries
- Dynamically updates table data in the UI

---

## 🛠️ Tech Stack
- Java  
- Java Swing  
- MySQL  
- JDBC  
- JPA (Entity mapping)  

---

## ▶️ How to Run
1. Set up a MySQL database:
   - Database name: `fa3_bcar`
   - Table: `attendance_register`

2. Update database credentials in code:
```java
String username = "root";
String password = "your_password";
```

3. Run:
```bash
FormativeAssessment3GUI.java
```

---

## 📂 Project Structure
```
src/formativeassessment/pkg3/gui/
│── FormativeAssessment3GUI.java   # Entry point
│── frmMain.java                   # UI + logic
│── AttendanceRegister.java        # Entity class
```

---

## 📌 Notes
This project demonstrates:
- GUI development using Java Swing  
- Database integration using JDBC  
- Data validation techniques  
- Basic ORM concepts using JPA annotations  

---
