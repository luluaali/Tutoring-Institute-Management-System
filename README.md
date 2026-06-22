# Tutoring Institute Management System (SQLite)

This project develops a Tutoring Institute Management System to organize student enrollments, batches, attendance, fees, tests, and results in a structured relational database. The main purpose is to centralize academic and administrative data so that the institute can track which students attend which batches, monitor fee payments, and analyze performance through test results. 

## Features

- Store details of students, teachers, subjects, batches, and classrooms
- Enroll students into batches and track which teacher teaches which batch
- Record attendance for each class session
- Record fee payments for students and batches
- Store tests and results for students in different subjects
- Run SQL queries with joins, aggregates, and subqueries to answer management questions
- Use transactions to load data consistently into multiple related tables 

## Technologies Used

- **Database:** SQLite  
- **Tools:** DB Browser for SQLite (implementation), Oracle SQL Developer Data Modeler (ER/relational modeling)  
- **Language:** SQL (DDL, DML, basic transaction control)

## Repository Contents

- `tutoring_institute.sql` – Main SQL script to create tables, constraints, and insert sample data
- `tutoring_institute.db` – SQLite database file with the implemented schema and data
- `diagrams/er-diagram.png` – ER / relational model of the tutoring institute database 
- `report.pdf` – Academic report describing design, normalization, queries, transactions, and recovery concepts 
- `screenshots/` – Screenshots of schema, sample queries, and outputs (optional)

> Note: File names can be adjusted to match your actual exports (e.g., `TutoringInstitute_SQL_Code.sql`, `TutoringInstitute.db`). 
## Database Design Overview

The database models a small tutoring institute with entities such as:

- Students, Teachers, Subjects
- Batches (groups of students taking a subject with a teacher)
- Enrollment of students into batches
- Attendance records
- FeePayment records
- Tests and Results 

The schema was designed using ER modeling and then converted into a normalized relational model with appropriate primary keys, foreign keys, and constraints to reduce redundancy and preserve data integrity. 

## How to Use

### Option 1: Using the `.db` file (recommended)

1. Install **DB Browser for SQLite**. 
2. Open the application and choose **File → Open Database**.
3. Select `tutoring_institute.db`.
4. Use the **Browse Data** tab to view tables, and the **Execute SQL** tab to run queries.

### Option 2: 
