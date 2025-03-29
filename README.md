# Student Management System

## Overview

This project is a **Student Management System** built using MySQL. It includes database tables for managing student records, courses, enrollment, attendance, and marks.

## Features

- Store student details (name, age, class, contact).
- Manage courses and instructors.
- Track student enrollments in courses.
- Record attendance status (Present/Absent).
- Store student marks and grades.

## Database Schema

The database consists of the following tables:

- **Students**: Stores student details.
- **Courses**: Contains course details and instructor names.
- **Enrollment**: Tracks which students are enrolled in which courses.
- **Attendance**: Records student attendance for courses.
- **Marks**: Stores student grades and marks.

## How to Use

1. Import the `student_management.sql` file into MySQL.
2. Use SQL queries to insert, update, or fetch data.
3. Modify and expand as needed for your projects.

## Sample Queries

To fetch all students:

```sql
SELECT * FROM Students;
```

To enroll a student in a course:

```sql
INSERT INTO Enrollment (student_id, course_id, enrollment_date)
VALUES (1, 2, '2025-03-29');
```

## License

This project is open-source. 

## Author

[Awais Manzoor](https://github.com/your-github-profile)

