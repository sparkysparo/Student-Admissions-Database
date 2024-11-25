# Student-Admissions-Database
## Overview
This repository contains a database project simulating a **Student Admissions System**. It demonstrates fundamental database design principles, including normalization, foreign key relationships, and handling real-world data challenges like missing values.

## Features
- **Database Schema**:
  - Three interconnected tables:
    - `students`: Contains student details.
    - `courses`: Stores course information.
    - `enrollments`: Links students to courses and tracks their GPA and admission status.
  - Relationships:
    - `students` ↔ `enrollments` (via `student_id`).
    - `courses` ↔ `enrollments` (via `course_id`).

- **Data**:
  - Generated using Python libraries (`pandas`, `numpy`, `random`).
  - Includes:
    - 2000 student records.
    - 20 course records.
    - Randomized enrollments.
  - Simulated missing values in GPA for realism.

- **Design Principles**:
  - Normalized structure to minimize redundancy and ensure data integrity.
  - Use of foreign keys for referential integrity.
  - Ethical considerations: anonymized and non-sensitive data.

## Files Included
- **Database File**: `Student_Admissions.db`
- **Documentation**: `Student Admissions Database Report.docx`
- **CSV Exports**:
  - `students.csv`
  - `courses.csv`
  - `enrollments.csv`

## Schema Diagram
The schema diagram below represents the relationships between the tables.

![Schema Diagram](schema_diagram.png)

## Installation and Usage
### Step 1: Clone the Repository
```bash
git clone https://github.com/sparkysparo/student-admissions-database.git
cd student-admissions-database
