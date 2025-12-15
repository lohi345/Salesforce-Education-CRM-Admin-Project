# 🎓 Salesforce Education CRM – Admin Project

## 📘 Overview
This project is a Salesforce Admin–focused **Education CRM** designed to manage
students, courses, and enrollments in a centralized system using standard
Salesforce configuration.

It demonstrates **real-world Salesforce Admin skills** such as data modeling,
validation rules, reporting, and dashboard creation.

## ❓ Business Problem
Educational institutions often manage student admissions, courses, and
enrollments using disconnected systems or spreadsheets, which leads to:
- Data duplication ❌
- Limited visibility 📉
- Manual reporting effort 🕒

## 💡 Solution
A centralized **Salesforce Education CRM** was designed and implemented to:
- Manage student information efficiently 👨‍🎓
- Maintain structured course data 📚
- Track student enrollments accurately 🔗
- Prevent duplicate enrollments 🚫
- Provide insights using reports and dashboards 📊

## 🧩 Data Model & Objects
The following custom objects were created:

### 👤 Student__c
- Stores student details such as department, admission status, year, email,
  and admission date

### 📘 Course__c
- Stores course information including course name, code, capacity, credits,
  and status

### 🔗 Enrollment__c
- Junction object used to manage the **many-to-many relationship** between
  Students and Courses

### 🔁 Relationships
- One Student ➝ Many Enrollments  
- One Course ➝ Many Enrollments  

## ⭐ Key Features
- Structured student lifecycle management 🧑‍🎓
- Course management with configurable attributes 🏫
- Enrollment tracking using a junction object 🔄
- Data integrity using validation rules ✔️
- Analytics using custom reports and dashboards 📈

## 🛡️ Business Logic
- **Validation Rule**
  - Prevents a student from enrolling in the same course more than once,
    ensuring clean and reliable data

## 📊 Reports & Dashboard
### Reports Created:
- Students by Department 🏢
- Course Enrollment Count 📘
- Student Enrollment Details 👥

### Dashboard:
- **Education CRM Dashboard**  
  - Visual overview of students and course enrollments 📊

## 🛠️ Tools & Platform
- Salesforce Trailhead Playground 🌐
- Salesforce Lightning Experience ⚡
- Salesforce Admin Configuration (No Apex code) 🧩

## 🎯 Project Level
Salesforce Admin – **Intermediate Level**





