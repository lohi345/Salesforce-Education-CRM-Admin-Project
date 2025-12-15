# Salesforce Education CRM – Admin Project

## Project Overview
This project is a Salesforce Admin–focused Education CRM designed to manage
students, courses, and enrollments for an educational institution using
standard Salesforce configuration.

## Business Problem
Educational institutions often struggle to manage student admissions,
course offerings, and enrollments across disconnected systems, leading to
data inconsistency and limited reporting.

## Solution
I designed and implemented a centralized Education CRM on Salesforce that
allows administrators to manage students, courses, and enrollments efficiently
with built-in validation and reporting.

## Objects & Data Model
- **Student__c** – Stores student information
- **Course__c** – Stores course details
- **Enrollment__c** – Junction object connecting Students and Courses

Relationship:
- One Student → Many Enrollments
- One Course → Many Enrollments

## Key Features
- Student lifecycle management (admission details, department, year)
- Course management with capacity and status
- Enrollment tracking using a junction object
- Validation rule to prevent duplicate student-course enrollments
- Reports and dashboards for insights

## Business Logic
- Validation Rule: Prevents a student from enrolling in the same course more than once

## Reports & Dashboard
- Students by Department
- Course Enrollment Count
- Student Enrollment Details
- Education CRM Dashboard for visual insights

## Tools & Platform
- Salesforce Trailhead Playground
- Salesforce Admin configuration (No Apex code)

## Author
Latchipatula Lohitha
