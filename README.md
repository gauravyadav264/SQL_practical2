CREATE DATABASE college_2 → TRUE: Creates a new database named college_2.
USE college_2 → TRUE: Selects the college_2 database for use.
Department table → TRUE: Stores department ID and department name.
Student_2 table → TRUE: Stores student details like roll number, name, email, Aadhaar number, and department.
Primary Key → TRUE: dept_id and roll_no must be unique and cannot be empty.
Unique Constraint → TRUE: Email, Aadhaar number, and department name cannot have duplicate values.
Foreign Key → TRUE: dept_id connects students and courses with the Department table.
Course table → TRUE: Stores course information such as DBMS and Circuits.
Enrollment table → TRUE: Stores student-course enrollment, semester, and grade. Semester must be between 1 and 8.
Enrollment of Nilisha → TRUE: Student 101 can take two different courses (501 and 502) in semester 3 because the courses are different.
