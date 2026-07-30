# 🎓 University Course Management System (SQL Final Project)

## 📌 Project Overview
The **University Course Management System** is a comprehensive database project designed to demonstrate practical SQL skills. It covers database creation, schema design, table relationships with Primary and Foreign keys, sample data insertion, and executing complex SQL queries ranging from basic CRUD operations to advanced window functions.

---

## 🛠️ Database Schema & Entities

The system consists of **5 main tables**:

1. **`Departments`**: Stores details of academic departments.
2. **`Students`**: Stores student personal and enrollment information.
3. **`Courses`**: Stores available courses linked to their respective departments.
4. **`Instructors`**: Stores details about course instructors, including their department and salary.
5. **`Enrollments`**: Manages the mapping between students and the courses they are enrolled in.

---

## ⚡ Tech Stack & Tools
* **Database Management System:** MySQL (MySQL Workbench 8.0+)
* **SQL Concepts Used:** 
  * DDL & DML Operations (CRUD)
  * Joins (`INNER JOIN`, `LEFT JOIN`)
  * Aggregations & Grouping (`GROUP BY`, `HAVING`)
  * Subqueries
  * Built-in Functions (`CONCAT`, `YEAR`, `TIMESTAMPDIFF`)
  * Advanced SQL (`CASE` Expressions, Window Functions `OVER()`)

---

## 🚀 How to Run the Project

1. Open **MySQL Workbench** or any SQL Client.
2. Open the `script.sql` file in your editor.
3. Select all queries and execute them sequentially (or run as a single script).
4. Verify that the database `UniversityCourseManagement` and all 5 tables are created successfully.

---

## ❓ Queries & Solutions Included

The project addresses 16 specific queries:
1. **CRUD Operations:** Performing `INSERT`, `SELECT`, `UPDATE`, and `DELETE` on tables.
2. **Date Filtering:** Retrieving students enrolled after 2022.
3. **Department Filtering:** Fetching Mathematics courses with a limit of 5.
4. **Grouping & Having:** Filtering courses with more than 5 enrolled students.
5. **Multi-Join (AND):** Finding students enrolled in both *Introduction to SQL* and *Data Structures*.
6. **Multi-Join (OR):** Finding students enrolled in either *Introduction to SQL* or *Data Structures*.
7. **Aggregations:** Calculating average course credits.
8. **Max Calculation:** Finding the maximum salary in the Computer Science department.
9. **Department Counts:** Counting enrolled students per department.
10. **INNER JOIN:** Retrieving student names along with their enrolled course names.
11. **LEFT JOIN:** Listing all students regardless of whether they are enrolled in a course.
12. **Subqueries:** Identifying students in high-capacity courses (> 10 students).
13. **Date Extraction:** Extracting the enrollment year using `YEAR()`.
14. **String Manipulation:** Concatenating instructor first and last names.
15. **Window Functions:** Calculating a running total of enrolled students using `COUNT() OVER()`.
16. **Conditional Logic:** Categorizing students into 'Senior' or 'Junior' using `CASE` and `TIMESTAMPDIFF`.

---

