# Project Details

Project Name: Salesforce Education CRM  
Project Type: Salesforce Admin (Intermediate)  
Platform: Salesforce Trailhead Playground – Lightning Experience  

---

## Objective
To design and configure a Salesforce-based Education CRM to manage student,
course, and enrollment data using Admin-level configuration.

---

## Custom Objects

### Student__c
Purpose: Stores student information.

Fields:
- Student ID (Auto Number)
- Student Name
- Department
- Admission Status
- Year
- Email
- Admission Date

---

### Course__c
Purpose: Stores course details.

Fields:
- Course Name
- Course Code
- Capacity
- Credits
- Course Status

---

### Enrollment__c
Purpose: Manages student-course enrollments (Junction Object).

Fields:
- Enrollment Number (Auto Number)
- Student (Lookup to Student__c)
- Course (Lookup to Course__c)

---

## Relationships
- Student__c → Enrollment__c (One-to-Many)
- Course__c → Enrollment__c (One-to-Many)

---

## Business Logic
Validation Rule:
- Name: Prevent_Duplicate_Enrollment
- Object: Enrollment__c
- Function: Prevents duplicate student-course enrollment records

---

## Reports
- Students by Department
- Course Enrollment Count
- Student Enrollment Details

---

## Dashboard
Name: Education CRM Dashboard  

Components:
- Students by Department (Donut Chart)
- Enrollments per Course (Bar Chart)
- Student Enrollment Details (Table)

---

## Outcome
The Education CRM provides a centralized system to manage students, courses,
and enrollments with data validation and reporting.
