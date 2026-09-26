# 🎓 Training Academy Database

This project is a small SQL database for managing a Training Academy.

## 📌 Project Description

The database manages:
- Students
- Courses
- Student enrollments
- Course sessions
- Student attendance

## 🗂️ Database Tables

### STUDENT
Stores student information:
- `id`
- `name`
- `email`

### COURSE
Stores course information:
- `id`
- `title`
- `fee`

### ENROLLMENT
Connects students with the courses they are enrolled in:
- `id`
- `student_id`
- `course_id`
- `enrollment_date`

### SESSION
Stores the sessions of each course:
- `id`
- `course_id`
- `session_date`

### ATTENDANCE
Records student attendance for each session:
- `id`
- `session_id`
- `student_id`
- `status`

## 🔗 Relationships

- A student can enroll in multiple courses.
- A course can have multiple students.
- `ENROLLMENT` connects `STUDENT` and `COURSE`.
- A course can have multiple sessions.
- `ATTENDANCE` connects students with sessions.

## 🧪 SQL Queries

The project includes queries to:

1. List all students.
2. List courses with a fee greater than 100.
3. Show each student's enrolled courses.
4. Show all sessions for the SQL course.
5. Show each student's attendance status.
6. Count the number of `Present` records for each student.
7. Calculate attendance percentage.

## 🛠️ Technologies

- MySQL
- SQL
- MySQL Workbench

## 📚 Workshop

This project was completed as the **Final Student Task** for the SQL Workshop.

---

**Created by:** Salwa Alhajali  
**Field:** Computer Science
